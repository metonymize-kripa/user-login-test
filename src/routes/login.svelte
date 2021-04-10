<script>
    import { goto } from '@sapper/app';
    
    let email = '';
    let password = '';

    async function login() {
        try {
            //firebase.auth().signInWithEmailAndPassword(email, password).then((res) => {
            //    goto('/dashboard');
            //});
        } catch(e) {
            let message = e.message || e;
            console.log("Something went wrong:", message);
        }
    }
</script>

<h1>Login form</h1>

<input type="email" bind:value={email} placeholder="your email"/>
<br />

<input type="password" bind:value={password} placeholder="your password"/>
<br />

<button on:click={login}>Login</button>
