<script>
    import Nav from '../components/Nav.svelte';
    import { onMount } from 'svelte';
    import { stores } from '@sapper/app';

    export let segment;

    const { session } = stores();

    onMount(async () => {
        firebase.auth().onIdTokenChanged(async (user) => {
            try {
                if (!user) {
                    console.log(`User does not exist`);
                    $session.user = false;
                    return;
                }
                const token = await user.getIdToken();
                $session.user = token;
                console.log(`User found and session set!`);

            } catch (e) {
                console.log(`Something went wrong`);
                $session.user = false;
                return;
            }
        });
    });
</script>

<style>
	main {
		position: relative;
		max-width: 56em;
		background-color: white;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>

<Nav {segment}/>

<main>
	<slot></slot>
</main>
