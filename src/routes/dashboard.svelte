<script context="module">
    import { goto } from '@sapper/app';

	export async function preload(page, session) {
        let { user } = session;
//        if (!user) {
//            return this.redirect(302, '/login');
//        }
    }
    
    async function logout() {
        return firebase.auth().signOut().then(() => {
            goto('/login');
        });
    }
</script>


<h1>This is our protected dashboard! Only visible when you are logged in with Firebase</h1> 
<button on:click={logout}>Logout</button>

<svg>
<defs>
  <style type='text/css'><![CDATA[
    .svglite line, .svglite polyline, .svglite polygon, .svglite path, .svglite rect, .svglite circle {
      fill: none;
      stroke: #000000;
      stroke-linecap: round;
      stroke-linejoin: round;
      stroke-miterlimit: 10.00;
    }
  ]]></style>
</defs>
<rect width='100%' height='100%' style='stroke: none; fill: #FFFFFF;'/>
<defs>
  <clipPath id='cpMC4wMHw3MjAuMDB8MC4wMHw1NzYuMDA='>
    <rect x='0.00' y='0.00' width='720.00' height='576.00' />
  </clipPath>
</defs>
<g clip-path='url(#cpMC4wMHw3MjAuMDB8MC4wMHw1NzYuMDA=)'>
</g>
<defs>
  <clipPath id='cpOTAuMDZ8NjkwLjExfDU2LjUzfDUyMS40MQ=='>
    <rect x='90.06' y='56.53' width='600.06' height='464.88' />
  </clipPath>
</defs>
<g clip-path='url(#cpOTAuMDZ8NjkwLjExfDU2LjUzfDUyMS40MQ==)'>
<polyline points='135.07,521.41 135.07,56.53 ' style='stroke-width: 0.32; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='257.67,521.41 257.67,56.53 ' style='stroke-width: 0.32; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='380.28,521.41 380.28,56.53 ' style='stroke-width: 0.32; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='502.88,521.41 502.88,56.53 ' style='stroke-width: 0.32; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='625.48,521.41 625.48,56.53 ' style='stroke-width: 0.32; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,501.37 690.11,501.37 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,467.97 690.11,467.97 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,434.56 690.11,434.56 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,401.16 690.11,401.16 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,367.76 690.11,367.76 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,334.35 690.11,334.35 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,300.95 690.11,300.95 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,267.55 690.11,267.55 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,234.14 690.11,234.14 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,200.74 690.11,200.74 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,167.34 690.11,167.34 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='90.06,133.94 690.11,133.94 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='196.37,521.41 196.37,56.53 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='318.97,521.41 318.97,56.53 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='441.58,521.41 441.58,56.53 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='564.18,521.41 564.18,56.53 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polyline points='686.78,521.41 686.78,56.53 ' style='stroke-width: 0.43; stroke: #CCCCCC; stroke-linecap: butt;' />
<polygon points='189.92,132.84 190.99,132.69 192.06,132.53 192.06,133.94 190.99,133.94 189.92,133.94 ' style='stroke-width: 0.38; stroke: #5002A2; fill: #5002A2;' />
<polygon points='192.06,132.53 193.13,132.36 193.13,133.94 192.06,133.94 ' style='stroke-width: 0.38; stroke: #5102A3; fill: #5102A3;' />
<polygon points='193.13,132.36 194.19,132.17 194.19,133.94 193.13,133.94 ' style='stroke-width: 0.38; stroke: #5202A3; fill: #5202A3;' />
<polygon points='194.19,132.17 195.26,131.97 195.26,133.94 194.19,133.94 ' style='stroke-width: 0.38; stroke: #5302A3; fill: #5302A3;' />
<polygon points='195.26,131.97 196.33,131.75 196.33,133.94 195.26,133.94 ' style='stroke-width: 0.38; stroke: #5402A3; fill: #5402A3;' />
<polygon points='196.33,131.75 197.40,131.51 198.46,131.26 198.46,133.94 197.40,133.94 196.33,133.94 ' style='stroke-width: 0.38; stroke: #5502A4; fill: #5502A4;' />
<polygon points='198.46,131.26 199.53,130.99 199.53,133.94 198.46,133.94 ' style='stroke-width: 0.38; stroke: #5601A4; fill: #5601A4;' />
<polygon points='199.53,130.99 200.60,130.70 200.60,133.94 199.53,133.94 ' style='stroke-width: 0.38; stroke: #5701A4; fill: #5701A4;' />
<polygon points='200.60,130.70 201.67,130.39 202.73,130.08 202.73,133.94 201.67,133.94 200.60,133.94 ' style='stroke-width: 0.38; stroke: #5801A4; fill: #5801A4;' />
<polygon points='202.73,130.08 203.80,129.74 203.80,133.94 202.73,133.94 ' style='stroke-width: 0.38; stroke: #5901A5; fill: #5901A5;' />
<polygon points='203.80,129.74 204.87,129.39 204.87,133.94 203.80,133.94 ' style='stroke-width: 0.38; stroke: #5A01A5; fill: #5A01A5;' />
<polygon points='204.87,129.39 205.94,129.02 207.00,128.64 207.00,133.94 205.94,133.94 204.87,133.94 ' style='stroke-width: 0.38; stroke: #5B01A5; fill: #5B01A5;' />
<polygon points='207.00,128.64 208.07,128.24 208.07,133.94 207.00,133.94 ' style='stroke-width: 0.38; stroke: #5C01A6; fill: #5C01A6;' />
<polygon points='208.07,128.24 209.14,127.84 209.14,133.94 208.07,133.94 ' style='stroke-width: 0.38; stroke: #5D01A6; fill: #5D01A6;' />
<polygon points='209.14,127.84 210.21,127.41 210.21,133.94 209.14,133.94 ' style='stroke-width: 0.38; stroke: #5E01A6; fill: #5E01A6;' />
<polygon points='210.21,127.41 211.27,126.98 211.27,133.94 210.21,133.94 ' style='stroke-width: 0.38; stroke: #5F01A6; fill: #5F01A6;' />
<polygon points='211.27,126.98 212.34,126.54 213.41,126.08 213.41,133.94 212.34,133.94 211.27,133.94 ' style='stroke-width: 0.38; stroke: #6001A6; fill: #6001A6;' />
<polygon points='213.41,126.08 214.48,125.62 214.48,133.94 213.41,133.94 ' style='stroke-width: 0.38; stroke: #6100A7; fill: #6100A7;' />
<polygon points='214.48,125.62 215.54,125.14 215.54,133.94 214.48,133.94 ' style='stroke-width: 0.38; stroke: #6200A7; fill: #6200A7;' />
<polygon points='215.54,125.14 216.61,124.66 217.68,124.17 217.68,133.94 216.61,133.94 215.54,133.94 ' style='stroke-width: 0.38; stroke: #6300A7; fill: #6300A7;' />
<polygon points='217.68,124.17 218.75,123.68 218.75,133.94 217.68,133.94 ' style='stroke-width: 0.38; stroke: #6400A7; fill: #6400A7;' />
<polygon points='218.75,123.68 219.81,123.18 219.81,133.94 218.75,133.94 ' style='stroke-width: 0.38; stroke: #6500A7; fill: #6500A7;' />
<polygon points='219.81,123.18 220.88,122.68 221.95,122.17 221.95,133.94 220.88,133.94 219.81,133.94 ' style='stroke-width: 0.38; stroke: #6600A7; fill: #6600A7;' />
<polygon points='221.95,122.17 223.02,121.67 223.02,133.94 221.95,133.94 ' style='stroke-width: 0.38; stroke: #6700A8; fill: #6700A8;' />
<polygon points='223.02,121.67 224.08,121.16 224.08,133.94 223.02,133.94 ' style='stroke-width: 0.38; stroke: #6800A8; fill: #6800A8;' />
<polygon points='224.08,121.16 225.15,120.66 226.22,120.15 226.22,133.94 225.15,133.94 224.08,133.94 ' style='stroke-width: 0.38; stroke: #6900A8; fill: #6900A8;' />
<polygon points='226.22,120.15 227.29,119.65 227.29,133.94 226.22,133.94 ' style='stroke-width: 0.38; stroke: #6A00A8; fill: #6A00A8;' />
<polygon points='227.29,119.65 228.35,119.16 228.35,133.94 227.29,133.94 ' style='stroke-width: 0.38; stroke: #6B00A8; fill: #6B00A8;' />
<polygon points='228.35,119.16 229.42,118.68 229.42,133.94 228.35,133.94 ' style='stroke-width: 0.38; stroke: #6C00A8; fill: #6C00A8;' />
<polygon points='229.42,118.68 230.49,118.21 230.49,133.94 229.42,133.94 ' style='stroke-width: 0.38; stroke: #6D00A8; fill: #6D00A8;' />
<polygon points='230.49,118.21 231.56,117.75 232.62,117.31 232.62,133.94 231.56,133.94 230.49,133.94 ' style='stroke-width: 0.38; stroke: #6E00A8; fill: #6E00A8;' />
<polygon points='232.62,117.31 233.69,116.89 233.69,133.94 232.62,133.94 ' style='stroke-width: 0.38; stroke: #6F00A8; fill: #6F00A8;' />
<polygon points='233.69,116.89 234.76,116.49 234.76,133.94 233.69,133.94 ' style='stroke-width: 0.38; stroke: #7000A8; fill: #7000A8;' />
<polygon points='234.76,116.49 235.83,116.11 236.89,115.75 236.89,133.94 235.83,133.94 234.76,133.94 ' style='stroke-width: 0.38; stroke: #7100A8; fill: #7100A8;' />
<polygon points='236.89,115.75 237.96,115.43 237.96,133.94 236.89,133.94 ' style='stroke-width: 0.38; stroke: #7201A8; fill: #7201A8;' />
<polygon points='237.96,115.43 239.03,115.14 239.03,133.94 237.96,133.94 ' style='stroke-width: 0.38; stroke: #7301A8; fill: #7301A8;' />
<polygon points='239.03,115.14 240.10,114.89 241.16,114.66 241.16,133.94 240.10,133.94 239.03,133.94 ' style='stroke-width: 0.38; stroke: #7401A8; fill: #7401A8;' />
<polygon points='241.16,114.66 242.23,114.48 242.23,133.94 241.16,133.94 ' style='stroke-width: 0.38; stroke: #7501A8; fill: #7501A8;' />
<polygon points='242.23,114.48 243.30,114.33 243.30,133.94 242.23,133.94 ' style='stroke-width: 0.38; stroke: #7601A8; fill: #7601A8;' />
<polygon points='243.30,114.33 244.37,114.23 245.43,114.16 245.43,133.94 244.37,133.94 243.30,133.94 ' style='stroke-width: 0.38; stroke: #7701A8; fill: #7701A8;' />
<polygon points='245.43,114.16 246.50,114.13 246.50,133.94 245.43,133.94 ' style='stroke-width: 0.38; stroke: #7801A8; fill: #7801A8;' />
<polygon points='246.50,114.13 247.57,114.14 247.57,133.94 246.50,133.94 ' style='stroke-width: 0.38; stroke: #7901A8; fill: #7901A8;' />
<polygon points='247.57,114.14 248.64,114.19 249.70,114.27 249.70,133.94 248.64,133.94 247.57,133.94 ' style='stroke-width: 0.38; stroke: #7A02A8; fill: #7A02A8;' />
<polygon points='249.70,114.27 250.77,114.38 250.77,133.94 249.70,133.94 ' style='stroke-width: 0.38; stroke: #7B02A8; fill: #7B02A8;' />
<polygon points='250.77,114.38 251.84,114.52 251.84,133.94 250.77,133.94 ' style='stroke-width: 0.38; stroke: #7C02A8; fill: #7C02A8;' />
<polygon points='251.84,114.52 252.91,114.68 253.97,114.87 253.97,133.94 252.91,133.94 251.84,133.94 ' style='stroke-width: 0.38; stroke: #7D03A8; fill: #7D03A8;' />
<polygon points='253.97,114.87 255.04,115.07 255.04,133.94 253.97,133.94 ' style='stroke-width: 0.38; stroke: #7E03A8; fill: #7E03A8;' />
<polygon points='255.04,115.07 256.11,115.28 256.11,133.94 255.04,133.94 ' style='stroke-width: 0.38; stroke: #7F03A8; fill: #7F03A8;' />
<polygon points='256.11,115.28 257.18,115.49 258.24,115.70 258.24,133.94 257.18,133.94 256.11,133.94 ' style='stroke-width: 0.38; stroke: #8004A8; fill: #8004A8;' />
<polygon points='258.24,115.70 259.31,115.91 259.31,133.94 258.24,133.94 ' style='stroke-width: 0.38; stroke: #8104A7; fill: #8104A7;' />
<polygon points='259.31,115.91 260.38,116.10 260.38,133.94 259.31,133.94 ' style='stroke-width: 0.38; stroke: #8204A7; fill: #8204A7;' />
<polygon points='260.38,116.10 261.45,116.27 262.51,116.42 262.51,133.94 261.45,133.94 260.38,133.94 ' style='stroke-width: 0.38; stroke: #8305A7; fill: #8305A7;' />
<polygon points='262.51,116.42 263.58,116.54 263.58,133.94 262.51,133.94 ' style='stroke-width: 0.38; stroke: #8405A7; fill: #8405A7;' />
<polygon points='263.58,116.54 264.65,116.62 264.65,133.94 263.58,133.94 ' style='stroke-width: 0.38; stroke: #8505A7; fill: #8505A7;' />
<polygon points='264.65,116.62 265.72,116.65 266.78,116.64 266.78,133.94 265.72,133.94 264.65,133.94 ' style='stroke-width: 0.38; stroke: #8606A6; fill: #8606A6;' />
<polygon points='266.78,116.64 267.85,116.58 268.92,116.47 268.92,133.94 267.85,133.94 266.78,133.94 ' style='stroke-width: 0.38; stroke: #8707A6; fill: #8707A6;' />
<polygon points='268.92,116.47 269.99,116.30 269.99,133.94 268.92,133.94 ' style='stroke-width: 0.38; stroke: #8808A6; fill: #8808A6;' />
<polygon points='269.99,116.30 271.05,116.06 271.05,133.94 269.99,133.94 ' style='stroke-width: 0.38; stroke: #8908A6; fill: #8908A6;' />
<polygon points='271.05,116.06 272.12,115.76 273.19,115.39 273.19,133.94 272.12,133.94 271.05,133.94 ' style='stroke-width: 0.38; stroke: #8A09A5; fill: #8A09A5;' />
<polygon points='273.19,115.39 274.26,114.95 274.26,133.94 273.19,133.94 ' style='stroke-width: 0.38; stroke: #8B0AA5; fill: #8B0AA5;' />
<polygon points='274.26,114.95 275.32,114.45 275.32,133.94 274.26,133.94 ' style='stroke-width: 0.38; stroke: #8C0AA5; fill: #8C0AA5;' />
<polygon points='275.32,114.45 276.39,113.85 277.46,113.19 277.46,133.94 276.39,133.94 275.32,133.94 ' style='stroke-width: 0.38; stroke: #8D0BA5; fill: #8D0BA5;' />
<polygon points='277.46,113.19 278.53,112.46 279.59,111.65 279.59,133.94 278.53,133.94 277.46,133.94 ' style='stroke-width: 0.38; stroke: #8E0CA4; fill: #8E0CA4;' />
<polygon points='279.59,111.65 280.66,110.78 280.66,133.94 279.59,133.94 ' style='stroke-width: 0.38; stroke: #8F0DA4; fill: #8F0DA4;' />
<polygon points='280.66,110.78 281.73,109.81 281.73,133.94 280.66,133.94 ' style='stroke-width: 0.38; stroke: #900DA4; fill: #900DA4;' />
<polygon points='281.73,109.81 282.80,108.77 283.87,107.67 283.87,133.94 282.80,133.94 281.73,133.94 ' style='stroke-width: 0.38; stroke: #910EA3; fill: #910EA3;' />
<polygon points='283.87,107.67 284.93,106.50 284.93,133.94 283.87,133.94 ' style='stroke-width: 0.38; stroke: #920FA3; fill: #920FA3;' />
<polygon points='284.93,106.50 286.00,105.26 286.00,133.94 284.93,133.94 ' style='stroke-width: 0.38; stroke: #930FA3; fill: #930FA3;' />
<polygon points='286.00,105.26 287.07,103.95 288.14,102.57 288.14,133.94 287.07,133.94 286.00,133.94 ' style='stroke-width: 0.38; stroke: #9410A2; fill: #9410A2;' />
<polygon points='288.14,102.57 289.20,101.14 289.20,133.94 288.14,133.94 ' style='stroke-width: 0.38; stroke: #9511A1; fill: #9511A1;' />
<polygon points='289.20,101.14 290.27,99.66 290.27,133.94 289.20,133.94 ' style='stroke-width: 0.38; stroke: #9512A1; fill: #9512A1;' />
<polygon points='290.27,99.66 291.34,98.13 291.34,133.94 290.27,133.94 ' style='stroke-width: 0.38; stroke: #9613A1; fill: #9613A1;' />
<polygon points='291.34,98.13 292.41,96.54 292.41,133.94 291.34,133.94 ' style='stroke-width: 0.38; stroke: #9713A1; fill: #9713A1;' />
<polygon points='292.41,96.54 293.47,94.91 294.54,93.25 294.54,133.94 293.47,133.94 292.41,133.94 ' style='stroke-width: 0.38; stroke: #9814A0; fill: #9814A0;' />
<polygon points='294.54,93.25 295.61,91.56 296.68,89.85 296.68,133.94 295.61,133.94 294.54,133.94 ' style='stroke-width: 0.38; stroke: #99159F; fill: #99159F;' />
<polygon points='296.68,89.85 297.74,88.12 297.74,133.94 296.68,133.94 ' style='stroke-width: 0.38; stroke: #9A169F; fill: #9A169F;' />
<polygon points='297.74,88.12 298.81,86.38 298.81,133.94 297.74,133.94 ' style='stroke-width: 0.38; stroke: #9B169F; fill: #9B169F;' />
<polygon points='298.81,86.38 299.88,84.63 300.95,82.90 300.95,133.94 299.88,133.94 298.81,133.94 ' style='stroke-width: 0.38; stroke: #9C179E; fill: #9C179E;' />
<polygon points='300.95,82.90 302.01,81.17 303.08,79.46 303.08,133.94 302.01,133.94 300.95,133.94 ' style='stroke-width: 0.38; stroke: #9D189D; fill: #9D189D;' />
<polygon points='303.08,79.46 304.15,77.78 304.15,133.94 303.08,133.94 ' style='stroke-width: 0.38; stroke: #9E199D; fill: #9E199D;' />
<polygon points='304.15,77.78 305.22,76.13 305.22,133.94 304.15,133.94 ' style='stroke-width: 0.38; stroke: #9F199D; fill: #9F199D;' />
<polygon points='305.22,76.13 306.28,74.52 307.35,72.95 307.35,133.94 306.28,133.94 305.22,133.94 ' style='stroke-width: 0.38; stroke: #A01A9C; fill: #A01A9C;' />
<polygon points='307.35,72.95 308.42,71.44 308.42,133.94 307.35,133.94 ' style='stroke-width: 0.38; stroke: #A11B9B; fill: #A11B9B;' />
<polygon points='308.42,71.44 309.49,69.98 309.49,133.94 308.42,133.94 ' style='stroke-width: 0.38; stroke: #A11C9B; fill: #A11C9B;' />
<polygon points='309.49,69.98 310.55,68.59 311.62,67.25 311.62,133.94 310.55,133.94 309.49,133.94 ' style='stroke-width: 0.38; stroke: #A21D9A; fill: #A21D9A;' />
<polygon points='311.62,67.25 312.69,65.98 312.69,133.94 311.62,133.94 ' style='stroke-width: 0.38; stroke: #A31E9A; fill: #A31E9A;' />
<polygon points='312.69,65.98 313.76,64.79 313.76,133.94 312.69,133.94 ' style='stroke-width: 0.38; stroke: #A41E9A; fill: #A41E9A;' />
<polygon points='313.76,64.79 314.82,63.67 315.89,62.63 315.89,133.94 314.82,133.94 313.76,133.94 ' style='stroke-width: 0.38; stroke: #A51F99; fill: #A51F99;' />
<polygon points='315.89,62.63 316.96,61.67 318.03,60.78 318.03,133.94 316.96,133.94 315.89,133.94 ' style='stroke-width: 0.38; stroke: #A62098; fill: #A62098;' />
<polygon points='318.03,60.78 319.09,59.97 320.16,59.26 320.16,133.94 319.09,133.94 318.03,133.94 ' style='stroke-width: 0.38; stroke: #A72197; fill: #A72197;' />
<polygon points='320.16,59.26 321.23,58.62 321.23,133.94 320.16,133.94 ' style='stroke-width: 0.38; stroke: #A82296; fill: #A82296;' />
<polygon points='321.23,58.62 322.30,58.07 322.30,133.94 321.23,133.94 ' style='stroke-width: 0.38; stroke: #A92296; fill: #A92296;' />
<polygon points='322.30,58.07 323.36,57.60 324.43,57.20 324.43,133.94 323.36,133.94 322.30,133.94 ' style='stroke-width: 0.38; stroke: #AA2395; fill: #AA2395;' />
<polygon points='324.43,57.20 325.50,56.91 325.50,133.94 324.43,133.94 ' style='stroke-width: 0.38; stroke: #AB2494; fill: #AB2494;' />
<polygon points='325.50,56.91 326.57,56.70 326.57,133.94 325.50,133.94 ' style='stroke-width: 0.38; stroke: #AB2594; fill: #AB2594;' />
<polygon points='326.57,56.70 327.63,56.58 328.70,56.53 328.70,133.94 327.63,133.94 326.57,133.94 ' style='stroke-width: 0.38; stroke: #AC2694; fill: #AC2694;' />
<polygon points='328.70,56.53 329.77,56.57 330.84,56.71 330.84,133.94 329.77,133.94 328.70,133.94 ' style='stroke-width: 0.38; stroke: #AD2793; fill: #AD2793;' />
<polygon points='330.84,56.71 331.90,56.94 331.90,133.94 330.84,133.94 ' style='stroke-width: 0.38; stroke: #AE2892; fill: #AE2892;' />
<polygon points='331.90,56.94 332.97,57.25 332.97,133.94 331.90,133.94 ' style='stroke-width: 0.38; stroke: #AF2892; fill: #AF2892;' />
<polygon points='332.97,57.25 334.04,57.65 335.11,58.13 335.11,133.94 334.04,133.94 332.97,133.94 ' style='stroke-width: 0.38; stroke: #B02991; fill: #B02991;' />
<polygon points='335.11,58.13 336.17,58.70 337.24,59.37 337.24,133.94 336.17,133.94 335.11,133.94 ' style='stroke-width: 0.38; stroke: #B12A90; fill: #B12A90;' />
<polygon points='337.24,59.37 338.31,60.11 339.38,60.93 339.38,133.94 338.31,133.94 337.24,133.94 ' style='stroke-width: 0.38; stroke: #B22B8F; fill: #B22B8F;' />
<polygon points='339.38,60.93 340.44,61.82 340.44,133.94 339.38,133.94 ' style='stroke-width: 0.38; stroke: #B32C8E; fill: #B32C8E;' />
<polygon points='340.44,61.82 341.51,62.80 341.51,133.94 340.44,133.94 ' style='stroke-width: 0.38; stroke: #B32D8E; fill: #B32D8E;' />
<polygon points='341.51,62.80 342.58,63.85 343.65,64.97 343.65,133.94 342.58,133.94 341.51,133.94 ' style='stroke-width: 0.38; stroke: #B42E8D; fill: #B42E8D;' />
<polygon points='343.65,64.97 344.71,66.15 345.78,67.39 345.78,133.94 344.71,133.94 343.65,133.94 ' style='stroke-width: 0.38; stroke: #B52F8C; fill: #B52F8C;' />
<polygon points='345.78,67.39 346.85,68.68 347.92,70.03 347.92,133.94 346.85,133.94 345.78,133.94 ' style='stroke-width: 0.38; stroke: #B6308B; fill: #B6308B;' />
<polygon points='347.92,70.03 348.98,71.41 350.05,72.83 350.05,133.94 348.98,133.94 347.92,133.94 ' style='stroke-width: 0.38; stroke: #B7318A; fill: #B7318A;' />
<polygon points='350.05,72.83 351.12,74.28 351.12,133.94 350.05,133.94 ' style='stroke-width: 0.38; stroke: #B83289; fill: #B83289;' />
<polygon points='351.12,74.28 352.19,75.75 352.19,133.94 351.12,133.94 ' style='stroke-width: 0.38; stroke: #B93289; fill: #B93289;' />
<polygon points='352.19,75.75 353.25,77.24 354.32,78.73 354.32,133.94 353.25,133.94 352.19,133.94 ' style='stroke-width: 0.38; stroke: #BA3388; fill: #BA3388;' />
<polygon points='354.32,78.73 355.39,80.23 356.46,81.72 356.46,133.94 355.39,133.94 354.32,133.94 ' style='stroke-width: 0.38; stroke: #BB3488; fill: #BB3488;' />
<polygon points='356.46,81.72 357.52,83.20 357.52,133.94 356.46,133.94 ' style='stroke-width: 0.38; stroke: #BC3587; fill: #BC3587;' />
<polygon points='357.52,83.20 358.59,84.66 358.59,133.94 357.52,133.94 ' style='stroke-width: 0.38; stroke: #BC3687; fill: #BC3687;' />
<polygon points='358.59,84.66 359.66,86.09 360.73,87.50 360.73,133.94 359.66,133.94 358.59,133.94 ' style='stroke-width: 0.38; stroke: #BD3786; fill: #BD3786;' />
<polygon points='360.73,87.50 361.79,88.86 362.86,90.19 362.86,133.94 361.79,133.94 360.73,133.94 ' style='stroke-width: 0.38; stroke: #BE3885; fill: #BE3885;' />
<polygon points='362.86,90.19 363.93,91.46 365.00,92.68 365.00,133.94 363.93,133.94 362.86,133.94 ' style='stroke-width: 0.38; stroke: #BF3984; fill: #BF3984;' />
<polygon points='365.00,92.68 366.06,93.85 367.13,94.96 367.13,133.94 366.06,133.94 365.00,133.94 ' style='stroke-width: 0.38; stroke: #C03A83; fill: #C03A83;' />
<polygon points='367.13,94.96 368.20,96.01 369.27,96.98 369.27,133.94 368.20,133.94 367.13,133.94 ' style='stroke-width: 0.38; stroke: #C13B82; fill: #C13B82;' />
<polygon points='369.27,96.98 370.33,97.88 371.40,98.73 371.40,133.94 370.33,133.94 369.27,133.94 ' style='stroke-width: 0.38; stroke: #C23C81; fill: #C23C81;' />
<polygon points='371.40,98.73 372.47,99.50 373.54,100.22 373.54,133.94 372.47,133.94 371.40,133.94 ' style='stroke-width: 0.38; stroke: #C33D80; fill: #C33D80;' />
<polygon points='373.54,100.22 374.60,100.86 374.60,133.94 373.54,133.94 ' style='stroke-width: 0.38; stroke: #C43E7F; fill: #C43E7F;' />
<polygon points='374.60,100.86 375.67,101.44 375.67,133.94 374.60,133.94 ' style='stroke-width: 0.38; stroke: #C43F7F; fill: #C43F7F;' />
<polygon points='375.67,101.44 376.74,101.96 377.81,102.44 377.81,133.94 376.74,133.94 375.67,133.94 ' style='stroke-width: 0.38; stroke: #C5407E; fill: #C5407E;' />
<polygon points='377.81,102.44 378.87,102.86 379.94,103.24 379.94,133.94 378.87,133.94 377.81,133.94 ' style='stroke-width: 0.38; stroke: #C6417D; fill: #C6417D;' />
<polygon points='379.94,103.24 381.01,103.57 382.08,103.88 382.08,133.94 381.01,133.94 379.94,133.94 ' style='stroke-width: 0.38; stroke: #C7427C; fill: #C7427C;' />
<polygon points='382.08,103.88 383.14,104.17 384.21,104.44 384.21,133.94 383.14,133.94 382.08,133.94 ' style='stroke-width: 0.38; stroke: #C8437B; fill: #C8437B;' />
<polygon points='384.21,104.44 385.28,104.70 386.35,104.96 386.35,133.94 385.28,133.94 384.21,133.94 ' style='stroke-width: 0.38; stroke: #C9447A; fill: #C9447A;' />
<polygon points='386.35,104.96 387.42,105.23 388.48,105.52 388.48,133.94 387.42,133.94 386.35,133.94 ' style='stroke-width: 0.38; stroke: #CA457A; fill: #CA457A;' />
<polygon points='388.48,105.52 389.55,105.82 390.62,106.14 390.62,133.94 389.55,133.94 388.48,133.94 ' style='stroke-width: 0.38; stroke: #CB4679; fill: #CB4679;' />
<polygon points='390.62,106.14 391.69,106.51 391.69,133.94 390.62,133.94 ' style='stroke-width: 0.38; stroke: #CC4778; fill: #CC4778;' />
<polygon points='391.69,106.51 392.75,106.91 392.75,133.94 391.69,133.94 ' style='stroke-width: 0.38; stroke: #CC4878; fill: #CC4878;' />
<polygon points='392.75,106.91 393.82,107.35 393.82,133.94 392.75,133.94 ' style='stroke-width: 0.38; stroke: #CC4877; fill: #CC4877;' />
<polygon points='393.82,107.35 394.89,107.83 394.89,133.94 393.82,133.94 ' style='stroke-width: 0.38; stroke: #CC4977; fill: #CC4977;' />
<polygon points='394.89,107.83 395.96,108.36 397.02,108.94 397.02,133.94 395.96,133.94 394.89,133.94 ' style='stroke-width: 0.38; stroke: #CD4A76; fill: #CD4A76;' />
<polygon points='397.02,108.94 398.09,109.57 399.16,110.24 399.16,133.94 398.09,133.94 397.02,133.94 ' style='stroke-width: 0.38; stroke: #CE4B75; fill: #CE4B75;' />
<polygon points='399.16,110.24 400.23,110.96 401.29,111.72 401.29,133.94 400.23,133.94 399.16,133.94 ' style='stroke-width: 0.38; stroke: #CF4C74; fill: #CF4C74;' />
<polygon points='401.29,111.72 402.36,112.52 403.43,113.36 403.43,133.94 402.36,133.94 401.29,133.94 ' style='stroke-width: 0.38; stroke: #D04D73; fill: #D04D73;' />
<polygon points='403.43,113.36 404.50,114.23 405.56,115.12 405.56,133.94 404.50,133.94 403.43,133.94 ' style='stroke-width: 0.38; stroke: #D14E72; fill: #D14E72;' />
<polygon points='405.56,115.12 406.63,116.03 407.70,116.95 407.70,133.94 406.63,133.94 405.56,133.94 ' style='stroke-width: 0.38; stroke: #D24F71; fill: #D24F71;' />
<polygon points='407.70,116.95 408.77,117.89 408.77,133.94 407.70,133.94 ' style='stroke-width: 0.38; stroke: #D35071; fill: #D35071;' />
<polygon points='408.77,117.89 409.83,118.82 409.83,133.94 408.77,133.94 ' style='stroke-width: 0.38; stroke: #D35171; fill: #D35171;' />
<polygon points='409.83,118.82 410.90,119.76 411.97,120.68 411.97,133.94 410.90,133.94 409.83,133.94 ' style='stroke-width: 0.38; stroke: #D45270; fill: #D45270;' />
<polygon points='411.97,120.68 413.04,121.59 414.10,122.47 414.10,133.94 413.04,133.94 411.97,133.94 ' style='stroke-width: 0.38; stroke: #D5536F; fill: #D5536F;' />
<polygon points='414.10,122.47 415.17,123.34 416.24,124.17 416.24,133.94 415.17,133.94 414.10,133.94 ' style='stroke-width: 0.38; stroke: #D5546E; fill: #D5546E;' />
<polygon points='416.24,124.17 417.31,124.98 418.37,125.75 418.37,133.94 417.31,133.94 416.24,133.94 ' style='stroke-width: 0.38; stroke: #D6556D; fill: #D6556D;' />
<polygon points='418.37,125.75 419.44,126.48 420.51,127.17 420.51,133.94 419.44,133.94 418.37,133.94 ' style='stroke-width: 0.38; stroke: #D7566C; fill: #D7566C;' />
<polygon points='420.51,127.17 421.58,127.82 422.64,128.44 422.64,133.94 421.58,133.94 420.51,133.94 ' style='stroke-width: 0.38; stroke: #D8576B; fill: #D8576B;' />
<polygon points='422.64,128.44 423.71,129.00 424.78,129.53 424.78,133.94 423.71,133.94 422.64,133.94 ' style='stroke-width: 0.38; stroke: #D9586A; fill: #D9586A;' />
<polygon points='424.78,129.53 425.85,130.01 425.85,133.94 424.78,133.94 ' style='stroke-width: 0.38; stroke: #DA596A; fill: #DA596A;' />
<polygon points='425.85,130.01 426.91,130.46 426.91,133.94 425.85,133.94 ' style='stroke-width: 0.38; stroke: #DA5A6A; fill: #DA5A6A;' />
<polygon points='426.91,130.46 427.98,130.87 429.05,131.24 429.05,133.94 427.98,133.94 426.91,133.94 ' style='stroke-width: 0.38; stroke: #DA5B69; fill: #DA5B69;' />
<polygon points='429.05,131.24 430.12,131.57 431.18,131.87 431.18,133.94 430.12,133.94 429.05,133.94 ' style='stroke-width: 0.38; stroke: #DB5C68; fill: #DB5C68;' />
<polygon points='431.18,131.87 432.25,132.14 433.32,132.39 433.32,133.94 432.25,133.94 431.18,133.94 ' style='stroke-width: 0.38; stroke: #DC5D67; fill: #DC5D67;' />
<polygon points='433.32,132.39 434.39,132.60 435.45,132.79 435.45,133.94 434.39,133.94 433.32,133.94 ' style='stroke-width: 0.38; stroke: #DD5E66; fill: #DD5E66;' />
<polygon points='435.45,132.79 435.45,133.94 ' style='stroke-width: 0.38; stroke: #DE5F65; fill: #DE5F65;' />
<polyline points='189.92,132.84 190.99,132.69 192.06,132.53 193.13,132.36 194.19,132.17 195.26,131.97 196.33,131.75 197.40,131.51 198.46,131.26 199.53,130.99 200.60,130.70 201.67,130.39 202.73,130.08 203.80,129.74 204.87,129.39 205.94,129.02 207.00,128.64 208.07,128.24 209.14,127.84 210.21,127.41 211.27,126.98 212.34,126.54 213.41,126.08 214.48,125.62 215.54,125.14 216.61,124.66 217.68,124.17 218.75,123.68 219.81,123.18 220.88,122.68 221.95,122.17 223.02,121.67 224.08,121.16 225.15,120.66 226.22,120.15 227.29,119.65 228.35,119.16 229.42,118.68 230.49,118.21 231.56,117.75 232.62,117.31 233.69,116.89 234.76,116.49 235.83,116.11 236.89,115.75 237.96,115.43 239.03,115.14 240.10,114.89 241.16,114.66 242.23,114.48 243.30,114.33 244.37,114.23 245.43,114.16 246.50,114.13 247.57,114.14 248.64,114.19 249.70,114.27 250.77,114.38 251.84,114.52 252.91,114.68 253.97,114.87 255.04,115.07 256.11,115.28 257.18,115.49 258.24,115.70 259.31,115.91 260.38,116.10 261.45,116.27 262.51,116.42 263.58,116.54 264.65,116.62 265.72,116.65 266.78,116.64 267.85,116.58 268.92,116.47 269.99,116.30 271.05,116.06 272.12,115.76 273.19,115.39 274.26,114.95 275.32,114.45 276.39,113.85 277.46,113.19 278.53,112.46 279.59,111.65 280.66,110.78 281.73,109.81 282.80,108.77 283.87,107.67 284.93,106.50 286.00,105.26 287.07,103.95 288.14,102.57 289.20,101.14 290.27,99.66 291.34,98.13 292.41,96.54 293.47,94.91 294.54,93.25 295.61,91.56 296.68,89.85 297.74,88.12 298.81,86.38 299.88,84.63 300.95,82.90 302.01,81.17 303.08,79.46 304.15,77.78 305.22,76.13 306.28,74.52 307.35,72.95 308.42,71.44 309.49,69.98 310.55,68.59 311.62,67.25 312.69,65.98 313.76,64.79 314.82,63.67 315.89,62.63 316.96,61.67 318.03,60.78 319.09,59.97 320.16,59.26 321.23,58.62 322.30,58.07 323.36,57.60 324.43,57.20 325.50,56.91 326.57,56.70 327.63,56.58 328.70,56.53 329.77,56.57 330.84,56.71 331.90,56.94 332.97,57.25 334.04,57.65 335.11,58.13 336.17,58.70 337.24,59.37 338.31,60.11 339.38,60.93 340.44,61.82 341.51,62.80 342.58,63.85 343.65,64.97 344.71,66.15 345.78,67.39 346.85,68.68 347.92,70.03 348.98,71.41 350.05,72.83 351.12,74.28 352.19,75.75 353.25,77.24 354.32,78.73 355.39,80.23 356.46,81.72 357.52,83.20 358.59,84.66 359.66,86.09 360.73,87.50 361.79,88.86 362.86,90.19 363.93,91.46 365.00,92.68 366.06,93.85 367.13,94.96 368.20,96.01 369.27,96.98 370.33,97.88 371.40,98.73 372.47,99.50 373.54,100.22 374.60,100.86 375.67,101.44 376.74,101.96 377.81,102.44 378.87,102.86 379.94,103.24 381.01,103.57 382.08,103.88 383.14,104.17 384.21,104.44 385.28,104.70 386.35,104.96 387.42,105.23 388.48,105.52 389.55,105.82 390.62,106.14 391.69,106.51 392.75,106.91 393.82,107.35 394.89,107.83 395.96,108.36 397.02,108.94 398.09,109.57 399.16,110.24 400.23,110.96 401.29,111.72 402.36,112.52 403.43,113.36 404.50,114.23 405.56,115.12 406.63,116.03 407.70,116.95 408.77,117.89 409.83,118.82 410.90,119.76 411.97,120.68 413.04,121.59 414.10,122.47 415.17,123.34 416.24,124.17 417.31,124.98 418.37,125.75 419.44,126.48 420.51,127.17 421.58,127.82 422.64,128.44 423.71,129.00 424.78,129.53 425.85,130.01 426.91,130.46 427.98,130.87 429.05,131.24 430.12,131.57 431.18,131.87 432.25,132.14 433.32,132.39 434.39,132.60 435.45,132.79 ' style='stroke-width: 1.07;' />
<polygon points='244.37,166.21 245.43,166.03 245.43,167.34 244.37,167.34 ' style='stroke-width: 0.38; stroke: #7701A8; fill: #7701A8;' />
<polygon points='245.43,166.03 246.50,165.83 246.50,167.34 245.43,167.34 ' style='stroke-width: 0.38; stroke: #7801A8; fill: #7801A8;' />
<polygon points='246.50,165.83 247.57,165.61 247.57,167.34 246.50,167.34 ' style='stroke-width: 0.38; stroke: #7901A8; fill: #7901A8;' />
<polygon points='247.57,165.61 248.64,165.35 249.70,165.07 249.70,167.34 248.64,167.34 247.57,167.34 ' style='stroke-width: 0.38; stroke: #7A02A8; fill: #7A02A8;' />
<polygon points='249.70,165.07 250.77,164.77 250.77,167.34 249.70,167.34 ' style='stroke-width: 0.38; stroke: #7B02A8; fill: #7B02A8;' />
<polygon points='250.77,164.77 251.84,164.43 251.84,167.34 250.77,167.34 ' style='stroke-width: 0.38; stroke: #7C02A8; fill: #7C02A8;' />
<polygon points='251.84,164.43 252.91,164.06 253.97,163.66 253.97,167.34 252.91,167.34 251.84,167.34 ' style='stroke-width: 0.38; stroke: #7D03A8; fill: #7D03A8;' />
<polygon points='253.97,163.66 255.04,163.22 255.04,167.34 253.97,167.34 ' style='stroke-width: 0.38; stroke: #7E03A8; fill: #7E03A8;' />
<polygon points='255.04,163.22 256.11,162.75 256.11,167.34 255.04,167.34 ' style='stroke-width: 0.38; stroke: #7F03A8; fill: #7F03A8;' />
<polygon points='256.11,162.75 257.18,162.25 258.24,161.72 258.24,167.34 257.18,167.34 256.11,167.34 ' style='stroke-width: 0.38; stroke: #8004A8; fill: #8004A8;' />
<polygon points='258.24,161.72 259.31,161.15 259.31,167.34 258.24,167.34 ' style='stroke-width: 0.38; stroke: #8104A7; fill: #8104A7;' />
<polygon points='259.31,161.15 260.38,160.54 260.38,167.34 259.31,167.34 ' style='stroke-width: 0.38; stroke: #8204A7; fill: #8204A7;' />
<polygon points='260.38,160.54 261.45,159.91 262.51,159.25 262.51,167.34 261.45,167.34 260.38,167.34 ' style='stroke-width: 0.38; stroke: #8305A7; fill: #8305A7;' />
<polygon points='262.51,159.25 263.58,158.56 263.58,167.34 262.51,167.34 ' style='stroke-width: 0.38; stroke: #8405A7; fill: #8405A7;' />
<polygon points='263.58,158.56 264.65,157.85 264.65,167.34 263.58,167.34 ' style='stroke-width: 0.38; stroke: #8505A7; fill: #8505A7;' />
<polygon points='264.65,157.85 265.72,157.11 266.78,156.36 266.78,167.34 265.72,167.34 264.65,167.34 ' style='stroke-width: 0.38; stroke: #8606A6; fill: #8606A6;' />
<polygon points='266.78,156.36 267.85,155.59 268.92,154.82 268.92,167.34 267.85,167.34 266.78,167.34 ' style='stroke-width: 0.38; stroke: #8707A6; fill: #8707A6;' />
<polygon points='268.92,154.82 269.99,154.03 269.99,167.34 268.92,167.34 ' style='stroke-width: 0.38; stroke: #8808A6; fill: #8808A6;' />
<polygon points='269.99,154.03 271.05,153.25 271.05,167.34 269.99,167.34 ' style='stroke-width: 0.38; stroke: #8908A6; fill: #8908A6;' />
<polygon points='271.05,153.25 272.12,152.47 273.19,151.70 273.19,167.34 272.12,167.34 271.05,167.34 ' style='stroke-width: 0.38; stroke: #8A09A5; fill: #8A09A5;' />
<polygon points='273.19,151.70 274.26,150.95 274.26,167.34 273.19,167.34 ' style='stroke-width: 0.38; stroke: #8B0AA5; fill: #8B0AA5;' />
<polygon points='274.26,150.95 275.32,150.20 275.32,167.34 274.26,167.34 ' style='stroke-width: 0.38; stroke: #8C0AA5; fill: #8C0AA5;' />
<polygon points='275.32,150.20 276.39,149.48 277.46,148.79 277.46,167.34 276.39,167.34 275.32,167.34 ' style='stroke-width: 0.38; stroke: #8D0BA5; fill: #8D0BA5;' />
<polygon points='277.46,148.79 278.53,148.12 279.59,147.48 279.59,167.34 278.53,167.34 277.46,167.34 ' style='stroke-width: 0.38; stroke: #8E0CA4; fill: #8E0CA4;' />
<polygon points='279.59,147.48 280.66,146.87 280.66,167.34 279.59,167.34 ' style='stroke-width: 0.38; stroke: #8F0DA4; fill: #8F0DA4;' />
<polygon points='280.66,146.87 281.73,146.31 281.73,167.34 280.66,167.34 ' style='stroke-width: 0.38; stroke: #900DA4; fill: #900DA4;' />
<polygon points='281.73,146.31 282.80,145.77 283.87,145.27 283.87,167.34 282.80,167.34 281.73,167.34 ' style='stroke-width: 0.38; stroke: #910EA3; fill: #910EA3;' />
<polygon points='283.87,145.27 284.93,144.80 284.93,167.34 283.87,167.34 ' style='stroke-width: 0.38; stroke: #920FA3; fill: #920FA3;' />
<polygon points='284.93,144.80 286.00,144.37 286.00,167.34 284.93,167.34 ' style='stroke-width: 0.38; stroke: #930FA3; fill: #930FA3;' />
<polygon points='286.00,144.37 287.07,143.97 288.14,143.61 288.14,167.34 287.07,167.34 286.00,167.34 ' style='stroke-width: 0.38; stroke: #9410A2; fill: #9410A2;' />
<polygon points='288.14,143.61 289.20,143.27 289.20,167.34 288.14,167.34 ' style='stroke-width: 0.38; stroke: #9511A1; fill: #9511A1;' />
<polygon points='289.20,143.27 290.27,142.95 290.27,167.34 289.20,167.34 ' style='stroke-width: 0.38; stroke: #9512A1; fill: #9512A1;' />
<polygon points='290.27,142.95 291.34,142.66 291.34,167.34 290.27,167.34 ' style='stroke-width: 0.38; stroke: #9613A1; fill: #9613A1;' />
<polygon points='291.34,142.66 292.41,142.38 292.41,167.34 291.34,167.34 ' style='stroke-width: 0.38; stroke: #9713A1; fill: #9713A1;' />
<polygon points='292.41,142.38 293.47,142.12 294.54,141.87 294.54,167.34 293.47,167.34 292.41,167.34 ' style='stroke-width: 0.38; stroke: #9814A0; fill: #9814A0;' />
<polygon points='294.54,141.87 295.61,141.62 296.68,141.37 296.68,167.34 295.61,167.34 294.54,167.34 ' style='stroke-width: 0.38; stroke: #99159F; fill: #99159F;' />
<polygon points='296.68,141.37 297.74,141.12 297.74,167.34 296.68,167.34 ' style='stroke-width: 0.38; stroke: #9A169F; fill: #9A169F;' />
<polygon points='297.74,141.12 298.81,140.87 298.81,167.34 297.74,167.34 ' style='stroke-width: 0.38; stroke: #9B169F; fill: #9B169F;' />
<polygon points='298.81,140.87 299.88,140.60 300.95,140.33 300.95,167.34 299.88,167.34 298.81,167.34 ' style='stroke-width: 0.38; stroke: #9C179E; fill: #9C179E;' />
<polygon points='300.95,140.33 302.01,140.04 303.08,139.73 303.08,167.34 302.01,167.34 300.95,167.34 ' style='stroke-width: 0.38; stroke: #9D189D; fill: #9D189D;' />
<polygon points='303.08,139.73 304.15,139.41 304.15,167.34 303.08,167.34 ' style='stroke-width: 0.38; stroke: #9E199D; fill: #9E199D;' />
<polygon points='304.15,139.41 305.22,139.06 305.22,167.34 304.15,167.34 ' style='stroke-width: 0.38; stroke: #9F199D; fill: #9F199D;' />
<polygon points='305.22,139.06 306.28,138.70 307.35,138.31 307.35,167.34 306.28,167.34 305.22,167.34 ' style='stroke-width: 0.38; stroke: #A01A9C; fill: #A01A9C;' />
<polygon points='307.35,138.31 308.42,137.91 308.42,167.34 307.35,167.34 ' style='stroke-width: 0.38; stroke: #A11B9B; fill: #A11B9B;' />
<polygon points='308.42,137.91 309.49,137.48 309.49,167.34 308.42,167.34 ' style='stroke-width: 0.38; stroke: #A11C9B; fill: #A11C9B;' />
<polygon points='309.49,137.48 310.55,137.03 311.62,136.56 311.62,167.34 310.55,167.34 309.49,167.34 ' style='stroke-width: 0.38; stroke: #A21D9A; fill: #A21D9A;' />
<polygon points='311.62,136.56 312.69,136.08 312.69,167.34 311.62,167.34 ' style='stroke-width: 0.38; stroke: #A31E9A; fill: #A31E9A;' />
<polygon points='312.69,136.08 313.76,135.57 313.76,167.34 312.69,167.34 ' style='stroke-width: 0.38; stroke: #A41E9A; fill: #A41E9A;' />
<polygon points='313.76,135.57 314.82,135.05 315.89,134.52 315.89,167.34 314.82,167.34 313.76,167.34 ' style='stroke-width: 0.38; stroke: #A51F99; fill: #A51F99;' />
<polygon points='315.89,134.52 316.96,133.97 318.03,133.40 318.03,167.34 316.96,167.34 315.89,167.34 ' style='stroke-width: 0.38; stroke: #A62098; fill: #A62098;' />
<polygon points='318.03,133.40 319.09,132.83 320.16,132.24 320.16,167.34 319.09,167.34 318.03,167.34 ' style='stroke-width: 0.38; stroke: #A72197; fill: #A72197;' />
<polygon points='320.16,132.24 321.23,131.63 321.23,167.34 320.16,167.34 ' style='stroke-width: 0.38; stroke: #A82296; fill: #A82296;' />
<polygon points='321.23,131.63 322.30,131.02 322.30,167.34 321.23,167.34 ' style='stroke-width: 0.38; stroke: #A92296; fill: #A92296;' />
<polygon points='322.30,131.02 323.36,130.39 324.43,129.75 324.43,167.34 323.36,167.34 322.30,167.34 ' style='stroke-width: 0.38; stroke: #AA2395; fill: #AA2395;' />
<polygon points='324.43,129.75 325.50,129.10 325.50,167.34 324.43,167.34 ' style='stroke-width: 0.38; stroke: #AB2494; fill: #AB2494;' />
<polygon points='325.50,129.10 326.57,128.42 326.57,167.34 325.50,167.34 ' style='stroke-width: 0.38; stroke: #AB2594; fill: #AB2594;' />
<polygon points='326.57,128.42 327.63,127.73 328.70,127.03 328.70,167.34 327.63,167.34 326.57,167.34 ' style='stroke-width: 0.38; stroke: #AC2694; fill: #AC2694;' />
<polygon points='328.70,127.03 329.77,126.31 330.84,125.56 330.84,167.34 329.77,167.34 328.70,167.34 ' style='stroke-width: 0.38; stroke: #AD2793; fill: #AD2793;' />
<polygon points='330.84,125.56 331.90,124.79 331.90,167.34 330.84,167.34 ' style='stroke-width: 0.38; stroke: #AE2892; fill: #AE2892;' />
<polygon points='331.90,124.79 332.97,124.00 332.97,167.34 331.90,167.34 ' style='stroke-width: 0.38; stroke: #AF2892; fill: #AF2892;' />
<polygon points='332.97,124.00 334.04,123.18 335.11,122.34 335.11,167.34 334.04,167.34 332.97,167.34 ' style='stroke-width: 0.38; stroke: #B02991; fill: #B02991;' />
<polygon points='335.11,122.34 336.17,121.48 337.24,120.58 337.24,167.34 336.17,167.34 335.11,167.34 ' style='stroke-width: 0.38; stroke: #B12A90; fill: #B12A90;' />
<polygon points='337.24,120.58 338.31,119.65 339.38,118.71 339.38,167.34 338.31,167.34 337.24,167.34 ' style='stroke-width: 0.38; stroke: #B22B8F; fill: #B22B8F;' />
<polygon points='339.38,118.71 340.44,117.73 340.44,167.34 339.38,167.34 ' style='stroke-width: 0.38; stroke: #B32C8E; fill: #B32C8E;' />
<polygon points='340.44,117.73 341.51,116.73 341.51,167.34 340.44,167.34 ' style='stroke-width: 0.38; stroke: #B32D8E; fill: #B32D8E;' />
<polygon points='341.51,116.73 342.58,115.70 343.65,114.66 343.65,167.34 342.58,167.34 341.51,167.34 ' style='stroke-width: 0.38; stroke: #B42E8D; fill: #B42E8D;' />
<polygon points='343.65,114.66 344.71,113.59 345.78,112.51 345.78,167.34 344.71,167.34 343.65,167.34 ' style='stroke-width: 0.38; stroke: #B52F8C; fill: #B52F8C;' />
<polygon points='345.78,112.51 346.85,111.41 347.92,110.31 347.92,167.34 346.85,167.34 345.78,167.34 ' style='stroke-width: 0.38; stroke: #B6308B; fill: #B6308B;' />
<polygon points='347.92,110.31 348.98,109.20 350.05,108.09 350.05,167.34 348.98,167.34 347.92,167.34 ' style='stroke-width: 0.38; stroke: #B7318A; fill: #B7318A;' />
<polygon points='350.05,108.09 351.12,106.99 351.12,167.34 350.05,167.34 ' style='stroke-width: 0.38; stroke: #B83289; fill: #B83289;' />
<polygon points='351.12,106.99 352.19,105.90 352.19,167.34 351.12,167.34 ' style='stroke-width: 0.38; stroke: #B93289; fill: #B93289;' />
<polygon points='352.19,105.90 353.25,104.83 354.32,103.79 354.32,167.34 353.25,167.34 352.19,167.34 ' style='stroke-width: 0.38; stroke: #BA3388; fill: #BA3388;' />
<polygon points='354.32,103.79 355.39,102.78 356.46,101.80 356.46,167.34 355.39,167.34 354.32,167.34 ' style='stroke-width: 0.38; stroke: #BB3488; fill: #BB3488;' />
<polygon points='356.46,101.80 357.52,100.86 357.52,167.34 356.46,167.34 ' style='stroke-width: 0.38; stroke: #BC3587; fill: #BC3587;' />
<polygon points='357.52,100.86 358.59,99.99 358.59,167.34 357.52,167.34 ' style='stroke-width: 0.38; stroke: #BC3687; fill: #BC3687;' />
<polygon points='358.59,99.99 359.66,99.17 360.73,98.41 360.73,167.34 359.66,167.34 358.59,167.34 ' style='stroke-width: 0.38; stroke: #BD3786; fill: #BD3786;' />
<polygon points='360.73,98.41 361.79,97.72 362.86,97.10 362.86,167.34 361.79,167.34 360.73,167.34 ' style='stroke-width: 0.38; stroke: #BE3885; fill: #BE3885;' />
<polygon points='362.86,97.10 363.93,96.57 365.00,96.13 365.00,167.34 363.93,167.34 362.86,167.34 ' style='stroke-width: 0.38; stroke: #BF3984; fill: #BF3984;' />
<polygon points='365.00,96.13 366.06,95.77 367.13,95.50 367.13,167.34 366.06,167.34 365.00,167.34 ' style='stroke-width: 0.38; stroke: #C03A83; fill: #C03A83;' />
<polygon points='367.13,95.50 368.20,95.32 369.27,95.25 369.27,167.34 368.20,167.34 367.13,167.34 ' style='stroke-width: 0.38; stroke: #C13B82; fill: #C13B82;' />
<polygon points='369.27,95.25 370.33,95.27 371.40,95.38 371.40,167.34 370.33,167.34 369.27,167.34 ' style='stroke-width: 0.38; stroke: #C23C81; fill: #C23C81;' />
<polygon points='371.40,95.38 372.47,95.58 373.54,95.86 373.54,167.34 372.47,167.34 371.40,167.34 ' style='stroke-width: 0.38; stroke: #C33D80; fill: #C33D80;' />
<polygon points='373.54,95.86 374.60,96.25 374.60,167.34 373.54,167.34 ' style='stroke-width: 0.38; stroke: #C43E7F; fill: #C43E7F;' />
<polygon points='374.60,96.25 375.67,96.73 375.67,167.34 374.60,167.34 ' style='stroke-width: 0.38; stroke: #C43F7F; fill: #C43F7F;' />
<polygon points='375.67,96.73 376.74,97.28 377.81,97.90 377.81,167.34 376.74,167.34 375.67,167.34 ' style='stroke-width: 0.38; stroke: #C5407E; fill: #C5407E;' />
<polygon points='377.81,97.90 378.87,98.59 379.94,99.37 379.94,167.34 378.87,167.34 377.81,167.34 ' style='stroke-width: 0.38; stroke: #C6417D; fill: #C6417D;' />
<polygon points='379.94,99.37 381.01,100.20 382.08,101.09 382.08,167.34 381.01,167.34 379.94,167.34 ' style='stroke-width: 0.38; stroke: #C7427C; fill: #C7427C;' />
<polygon points='382.08,101.09 383.14,102.03 384.21,103.01 384.21,167.34 383.14,167.34 382.08,167.34 ' style='stroke-width: 0.38; stroke: #C8437B; fill: #C8437B;' />
<polygon points='384.21,103.01 385.28,104.05 386.35,105.12 386.35,167.34 385.28,167.34 384.21,167.34 ' style='stroke-width: 0.38; stroke: #C9447A; fill: #C9447A;' />
<polygon points='386.35,105.12 387.42,106.23 388.48,107.36 388.48,167.34 387.42,167.34 386.35,167.34 ' style='stroke-width: 0.38; stroke: #CA457A; fill: #CA457A;' />
<polygon points='388.48,107.36 389.55,108.53 390.62,109.71 390.62,167.34 389.55,167.34 388.48,167.34 ' style='stroke-width: 0.38; stroke: #CB4679; fill: #CB4679;' />
<polygon points='390.62,109.71 391.69,110.92 391.69,167.34 390.62,167.34 ' style='stroke-width: 0.38; stroke: #CC4778; fill: #CC4778;' />
<polygon points='391.69,110.92 392.75,112.15 392.75,167.34 391.69,167.34 ' style='stroke-width: 0.38; stroke: #CC4878; fill: #CC4878;' />
<polygon points='392.75,112.15 393.82,113.40 393.82,167.34 392.75,167.34 ' style='stroke-width: 0.38; stroke: #CC4877; fill: #CC4877;' />
<polygon points='393.82,113.40 394.89,114.65 394.89,167.34 393.82,167.34 ' style='stroke-width: 0.38; stroke: #CC4977; fill: #CC4977;' />
<polygon points='394.89,114.65 395.96,115.92 397.02,117.20 397.02,167.34 395.96,167.34 394.89,167.34 ' style='stroke-width: 0.38; stroke: #CD4A76; fill: #CD4A76;' />
<polygon points='397.02,117.20 398.09,118.49 399.16,119.78 399.16,167.34 398.09,167.34 397.02,167.34 ' style='stroke-width: 0.38; stroke: #CE4B75; fill: #CE4B75;' />
<polygon points='399.16,119.78 400.23,121.07 401.29,122.36 401.29,167.34 400.23,167.34 399.16,167.34 ' style='stroke-width: 0.38; stroke: #CF4C74; fill: #CF4C74;' />
<polygon points='401.29,122.36 402.36,123.65 403.43,124.93 403.43,167.34 402.36,167.34 401.29,167.34 ' style='stroke-width: 0.38; stroke: #D04D73; fill: #D04D73;' />
<polygon points='403.43,124.93 404.50,126.21 405.56,127.47 405.56,167.34 404.50,167.34 403.43,167.34 ' style='stroke-width: 0.38; stroke: #D14E72; fill: #D14E72;' />
<polygon points='405.56,127.47 406.63,128.71 407.70,129.93 407.70,167.34 406.63,167.34 405.56,167.34 ' style='stroke-width: 0.38; stroke: #D24F71; fill: #D24F71;' />
<polygon points='407.70,129.93 408.77,131.12 408.77,167.34 407.70,167.34 ' style='stroke-width: 0.38; stroke: #D35071; fill: #D35071;' />
<polygon points='408.77,131.12 409.83,132.28 409.83,167.34 408.77,167.34 ' style='stroke-width: 0.38; stroke: #D35171; fill: #D35171;' />
<polygon points='409.83,132.28 410.90,133.42 411.97,134.52 411.97,167.34 410.90,167.34 409.83,167.34 ' style='stroke-width: 0.38; stroke: #D45270; fill: #D45270;' />
<polygon points='411.97,134.52 413.04,135.57 414.10,136.57 414.10,167.34 413.04,167.34 411.97,167.34 ' style='stroke-width: 0.38; stroke: #D5536F; fill: #D5536F;' />
<polygon points='414.10,136.57 415.17,137.54 416.24,138.45 416.24,167.34 415.17,167.34 414.10,167.34 ' style='stroke-width: 0.38; stroke: #D5546E; fill: #D5546E;' />
<polygon points='416.24,138.45 417.31,139.32 418.37,140.12 418.37,167.34 417.31,167.34 416.24,167.34 ' style='stroke-width: 0.38; stroke: #D6556D; fill: #D6556D;' />
<polygon points='418.37,140.12 419.44,140.87 420.51,141.57 420.51,167.34 419.44,167.34 418.37,167.34 ' style='stroke-width: 0.38; stroke: #D7566C; fill: #D7566C;' />
<polygon points='420.51,141.57 421.58,142.22 422.64,142.82 422.64,167.34 421.58,167.34 420.51,167.34 ' style='stroke-width: 0.38; stroke: #D8576B; fill: #D8576B;' />
<polygon points='422.64,142.82 423.71,143.35 424.78,143.84 424.78,167.34 423.71,167.34 422.64,167.34 ' style='stroke-width: 0.38; stroke: #D9586A; fill: #D9586A;' />
<polygon points='424.78,143.84 425.85,144.29 425.85,167.34 424.78,167.34 ' style='stroke-width: 0.38; stroke: #DA596A; fill: #DA596A;' />
<polygon points='425.85,144.29 426.91,144.69 426.91,167.34 425.85,167.34 ' style='stroke-width: 0.38; stroke: #DA5A6A; fill: #DA5A6A;' />
<polygon points='426.91,144.69 427.98,145.06 429.05,145.38 429.05,167.34 427.98,167.34 426.91,167.34 ' style='stroke-width: 0.38; stroke: #DA5B69; fill: #DA5B69;' />
<polygon points='429.05,145.38 430.12,145.68 431.18,145.95 431.18,167.34 430.12,167.34 429.05,167.34 ' style='stroke-width: 0.38; stroke: #DB5C68; fill: #DB5C68;' />
<polygon points='431.18,145.95 432.25,146.20 433.32,146.44 433.32,167.34 432.25,167.34 431.18,167.34 ' style='stroke-width: 0.38; stroke: #DC5D67; fill: #DC5D67;' />
<polygon points='433.32,146.44 434.39,146.67 435.45,146.89 435.45,167.34 434.39,167.34 433.32,167.34 ' style='stroke-width: 0.38; stroke: #DD5E66; fill: #DD5E66;' />
<polygon points='435.45,146.89 436.52,147.12 437.59,147.34 437.59,167.34 436.52,167.34 435.45,167.34 ' style='stroke-width: 0.38; stroke: #DE5F65; fill: #DE5F65;' />
<polygon points='437.59,147.34 438.66,147.58 438.66,167.34 437.59,167.34 ' style='stroke-width: 0.38; stroke: #DE6064; fill: #DE6064;' />
<polygon points='438.66,147.58 439.72,147.83 439.72,167.34 438.66,167.34 ' style='stroke-width: 0.38; stroke: #DE6164; fill: #DE6164;' />
<polygon points='439.72,147.83 440.79,148.10 441.86,148.39 441.86,167.34 440.79,167.34 439.72,167.34 ' style='stroke-width: 0.38; stroke: #DF6263; fill: #DF6263;' />
<polygon points='441.86,148.39 442.93,148.70 443.99,149.04 443.99,167.34 442.93,167.34 441.86,167.34 ' style='stroke-width: 0.38; stroke: #E06363; fill: #E06363;' />
<polygon points='443.99,149.04 445.06,149.40 446.13,149.79 446.13,167.34 445.06,167.34 443.99,167.34 ' style='stroke-width: 0.38; stroke: #E16462; fill: #E16462;' />
<polygon points='446.13,149.79 447.20,150.21 448.26,150.65 448.26,167.34 447.20,167.34 446.13,167.34 ' style='stroke-width: 0.38; stroke: #E26561; fill: #E26561;' />
<polygon points='448.26,150.65 449.33,151.12 450.40,151.61 450.40,167.34 449.33,167.34 448.26,167.34 ' style='stroke-width: 0.38; stroke: #E26660; fill: #E26660;' />
<polygon points='450.40,151.61 451.47,152.14 451.47,167.34 450.40,167.34 ' style='stroke-width: 0.38; stroke: #E3675F; fill: #E3675F;' />
<polygon points='451.47,152.14 452.53,152.68 452.53,167.34 451.47,167.34 ' style='stroke-width: 0.38; stroke: #E3685F; fill: #E3685F;' />
<polygon points='452.53,152.68 453.60,153.24 454.67,153.82 454.67,167.34 453.60,167.34 452.53,167.34 ' style='stroke-width: 0.38; stroke: #E4695E; fill: #E4695E;' />
<polygon points='454.67,153.82 455.74,154.41 456.80,155.01 456.80,167.34 455.74,167.34 454.67,167.34 ' style='stroke-width: 0.38; stroke: #E56A5D; fill: #E56A5D;' />
<polygon points='456.80,155.01 457.87,155.62 458.94,156.24 458.94,167.34 457.87,167.34 456.80,167.34 ' style='stroke-width: 0.38; stroke: #E56B5D; fill: #E56B5D;' />
<polygon points='458.94,156.24 460.01,156.85 461.07,157.46 461.07,167.34 460.01,167.34 458.94,167.34 ' style='stroke-width: 0.38; stroke: #E66C5C; fill: #E66C5C;' />
<polygon points='461.07,157.46 462.14,158.07 462.14,167.34 461.07,167.34 ' style='stroke-width: 0.38; stroke: #E76D5B; fill: #E76D5B;' />
<polygon points='462.14,158.07 463.21,158.66 463.21,167.34 462.14,167.34 ' style='stroke-width: 0.38; stroke: #E76E5B; fill: #E76E5B;' />
<polygon points='463.21,158.66 464.28,159.25 465.34,159.82 465.34,167.34 464.28,167.34 463.21,167.34 ' style='stroke-width: 0.38; stroke: #E76F5A; fill: #E76F5A;' />
<polygon points='465.34,159.82 466.41,160.38 467.48,160.91 467.48,167.34 466.41,167.34 465.34,167.34 ' style='stroke-width: 0.38; stroke: #E87059; fill: #E87059;' />
<polygon points='467.48,160.91 468.55,161.42 469.61,161.91 469.61,167.34 468.55,167.34 467.48,167.34 ' style='stroke-width: 0.38; stroke: #E97158; fill: #E97158;' />
<polygon points='469.61,161.91 470.68,162.38 471.75,162.83 471.75,167.34 470.68,167.34 469.61,167.34 ' style='stroke-width: 0.38; stroke: #E97257; fill: #E97257;' />
<polygon points='471.75,162.83 472.82,163.24 472.82,167.34 471.75,167.34 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,163.24 473.88,163.63 473.88,167.34 472.82,167.34 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,163.63 474.95,164.00 476.02,164.34 476.02,167.34 474.95,167.34 473.88,167.34 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,164.34 477.09,164.66 478.15,164.95 478.15,167.34 477.09,167.34 476.02,167.34 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,164.95 479.22,165.22 480.29,165.46 480.29,167.34 479.22,167.34 478.15,167.34 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,165.46 481.36,165.68 481.36,167.34 480.29,167.34 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,165.68 482.42,165.89 482.42,167.34 481.36,167.34 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,165.89 483.49,166.07 484.56,166.23 484.56,167.34 483.49,167.34 482.42,167.34 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,166.23 484.56,167.34 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polyline points='244.37,166.21 245.43,166.03 246.50,165.83 247.57,165.61 248.64,165.35 249.70,165.07 250.77,164.77 251.84,164.43 252.91,164.06 253.97,163.66 255.04,163.22 256.11,162.75 257.18,162.25 258.24,161.72 259.31,161.15 260.38,160.54 261.45,159.91 262.51,159.25 263.58,158.56 264.65,157.85 265.72,157.11 266.78,156.36 267.85,155.59 268.92,154.82 269.99,154.03 271.05,153.25 272.12,152.47 273.19,151.70 274.26,150.95 275.32,150.20 276.39,149.48 277.46,148.79 278.53,148.12 279.59,147.48 280.66,146.87 281.73,146.31 282.80,145.77 283.87,145.27 284.93,144.80 286.00,144.37 287.07,143.97 288.14,143.61 289.20,143.27 290.27,142.95 291.34,142.66 292.41,142.38 293.47,142.12 294.54,141.87 295.61,141.62 296.68,141.37 297.74,141.12 298.81,140.87 299.88,140.60 300.95,140.33 302.01,140.04 303.08,139.73 304.15,139.41 305.22,139.06 306.28,138.70 307.35,138.31 308.42,137.91 309.49,137.48 310.55,137.03 311.62,136.56 312.69,136.08 313.76,135.57 314.82,135.05 315.89,134.52 316.96,133.97 318.03,133.40 319.09,132.83 320.16,132.24 321.23,131.63 322.30,131.02 323.36,130.39 324.43,129.75 325.50,129.10 326.57,128.42 327.63,127.73 328.70,127.03 329.77,126.31 330.84,125.56 331.90,124.79 332.97,124.00 334.04,123.18 335.11,122.34 336.17,121.48 337.24,120.58 338.31,119.65 339.38,118.71 340.44,117.73 341.51,116.73 342.58,115.70 343.65,114.66 344.71,113.59 345.78,112.51 346.85,111.41 347.92,110.31 348.98,109.20 350.05,108.09 351.12,106.99 352.19,105.90 353.25,104.83 354.32,103.79 355.39,102.78 356.46,101.80 357.52,100.86 358.59,99.99 359.66,99.17 360.73,98.41 361.79,97.72 362.86,97.10 363.93,96.57 365.00,96.13 366.06,95.77 367.13,95.50 368.20,95.32 369.27,95.25 370.33,95.27 371.40,95.38 372.47,95.58 373.54,95.86 374.60,96.25 375.67,96.73 376.74,97.28 377.81,97.90 378.87,98.59 379.94,99.37 381.01,100.20 382.08,101.09 383.14,102.03 384.21,103.01 385.28,104.05 386.35,105.12 387.42,106.23 388.48,107.36 389.55,108.53 390.62,109.71 391.69,110.92 392.75,112.15 393.82,113.40 394.89,114.65 395.96,115.92 397.02,117.20 398.09,118.49 399.16,119.78 400.23,121.07 401.29,122.36 402.36,123.65 403.43,124.93 404.50,126.21 405.56,127.47 406.63,128.71 407.70,129.93 408.77,131.12 409.83,132.28 410.90,133.42 411.97,134.52 413.04,135.57 414.10,136.57 415.17,137.54 416.24,138.45 417.31,139.32 418.37,140.12 419.44,140.87 420.51,141.57 421.58,142.22 422.64,142.82 423.71,143.35 424.78,143.84 425.85,144.29 426.91,144.69 427.98,145.06 429.05,145.38 430.12,145.68 431.18,145.95 432.25,146.20 433.32,146.44 434.39,146.67 435.45,146.89 436.52,147.12 437.59,147.34 438.66,147.58 439.72,147.83 440.79,148.10 441.86,148.39 442.93,148.70 443.99,149.04 445.06,149.40 446.13,149.79 447.20,150.21 448.26,150.65 449.33,151.12 450.40,151.61 451.47,152.14 452.53,152.68 453.60,153.24 454.67,153.82 455.74,154.41 456.80,155.01 457.87,155.62 458.94,156.24 460.01,156.85 461.07,157.46 462.14,158.07 463.21,158.66 464.28,159.25 465.34,159.82 466.41,160.38 467.48,160.91 468.55,161.42 469.61,161.91 470.68,162.38 471.75,162.83 472.82,163.24 473.88,163.63 474.95,164.00 476.02,164.34 477.09,164.66 478.15,164.95 479.22,165.22 480.29,165.46 481.36,165.68 482.42,165.89 483.49,166.07 484.56,166.23 ' style='stroke-width: 1.07;' />
<polygon points='304.15,199.60 305.22,199.40 305.22,200.74 304.15,200.74 ' style='stroke-width: 0.38; stroke: #9F199D; fill: #9F199D;' />
<polygon points='305.22,199.40 306.28,199.18 307.35,198.92 307.35,200.74 306.28,200.74 305.22,200.74 ' style='stroke-width: 0.38; stroke: #A01A9C; fill: #A01A9C;' />
<polygon points='307.35,198.92 308.42,198.63 308.42,200.74 307.35,200.74 ' style='stroke-width: 0.38; stroke: #A11B9B; fill: #A11B9B;' />
<polygon points='308.42,198.63 309.49,198.30 309.49,200.74 308.42,200.74 ' style='stroke-width: 0.38; stroke: #A11C9B; fill: #A11C9B;' />
<polygon points='309.49,198.30 310.55,197.93 311.62,197.51 311.62,200.74 310.55,200.74 309.49,200.74 ' style='stroke-width: 0.38; stroke: #A21D9A; fill: #A21D9A;' />
<polygon points='311.62,197.51 312.69,197.06 312.69,200.74 311.62,200.74 ' style='stroke-width: 0.38; stroke: #A31E9A; fill: #A31E9A;' />
<polygon points='312.69,197.06 313.76,196.56 313.76,200.74 312.69,200.74 ' style='stroke-width: 0.38; stroke: #A41E9A; fill: #A41E9A;' />
<polygon points='313.76,196.56 314.82,195.99 315.89,195.37 315.89,200.74 314.82,200.74 313.76,200.74 ' style='stroke-width: 0.38; stroke: #A51F99; fill: #A51F99;' />
<polygon points='315.89,195.37 316.96,194.70 318.03,193.98 318.03,200.74 316.96,200.74 315.89,200.74 ' style='stroke-width: 0.38; stroke: #A62098; fill: #A62098;' />
<polygon points='318.03,193.98 319.09,193.20 320.16,192.35 320.16,200.74 319.09,200.74 318.03,200.74 ' style='stroke-width: 0.38; stroke: #A72197; fill: #A72197;' />
<polygon points='320.16,192.35 321.23,191.45 321.23,200.74 320.16,200.74 ' style='stroke-width: 0.38; stroke: #A82296; fill: #A82296;' />
<polygon points='321.23,191.45 322.30,190.48 322.30,200.74 321.23,200.74 ' style='stroke-width: 0.38; stroke: #A92296; fill: #A92296;' />
<polygon points='322.30,190.48 323.36,189.47 324.43,188.40 324.43,200.74 323.36,200.74 322.30,200.74 ' style='stroke-width: 0.38; stroke: #AA2395; fill: #AA2395;' />
<polygon points='324.43,188.40 325.50,187.27 325.50,200.74 324.43,200.74 ' style='stroke-width: 0.38; stroke: #AB2494; fill: #AB2494;' />
<polygon points='325.50,187.27 326.57,186.10 326.57,200.74 325.50,200.74 ' style='stroke-width: 0.38; stroke: #AB2594; fill: #AB2594;' />
<polygon points='326.57,186.10 327.63,184.88 328.70,183.63 328.70,200.74 327.63,200.74 326.57,200.74 ' style='stroke-width: 0.38; stroke: #AC2694; fill: #AC2694;' />
<polygon points='328.70,183.63 329.77,182.34 330.84,181.03 330.84,200.74 329.77,200.74 328.70,200.74 ' style='stroke-width: 0.38; stroke: #AD2793; fill: #AD2793;' />
<polygon points='330.84,181.03 331.90,179.69 331.90,200.74 330.84,200.74 ' style='stroke-width: 0.38; stroke: #AE2892; fill: #AE2892;' />
<polygon points='331.90,179.69 332.97,178.35 332.97,200.74 331.90,200.74 ' style='stroke-width: 0.38; stroke: #AF2892; fill: #AF2892;' />
<polygon points='332.97,178.35 334.04,177.01 335.11,175.67 335.11,200.74 334.04,200.74 332.97,200.74 ' style='stroke-width: 0.38; stroke: #B02991; fill: #B02991;' />
<polygon points='335.11,175.67 336.17,174.34 337.24,173.03 337.24,200.74 336.17,200.74 335.11,200.74 ' style='stroke-width: 0.38; stroke: #B12A90; fill: #B12A90;' />
<polygon points='337.24,173.03 338.31,171.76 339.38,170.52 339.38,200.74 338.31,200.74 337.24,200.74 ' style='stroke-width: 0.38; stroke: #B22B8F; fill: #B22B8F;' />
<polygon points='339.38,170.52 340.44,169.32 340.44,200.74 339.38,200.74 ' style='stroke-width: 0.38; stroke: #B32C8E; fill: #B32C8E;' />
<polygon points='340.44,169.32 341.51,168.17 341.51,200.74 340.44,200.74 ' style='stroke-width: 0.38; stroke: #B32D8E; fill: #B32D8E;' />
<polygon points='341.51,168.17 342.58,167.08 343.65,166.05 343.65,200.74 342.58,200.74 341.51,200.74 ' style='stroke-width: 0.38; stroke: #B42E8D; fill: #B42E8D;' />
<polygon points='343.65,166.05 344.71,165.08 345.78,164.17 345.78,200.74 344.71,200.74 343.65,200.74 ' style='stroke-width: 0.38; stroke: #B52F8C; fill: #B52F8C;' />
<polygon points='345.78,164.17 346.85,163.33 347.92,162.56 347.92,200.74 346.85,200.74 345.78,200.74 ' style='stroke-width: 0.38; stroke: #B6308B; fill: #B6308B;' />
<polygon points='347.92,162.56 348.98,161.85 350.05,161.19 350.05,200.74 348.98,200.74 347.92,200.74 ' style='stroke-width: 0.38; stroke: #B7318A; fill: #B7318A;' />
<polygon points='350.05,161.19 351.12,160.59 351.12,200.74 350.05,200.74 ' style='stroke-width: 0.38; stroke: #B83289; fill: #B83289;' />
<polygon points='351.12,160.59 352.19,160.05 352.19,200.74 351.12,200.74 ' style='stroke-width: 0.38; stroke: #B93289; fill: #B93289;' />
<polygon points='352.19,160.05 353.25,159.56 354.32,159.10 354.32,200.74 353.25,200.74 352.19,200.74 ' style='stroke-width: 0.38; stroke: #BA3388; fill: #BA3388;' />
<polygon points='354.32,159.10 355.39,158.68 356.46,158.27 356.46,200.74 355.39,200.74 354.32,200.74 ' style='stroke-width: 0.38; stroke: #BB3488; fill: #BB3488;' />
<polygon points='356.46,158.27 357.52,157.89 357.52,200.74 356.46,200.74 ' style='stroke-width: 0.38; stroke: #BC3587; fill: #BC3587;' />
<polygon points='357.52,157.89 358.59,157.51 358.59,200.74 357.52,200.74 ' style='stroke-width: 0.38; stroke: #BC3687; fill: #BC3687;' />
<polygon points='358.59,157.51 359.66,157.14 360.73,156.76 360.73,200.74 359.66,200.74 358.59,200.74 ' style='stroke-width: 0.38; stroke: #BD3786; fill: #BD3786;' />
<polygon points='360.73,156.76 361.79,156.37 362.86,155.97 362.86,200.74 361.79,200.74 360.73,200.74 ' style='stroke-width: 0.38; stroke: #BE3885; fill: #BE3885;' />
<polygon points='362.86,155.97 363.93,155.53 365.00,155.07 365.00,200.74 363.93,200.74 362.86,200.74 ' style='stroke-width: 0.38; stroke: #BF3984; fill: #BF3984;' />
<polygon points='365.00,155.07 366.06,154.59 367.13,154.07 367.13,200.74 366.06,200.74 365.00,200.74 ' style='stroke-width: 0.38; stroke: #C03A83; fill: #C03A83;' />
<polygon points='367.13,154.07 368.20,153.53 369.27,152.95 369.27,200.74 368.20,200.74 367.13,200.74 ' style='stroke-width: 0.38; stroke: #C13B82; fill: #C13B82;' />
<polygon points='369.27,152.95 370.33,152.35 371.40,151.72 371.40,200.74 370.33,200.74 369.27,200.74 ' style='stroke-width: 0.38; stroke: #C23C81; fill: #C23C81;' />
<polygon points='371.40,151.72 372.47,151.08 373.54,150.42 373.54,200.74 372.47,200.74 371.40,200.74 ' style='stroke-width: 0.38; stroke: #C33D80; fill: #C33D80;' />
<polygon points='373.54,150.42 374.60,149.75 374.60,200.74 373.54,200.74 ' style='stroke-width: 0.38; stroke: #C43E7F; fill: #C43E7F;' />
<polygon points='374.60,149.75 375.67,149.07 375.67,200.74 374.60,200.74 ' style='stroke-width: 0.38; stroke: #C43F7F; fill: #C43F7F;' />
<polygon points='375.67,149.07 376.74,148.40 377.81,147.74 377.81,200.74 376.74,200.74 375.67,200.74 ' style='stroke-width: 0.38; stroke: #C5407E; fill: #C5407E;' />
<polygon points='377.81,147.74 378.87,147.08 379.94,146.45 379.94,200.74 378.87,200.74 377.81,200.74 ' style='stroke-width: 0.38; stroke: #C6417D; fill: #C6417D;' />
<polygon points='379.94,146.45 381.01,145.85 382.08,145.26 382.08,200.74 381.01,200.74 379.94,200.74 ' style='stroke-width: 0.38; stroke: #C7427C; fill: #C7427C;' />
<polygon points='382.08,145.26 383.14,144.71 384.21,144.19 384.21,200.74 383.14,200.74 382.08,200.74 ' style='stroke-width: 0.38; stroke: #C8437B; fill: #C8437B;' />
<polygon points='384.21,144.19 385.28,143.71 386.35,143.26 386.35,200.74 385.28,200.74 384.21,200.74 ' style='stroke-width: 0.38; stroke: #C9447A; fill: #C9447A;' />
<polygon points='386.35,143.26 387.42,142.84 388.48,142.46 388.48,200.74 387.42,200.74 386.35,200.74 ' style='stroke-width: 0.38; stroke: #CA457A; fill: #CA457A;' />
<polygon points='388.48,142.46 389.55,142.10 390.62,141.77 390.62,200.74 389.55,200.74 388.48,200.74 ' style='stroke-width: 0.38; stroke: #CB4679; fill: #CB4679;' />
<polygon points='390.62,141.77 391.69,141.46 391.69,200.74 390.62,200.74 ' style='stroke-width: 0.38; stroke: #CC4778; fill: #CC4778;' />
<polygon points='391.69,141.46 392.75,141.17 392.75,200.74 391.69,200.74 ' style='stroke-width: 0.38; stroke: #CC4878; fill: #CC4878;' />
<polygon points='392.75,141.17 393.82,140.89 393.82,200.74 392.75,200.74 ' style='stroke-width: 0.38; stroke: #CC4877; fill: #CC4877;' />
<polygon points='393.82,140.89 394.89,140.62 394.89,200.74 393.82,200.74 ' style='stroke-width: 0.38; stroke: #CC4977; fill: #CC4977;' />
<polygon points='394.89,140.62 395.96,140.36 397.02,140.09 397.02,200.74 395.96,200.74 394.89,200.74 ' style='stroke-width: 0.38; stroke: #CD4A76; fill: #CD4A76;' />
<polygon points='397.02,140.09 398.09,139.83 399.16,139.56 399.16,200.74 398.09,200.74 397.02,200.74 ' style='stroke-width: 0.38; stroke: #CE4B75; fill: #CE4B75;' />
<polygon points='399.16,139.56 400.23,139.29 401.29,139.01 401.29,200.74 400.23,200.74 399.16,200.74 ' style='stroke-width: 0.38; stroke: #CF4C74; fill: #CF4C74;' />
<polygon points='401.29,139.01 402.36,138.73 403.43,138.45 403.43,200.74 402.36,200.74 401.29,200.74 ' style='stroke-width: 0.38; stroke: #D04D73; fill: #D04D73;' />
<polygon points='403.43,138.45 404.50,138.17 405.56,137.90 405.56,200.74 404.50,200.74 403.43,200.74 ' style='stroke-width: 0.38; stroke: #D14E72; fill: #D14E72;' />
<polygon points='405.56,137.90 406.63,137.63 407.70,137.39 407.70,200.74 406.63,200.74 405.56,200.74 ' style='stroke-width: 0.38; stroke: #D24F71; fill: #D24F71;' />
<polygon points='407.70,137.39 408.77,137.17 408.77,200.74 407.70,200.74 ' style='stroke-width: 0.38; stroke: #D35071; fill: #D35071;' />
<polygon points='408.77,137.17 409.83,136.98 409.83,200.74 408.77,200.74 ' style='stroke-width: 0.38; stroke: #D35171; fill: #D35171;' />
<polygon points='409.83,136.98 410.90,136.82 411.97,136.71 411.97,200.74 410.90,200.74 409.83,200.74 ' style='stroke-width: 0.38; stroke: #D45270; fill: #D45270;' />
<polygon points='411.97,136.71 413.04,136.67 414.10,136.69 414.10,200.74 413.04,200.74 411.97,200.74 ' style='stroke-width: 0.38; stroke: #D5536F; fill: #D5536F;' />
<polygon points='414.10,136.69 415.17,136.77 416.24,136.92 416.24,200.74 415.17,200.74 414.10,200.74 ' style='stroke-width: 0.38; stroke: #D5546E; fill: #D5546E;' />
<polygon points='416.24,136.92 417.31,137.15 418.37,137.47 418.37,200.74 417.31,200.74 416.24,200.74 ' style='stroke-width: 0.38; stroke: #D6556D; fill: #D6556D;' />
<polygon points='418.37,137.47 419.44,137.88 420.51,138.37 420.51,200.74 419.44,200.74 418.37,200.74 ' style='stroke-width: 0.38; stroke: #D7566C; fill: #D7566C;' />
<polygon points='420.51,138.37 421.58,138.94 422.64,139.59 422.64,200.74 421.58,200.74 420.51,200.74 ' style='stroke-width: 0.38; stroke: #D8576B; fill: #D8576B;' />
<polygon points='422.64,139.59 423.71,140.33 424.78,141.15 424.78,200.74 423.71,200.74 422.64,200.74 ' style='stroke-width: 0.38; stroke: #D9586A; fill: #D9586A;' />
<polygon points='424.78,141.15 425.85,142.03 425.85,200.74 424.78,200.74 ' style='stroke-width: 0.38; stroke: #DA596A; fill: #DA596A;' />
<polygon points='425.85,142.03 426.91,142.97 426.91,200.74 425.85,200.74 ' style='stroke-width: 0.38; stroke: #DA5A6A; fill: #DA5A6A;' />
<polygon points='426.91,142.97 427.98,143.96 429.05,145.00 429.05,200.74 427.98,200.74 426.91,200.74 ' style='stroke-width: 0.38; stroke: #DA5B69; fill: #DA5B69;' />
<polygon points='429.05,145.00 430.12,146.08 431.18,147.17 431.18,200.74 430.12,200.74 429.05,200.74 ' style='stroke-width: 0.38; stroke: #DB5C68; fill: #DB5C68;' />
<polygon points='431.18,147.17 432.25,148.27 433.32,149.38 433.32,200.74 432.25,200.74 431.18,200.74 ' style='stroke-width: 0.38; stroke: #DC5D67; fill: #DC5D67;' />
<polygon points='433.32,149.38 434.39,150.48 435.45,151.55 435.45,200.74 434.39,200.74 433.32,200.74 ' style='stroke-width: 0.38; stroke: #DD5E66; fill: #DD5E66;' />
<polygon points='435.45,151.55 436.52,152.60 437.59,153.61 437.59,200.74 436.52,200.74 435.45,200.74 ' style='stroke-width: 0.38; stroke: #DE5F65; fill: #DE5F65;' />
<polygon points='437.59,153.61 438.66,154.57 438.66,200.74 437.59,200.74 ' style='stroke-width: 0.38; stroke: #DE6064; fill: #DE6064;' />
<polygon points='438.66,154.57 439.72,155.48 439.72,200.74 438.66,200.74 ' style='stroke-width: 0.38; stroke: #DE6164; fill: #DE6164;' />
<polygon points='439.72,155.48 440.79,156.33 441.86,157.10 441.86,200.74 440.79,200.74 439.72,200.74 ' style='stroke-width: 0.38; stroke: #DF6263; fill: #DF6263;' />
<polygon points='441.86,157.10 442.93,157.82 443.99,158.47 443.99,200.74 442.93,200.74 441.86,200.74 ' style='stroke-width: 0.38; stroke: #E06363; fill: #E06363;' />
<polygon points='443.99,158.47 445.06,159.05 446.13,159.55 446.13,200.74 445.06,200.74 443.99,200.74 ' style='stroke-width: 0.38; stroke: #E16462; fill: #E16462;' />
<polygon points='446.13,159.55 447.20,159.98 448.26,160.35 448.26,200.74 447.20,200.74 446.13,200.74 ' style='stroke-width: 0.38; stroke: #E26561; fill: #E26561;' />
<polygon points='448.26,160.35 449.33,160.67 450.40,160.93 450.40,200.74 449.33,200.74 448.26,200.74 ' style='stroke-width: 0.38; stroke: #E26660; fill: #E26660;' />
<polygon points='450.40,160.93 451.47,161.13 451.47,200.74 450.40,200.74 ' style='stroke-width: 0.38; stroke: #E3675F; fill: #E3675F;' />
<polygon points='451.47,161.13 452.53,161.29 452.53,200.74 451.47,200.74 ' style='stroke-width: 0.38; stroke: #E3685F; fill: #E3685F;' />
<polygon points='452.53,161.29 453.60,161.43 454.67,161.54 454.67,200.74 453.60,200.74 452.53,200.74 ' style='stroke-width: 0.38; stroke: #E4695E; fill: #E4695E;' />
<polygon points='454.67,161.54 455.74,161.63 456.80,161.71 456.80,200.74 455.74,200.74 454.67,200.74 ' style='stroke-width: 0.38; stroke: #E56A5D; fill: #E56A5D;' />
<polygon points='456.80,161.71 457.87,161.80 458.94,161.91 458.94,200.74 457.87,200.74 456.80,200.74 ' style='stroke-width: 0.38; stroke: #E56B5D; fill: #E56B5D;' />
<polygon points='458.94,161.91 460.01,162.03 461.07,162.17 461.07,200.74 460.01,200.74 458.94,200.74 ' style='stroke-width: 0.38; stroke: #E66C5C; fill: #E66C5C;' />
<polygon points='461.07,162.17 462.14,162.37 462.14,200.74 461.07,200.74 ' style='stroke-width: 0.38; stroke: #E76D5B; fill: #E76D5B;' />
<polygon points='462.14,162.37 463.21,162.60 463.21,200.74 462.14,200.74 ' style='stroke-width: 0.38; stroke: #E76E5B; fill: #E76E5B;' />
<polygon points='463.21,162.60 464.28,162.89 465.34,163.23 465.34,200.74 464.28,200.74 463.21,200.74 ' style='stroke-width: 0.38; stroke: #E76F5A; fill: #E76F5A;' />
<polygon points='465.34,163.23 466.41,163.62 467.48,164.09 467.48,200.74 466.41,200.74 465.34,200.74 ' style='stroke-width: 0.38; stroke: #E87059; fill: #E87059;' />
<polygon points='467.48,164.09 468.55,164.63 469.61,165.24 469.61,200.74 468.55,200.74 467.48,200.74 ' style='stroke-width: 0.38; stroke: #E97158; fill: #E97158;' />
<polygon points='469.61,165.24 470.68,165.91 471.75,166.64 471.75,200.74 470.68,200.74 469.61,200.74 ' style='stroke-width: 0.38; stroke: #E97257; fill: #E97257;' />
<polygon points='471.75,166.64 472.82,167.46 472.82,200.74 471.75,200.74 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,167.46 473.88,168.33 473.88,200.74 472.82,200.74 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,168.33 474.95,169.27 476.02,170.26 476.02,200.74 474.95,200.74 473.88,200.74 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,170.26 477.09,171.29 478.15,172.38 478.15,200.74 477.09,200.74 476.02,200.74 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,172.38 479.22,173.51 480.29,174.67 480.29,200.74 479.22,200.74 478.15,200.74 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,174.67 481.36,175.85 481.36,200.74 480.29,200.74 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,175.85 482.42,177.05 482.42,200.74 481.36,200.74 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,177.05 483.49,178.26 484.56,179.47 484.56,200.74 483.49,200.74 482.42,200.74 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,179.47 485.63,180.68 486.69,181.88 486.69,200.74 485.63,200.74 484.56,200.74 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polygon points='486.69,181.88 487.76,183.07 488.83,184.24 488.83,200.74 487.76,200.74 486.69,200.74 ' style='stroke-width: 0.38; stroke: #EF7C51; fill: #EF7C51;' />
<polygon points='488.83,184.24 489.90,185.37 489.90,200.74 488.83,200.74 ' style='stroke-width: 0.38; stroke: #EF7D50; fill: #EF7D50;' />
<polygon points='489.90,185.37 490.97,186.47 490.97,200.74 489.90,200.74 ' style='stroke-width: 0.38; stroke: #EF7E50; fill: #EF7E50;' />
<polygon points='490.97,186.47 492.03,187.54 493.10,188.56 493.10,200.74 492.03,200.74 490.97,200.74 ' style='stroke-width: 0.38; stroke: #F07F4F; fill: #F07F4F;' />
<polygon points='493.10,188.56 494.17,189.55 495.24,190.48 495.24,200.74 494.17,200.74 493.10,200.74 ' style='stroke-width: 0.38; stroke: #F0804E; fill: #F0804E;' />
<polygon points='495.24,190.48 496.30,191.37 497.37,192.21 497.37,200.74 496.30,200.74 495.24,200.74 ' style='stroke-width: 0.38; stroke: #F1814D; fill: #F1814D;' />
<polygon points='497.37,192.21 498.44,193.00 498.44,200.74 497.37,200.74 ' style='stroke-width: 0.38; stroke: #F1824C; fill: #F1824C;' />
<polygon points='498.44,193.00 499.51,193.75 499.51,200.74 498.44,200.74 ' style='stroke-width: 0.38; stroke: #F1834C; fill: #F1834C;' />
<polygon points='499.51,193.75 500.57,194.43 501.64,195.07 501.64,200.74 500.57,200.74 499.51,200.74 ' style='stroke-width: 0.38; stroke: #F2844B; fill: #F2844B;' />
<polygon points='501.64,195.07 502.71,195.66 503.78,196.21 503.78,200.74 502.71,200.74 501.64,200.74 ' style='stroke-width: 0.38; stroke: #F3854B; fill: #F3854B;' />
<polygon points='503.78,196.21 504.84,196.72 504.84,200.74 503.78,200.74 ' style='stroke-width: 0.38; stroke: #F3864A; fill: #F3864A;' />
<polygon points='504.84,196.72 505.91,197.17 505.91,200.74 504.84,200.74 ' style='stroke-width: 0.38; stroke: #F3874A; fill: #F3874A;' />
<polygon points='505.91,197.17 506.98,197.59 508.05,197.96 508.05,200.74 506.98,200.74 505.91,200.74 ' style='stroke-width: 0.38; stroke: #F48849; fill: #F48849;' />
<polygon points='508.05,197.96 509.11,198.31 510.18,198.61 510.18,200.74 509.11,200.74 508.05,200.74 ' style='stroke-width: 0.38; stroke: #F48948; fill: #F48948;' />
<polygon points='510.18,198.61 511.25,198.89 511.25,200.74 510.18,200.74 ' style='stroke-width: 0.38; stroke: #F58A47; fill: #F58A47;' />
<polygon points='511.25,198.89 512.32,199.13 512.32,200.74 511.25,200.74 ' style='stroke-width: 0.38; stroke: #F58B47; fill: #F58B47;' />
<polygon points='512.32,199.13 513.38,199.35 514.45,199.54 514.45,200.74 513.38,200.74 512.32,200.74 ' style='stroke-width: 0.38; stroke: #F58C46; fill: #F58C46;' />
<polygon points='514.45,199.54 515.52,199.71 515.52,200.74 514.45,200.74 ' style='stroke-width: 0.38; stroke: #F68D45; fill: #F68D45;' />
<polyline points='304.15,199.60 305.22,199.40 306.28,199.18 307.35,198.92 308.42,198.63 309.49,198.30 310.55,197.93 311.62,197.51 312.69,197.06 313.76,196.56 314.82,195.99 315.89,195.37 316.96,194.70 318.03,193.98 319.09,193.20 320.16,192.35 321.23,191.45 322.30,190.48 323.36,189.47 324.43,188.40 325.50,187.27 326.57,186.10 327.63,184.88 328.70,183.63 329.77,182.34 330.84,181.03 331.90,179.69 332.97,178.35 334.04,177.01 335.11,175.67 336.17,174.34 337.24,173.03 338.31,171.76 339.38,170.52 340.44,169.32 341.51,168.17 342.58,167.08 343.65,166.05 344.71,165.08 345.78,164.17 346.85,163.33 347.92,162.56 348.98,161.85 350.05,161.19 351.12,160.59 352.19,160.05 353.25,159.56 354.32,159.10 355.39,158.68 356.46,158.27 357.52,157.89 358.59,157.51 359.66,157.14 360.73,156.76 361.79,156.37 362.86,155.97 363.93,155.53 365.00,155.07 366.06,154.59 367.13,154.07 368.20,153.53 369.27,152.95 370.33,152.35 371.40,151.72 372.47,151.08 373.54,150.42 374.60,149.75 375.67,149.07 376.74,148.40 377.81,147.74 378.87,147.08 379.94,146.45 381.01,145.85 382.08,145.26 383.14,144.71 384.21,144.19 385.28,143.71 386.35,143.26 387.42,142.84 388.48,142.46 389.55,142.10 390.62,141.77 391.69,141.46 392.75,141.17 393.82,140.89 394.89,140.62 395.96,140.36 397.02,140.09 398.09,139.83 399.16,139.56 400.23,139.29 401.29,139.01 402.36,138.73 403.43,138.45 404.50,138.17 405.56,137.90 406.63,137.63 407.70,137.39 408.77,137.17 409.83,136.98 410.90,136.82 411.97,136.71 413.04,136.67 414.10,136.69 415.17,136.77 416.24,136.92 417.31,137.15 418.37,137.47 419.44,137.88 420.51,138.37 421.58,138.94 422.64,139.59 423.71,140.33 424.78,141.15 425.85,142.03 426.91,142.97 427.98,143.96 429.05,145.00 430.12,146.08 431.18,147.17 432.25,148.27 433.32,149.38 434.39,150.48 435.45,151.55 436.52,152.60 437.59,153.61 438.66,154.57 439.72,155.48 440.79,156.33 441.86,157.10 442.93,157.82 443.99,158.47 445.06,159.05 446.13,159.55 447.20,159.98 448.26,160.35 449.33,160.67 450.40,160.93 451.47,161.13 452.53,161.29 453.60,161.43 454.67,161.54 455.74,161.63 456.80,161.71 457.87,161.80 458.94,161.91 460.01,162.03 461.07,162.17 462.14,162.37 463.21,162.60 464.28,162.89 465.34,163.23 466.41,163.62 467.48,164.09 468.55,164.63 469.61,165.24 470.68,165.91 471.75,166.64 472.82,167.46 473.88,168.33 474.95,169.27 476.02,170.26 477.09,171.29 478.15,172.38 479.22,173.51 480.29,174.67 481.36,175.85 482.42,177.05 483.49,178.26 484.56,179.47 485.63,180.68 486.69,181.88 487.76,183.07 488.83,184.24 489.90,185.37 490.97,186.47 492.03,187.54 493.10,188.56 494.17,189.55 495.24,190.48 496.30,191.37 497.37,192.21 498.44,193.00 499.51,193.75 500.57,194.43 501.64,195.07 502.71,195.66 503.78,196.21 504.84,196.72 505.91,197.17 506.98,197.59 508.05,197.96 509.11,198.31 510.18,198.61 511.25,198.89 512.32,199.13 513.38,199.35 514.45,199.54 515.52,199.71 ' style='stroke-width: 1.07;' />
<polygon points='337.24,233.03 338.31,232.89 339.38,232.73 339.38,234.14 338.31,234.14 337.24,234.14 ' style='stroke-width: 0.38; stroke: #B22B8F; fill: #B22B8F;' />
<polygon points='339.38,232.73 340.44,232.57 340.44,234.14 339.38,234.14 ' style='stroke-width: 0.38; stroke: #B32C8E; fill: #B32C8E;' />
<polygon points='340.44,232.57 341.51,232.38 341.51,234.14 340.44,234.14 ' style='stroke-width: 0.38; stroke: #B32D8E; fill: #B32D8E;' />
<polygon points='341.51,232.38 342.58,232.19 343.65,231.98 343.65,234.14 342.58,234.14 341.51,234.14 ' style='stroke-width: 0.38; stroke: #B42E8D; fill: #B42E8D;' />
<polygon points='343.65,231.98 344.71,231.76 345.78,231.52 345.78,234.14 344.71,234.14 343.65,234.14 ' style='stroke-width: 0.38; stroke: #B52F8C; fill: #B52F8C;' />
<polygon points='345.78,231.52 346.85,231.27 347.92,231.01 347.92,234.14 346.85,234.14 345.78,234.14 ' style='stroke-width: 0.38; stroke: #B6308B; fill: #B6308B;' />
<polygon points='347.92,231.01 348.98,230.73 350.05,230.44 350.05,234.14 348.98,234.14 347.92,234.14 ' style='stroke-width: 0.38; stroke: #B7318A; fill: #B7318A;' />
<polygon points='350.05,230.44 351.12,230.14 351.12,234.14 350.05,234.14 ' style='stroke-width: 0.38; stroke: #B83289; fill: #B83289;' />
<polygon points='351.12,230.14 352.19,229.83 352.19,234.14 351.12,234.14 ' style='stroke-width: 0.38; stroke: #B93289; fill: #B93289;' />
<polygon points='352.19,229.83 353.25,229.51 354.32,229.18 354.32,234.14 353.25,234.14 352.19,234.14 ' style='stroke-width: 0.38; stroke: #BA3388; fill: #BA3388;' />
<polygon points='354.32,229.18 355.39,228.83 356.46,228.48 356.46,234.14 355.39,234.14 354.32,234.14 ' style='stroke-width: 0.38; stroke: #BB3488; fill: #BB3488;' />
<polygon points='356.46,228.48 357.52,228.12 357.52,234.14 356.46,234.14 ' style='stroke-width: 0.38; stroke: #BC3587; fill: #BC3587;' />
<polygon points='357.52,228.12 358.59,227.75 358.59,234.14 357.52,234.14 ' style='stroke-width: 0.38; stroke: #BC3687; fill: #BC3687;' />
<polygon points='358.59,227.75 359.66,227.36 360.73,226.97 360.73,234.14 359.66,234.14 358.59,234.14 ' style='stroke-width: 0.38; stroke: #BD3786; fill: #BD3786;' />
<polygon points='360.73,226.97 361.79,226.56 362.86,226.15 362.86,234.14 361.79,234.14 360.73,234.14 ' style='stroke-width: 0.38; stroke: #BE3885; fill: #BE3885;' />
<polygon points='362.86,226.15 363.93,225.71 365.00,225.26 365.00,234.14 363.93,234.14 362.86,234.14 ' style='stroke-width: 0.38; stroke: #BF3984; fill: #BF3984;' />
<polygon points='365.00,225.26 366.06,224.79 367.13,224.30 367.13,234.14 366.06,234.14 365.00,234.14 ' style='stroke-width: 0.38; stroke: #C03A83; fill: #C03A83;' />
<polygon points='367.13,224.30 368.20,223.78 369.27,223.23 369.27,234.14 368.20,234.14 367.13,234.14 ' style='stroke-width: 0.38; stroke: #C13B82; fill: #C13B82;' />
<polygon points='369.27,223.23 370.33,222.65 371.40,222.03 371.40,234.14 370.33,234.14 369.27,234.14 ' style='stroke-width: 0.38; stroke: #C23C81; fill: #C23C81;' />
<polygon points='371.40,222.03 372.47,221.37 373.54,220.67 373.54,234.14 372.47,234.14 371.40,234.14 ' style='stroke-width: 0.38; stroke: #C33D80; fill: #C33D80;' />
<polygon points='373.54,220.67 374.60,219.91 374.60,234.14 373.54,234.14 ' style='stroke-width: 0.38; stroke: #C43E7F; fill: #C43E7F;' />
<polygon points='374.60,219.91 375.67,219.10 375.67,234.14 374.60,234.14 ' style='stroke-width: 0.38; stroke: #C43F7F; fill: #C43F7F;' />
<polygon points='375.67,219.10 376.74,218.23 377.81,217.30 377.81,234.14 376.74,234.14 375.67,234.14 ' style='stroke-width: 0.38; stroke: #C5407E; fill: #C5407E;' />
<polygon points='377.81,217.30 378.87,216.31 379.94,215.23 379.94,234.14 378.87,234.14 377.81,234.14 ' style='stroke-width: 0.38; stroke: #C6417D; fill: #C6417D;' />
<polygon points='379.94,215.23 381.01,214.08 382.08,212.86 382.08,234.14 381.01,234.14 379.94,234.14 ' style='stroke-width: 0.38; stroke: #C7427C; fill: #C7427C;' />
<polygon points='382.08,212.86 383.14,211.57 384.21,210.20 384.21,234.14 383.14,234.14 382.08,234.14 ' style='stroke-width: 0.38; stroke: #C8437B; fill: #C8437B;' />
<polygon points='384.21,210.20 385.28,208.74 386.35,207.20 386.35,234.14 385.28,234.14 384.21,234.14 ' style='stroke-width: 0.38; stroke: #C9447A; fill: #C9447A;' />
<polygon points='386.35,207.20 387.42,205.59 388.48,203.91 388.48,234.14 387.42,234.14 386.35,234.14 ' style='stroke-width: 0.38; stroke: #CA457A; fill: #CA457A;' />
<polygon points='388.48,203.91 389.55,202.17 390.62,200.36 390.62,234.14 389.55,234.14 388.48,234.14 ' style='stroke-width: 0.38; stroke: #CB4679; fill: #CB4679;' />
<polygon points='390.62,200.36 391.69,198.48 391.69,234.14 390.62,234.14 ' style='stroke-width: 0.38; stroke: #CC4778; fill: #CC4778;' />
<polygon points='391.69,198.48 392.75,196.56 392.75,234.14 391.69,234.14 ' style='stroke-width: 0.38; stroke: #CC4878; fill: #CC4878;' />
<polygon points='392.75,196.56 393.82,194.59 393.82,234.14 392.75,234.14 ' style='stroke-width: 0.38; stroke: #CC4877; fill: #CC4877;' />
<polygon points='393.82,194.59 394.89,192.59 394.89,234.14 393.82,234.14 ' style='stroke-width: 0.38; stroke: #CC4977; fill: #CC4977;' />
<polygon points='394.89,192.59 395.96,190.57 397.02,188.53 397.02,234.14 395.96,234.14 394.89,234.14 ' style='stroke-width: 0.38; stroke: #CD4A76; fill: #CD4A76;' />
<polygon points='397.02,188.53 398.09,186.49 399.16,184.45 399.16,234.14 398.09,234.14 397.02,234.14 ' style='stroke-width: 0.38; stroke: #CE4B75; fill: #CE4B75;' />
<polygon points='399.16,184.45 400.23,182.43 401.29,180.43 401.29,234.14 400.23,234.14 399.16,234.14 ' style='stroke-width: 0.38; stroke: #CF4C74; fill: #CF4C74;' />
<polygon points='401.29,180.43 402.36,178.49 403.43,176.59 403.43,234.14 402.36,234.14 401.29,234.14 ' style='stroke-width: 0.38; stroke: #D04D73; fill: #D04D73;' />
<polygon points='403.43,176.59 404.50,174.75 405.56,172.98 405.56,234.14 404.50,234.14 403.43,234.14 ' style='stroke-width: 0.38; stroke: #D14E72; fill: #D14E72;' />
<polygon points='405.56,172.98 406.63,171.28 407.70,169.68 407.70,234.14 406.63,234.14 405.56,234.14 ' style='stroke-width: 0.38; stroke: #D24F71; fill: #D24F71;' />
<polygon points='407.70,169.68 408.77,168.18 408.77,234.14 407.70,234.14 ' style='stroke-width: 0.38; stroke: #D35071; fill: #D35071;' />
<polygon points='408.77,168.18 409.83,166.77 409.83,234.14 408.77,234.14 ' style='stroke-width: 0.38; stroke: #D35171; fill: #D35171;' />
<polygon points='409.83,166.77 410.90,165.47 411.97,164.26 411.97,234.14 410.90,234.14 409.83,234.14 ' style='stroke-width: 0.38; stroke: #D45270; fill: #D45270;' />
<polygon points='411.97,164.26 413.04,163.19 414.10,162.23 414.10,234.14 413.04,234.14 411.97,234.14 ' style='stroke-width: 0.38; stroke: #D5536F; fill: #D5536F;' />
<polygon points='414.10,162.23 415.17,161.38 416.24,160.63 416.24,234.14 415.17,234.14 414.10,234.14 ' style='stroke-width: 0.38; stroke: #D5546E; fill: #D5546E;' />
<polygon points='416.24,160.63 417.31,159.99 418.37,159.47 418.37,234.14 417.31,234.14 416.24,234.14 ' style='stroke-width: 0.38; stroke: #D6556D; fill: #D6556D;' />
<polygon points='418.37,159.47 419.44,159.06 420.51,158.74 420.51,234.14 419.44,234.14 418.37,234.14 ' style='stroke-width: 0.38; stroke: #D7566C; fill: #D7566C;' />
<polygon points='420.51,158.74 421.58,158.51 422.64,158.36 422.64,234.14 421.58,234.14 420.51,234.14 ' style='stroke-width: 0.38; stroke: #D8576B; fill: #D8576B;' />
<polygon points='422.64,158.36 423.71,158.32 424.78,158.35 424.78,234.14 423.71,234.14 422.64,234.14 ' style='stroke-width: 0.38; stroke: #D9586A; fill: #D9586A;' />
<polygon points='424.78,158.35 425.85,158.45 425.85,234.14 424.78,234.14 ' style='stroke-width: 0.38; stroke: #DA596A; fill: #DA596A;' />
<polygon points='425.85,158.45 426.91,158.61 426.91,234.14 425.85,234.14 ' style='stroke-width: 0.38; stroke: #DA5A6A; fill: #DA5A6A;' />
<polygon points='426.91,158.61 427.98,158.83 429.05,159.12 429.05,234.14 427.98,234.14 426.91,234.14 ' style='stroke-width: 0.38; stroke: #DA5B69; fill: #DA5B69;' />
<polygon points='429.05,159.12 430.12,159.46 431.18,159.85 431.18,234.14 430.12,234.14 429.05,234.14 ' style='stroke-width: 0.38; stroke: #DB5C68; fill: #DB5C68;' />
<polygon points='431.18,159.85 432.25,160.28 433.32,160.75 433.32,234.14 432.25,234.14 431.18,234.14 ' style='stroke-width: 0.38; stroke: #DC5D67; fill: #DC5D67;' />
<polygon points='433.32,160.75 434.39,161.27 435.45,161.83 435.45,234.14 434.39,234.14 433.32,234.14 ' style='stroke-width: 0.38; stroke: #DD5E66; fill: #DD5E66;' />
<polygon points='435.45,161.83 436.52,162.42 437.59,163.05 437.59,234.14 436.52,234.14 435.45,234.14 ' style='stroke-width: 0.38; stroke: #DE5F65; fill: #DE5F65;' />
<polygon points='437.59,163.05 438.66,163.71 438.66,234.14 437.59,234.14 ' style='stroke-width: 0.38; stroke: #DE6064; fill: #DE6064;' />
<polygon points='438.66,163.71 439.72,164.41 439.72,234.14 438.66,234.14 ' style='stroke-width: 0.38; stroke: #DE6164; fill: #DE6164;' />
<polygon points='439.72,164.41 440.79,165.15 441.86,165.92 441.86,234.14 440.79,234.14 439.72,234.14 ' style='stroke-width: 0.38; stroke: #DF6263; fill: #DF6263;' />
<polygon points='441.86,165.92 442.93,166.72 443.99,167.55 443.99,234.14 442.93,234.14 441.86,234.14 ' style='stroke-width: 0.38; stroke: #E06363; fill: #E06363;' />
<polygon points='443.99,167.55 445.06,168.41 446.13,169.31 446.13,234.14 445.06,234.14 443.99,234.14 ' style='stroke-width: 0.38; stroke: #E16462; fill: #E16462;' />
<polygon points='446.13,169.31 447.20,170.23 448.26,171.17 448.26,234.14 447.20,234.14 446.13,234.14 ' style='stroke-width: 0.38; stroke: #E26561; fill: #E26561;' />
<polygon points='448.26,171.17 449.33,172.13 450.40,173.11 450.40,234.14 449.33,234.14 448.26,234.14 ' style='stroke-width: 0.38; stroke: #E26660; fill: #E26660;' />
<polygon points='450.40,173.11 451.47,174.10 451.47,234.14 450.40,234.14 ' style='stroke-width: 0.38; stroke: #E3675F; fill: #E3675F;' />
<polygon points='451.47,174.10 452.53,175.11 452.53,234.14 451.47,234.14 ' style='stroke-width: 0.38; stroke: #E3685F; fill: #E3685F;' />
<polygon points='452.53,175.11 453.60,176.11 454.67,177.12 454.67,234.14 453.60,234.14 452.53,234.14 ' style='stroke-width: 0.38; stroke: #E4695E; fill: #E4695E;' />
<polygon points='454.67,177.12 455.74,178.12 456.80,179.10 456.80,234.14 455.74,234.14 454.67,234.14 ' style='stroke-width: 0.38; stroke: #E56A5D; fill: #E56A5D;' />
<polygon points='456.80,179.10 457.87,180.06 458.94,181.00 458.94,234.14 457.87,234.14 456.80,234.14 ' style='stroke-width: 0.38; stroke: #E56B5D; fill: #E56B5D;' />
<polygon points='458.94,181.00 460.01,181.92 461.07,182.80 461.07,234.14 460.01,234.14 458.94,234.14 ' style='stroke-width: 0.38; stroke: #E66C5C; fill: #E66C5C;' />
<polygon points='461.07,182.80 462.14,183.63 462.14,234.14 461.07,234.14 ' style='stroke-width: 0.38; stroke: #E76D5B; fill: #E76D5B;' />
<polygon points='462.14,183.63 463.21,184.42 463.21,234.14 462.14,234.14 ' style='stroke-width: 0.38; stroke: #E76E5B; fill: #E76E5B;' />
<polygon points='463.21,184.42 464.28,185.17 465.34,185.87 465.34,234.14 464.28,234.14 463.21,234.14 ' style='stroke-width: 0.38; stroke: #E76F5A; fill: #E76F5A;' />
<polygon points='465.34,185.87 466.41,186.51 467.48,187.10 467.48,234.14 466.41,234.14 465.34,234.14 ' style='stroke-width: 0.38; stroke: #E87059; fill: #E87059;' />
<polygon points='467.48,187.10 468.55,187.62 469.61,188.09 469.61,234.14 468.55,234.14 467.48,234.14 ' style='stroke-width: 0.38; stroke: #E97158; fill: #E97158;' />
<polygon points='469.61,188.09 470.68,188.51 471.75,188.88 471.75,234.14 470.68,234.14 469.61,234.14 ' style='stroke-width: 0.38; stroke: #E97257; fill: #E97257;' />
<polygon points='471.75,188.88 472.82,189.18 472.82,234.14 471.75,234.14 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,189.18 473.88,189.43 473.88,234.14 472.82,234.14 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,189.43 474.95,189.64 476.02,189.81 476.02,234.14 474.95,234.14 473.88,234.14 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,189.81 477.09,189.94 478.15,190.03 478.15,234.14 477.09,234.14 476.02,234.14 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,190.03 479.22,190.09 480.29,190.13 480.29,234.14 479.22,234.14 478.15,234.14 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,190.13 481.36,190.15 481.36,234.14 480.29,234.14 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,190.15 482.42,190.17 482.42,234.14 481.36,234.14 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,190.17 483.49,190.17 484.56,190.19 484.56,234.14 483.49,234.14 482.42,234.14 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,190.19 485.63,190.21 486.69,190.25 486.69,234.14 485.63,234.14 484.56,234.14 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polygon points='486.69,190.25 487.76,190.31 488.83,190.41 488.83,234.14 487.76,234.14 486.69,234.14 ' style='stroke-width: 0.38; stroke: #EF7C51; fill: #EF7C51;' />
<polygon points='488.83,190.41 489.90,190.54 489.90,234.14 488.83,234.14 ' style='stroke-width: 0.38; stroke: #EF7D50; fill: #EF7D50;' />
<polygon points='489.90,190.54 490.97,190.72 490.97,234.14 489.90,234.14 ' style='stroke-width: 0.38; stroke: #EF7E50; fill: #EF7E50;' />
<polygon points='490.97,190.72 492.03,190.95 493.10,191.22 493.10,234.14 492.03,234.14 490.97,234.14 ' style='stroke-width: 0.38; stroke: #F07F4F; fill: #F07F4F;' />
<polygon points='493.10,191.22 494.17,191.55 495.24,191.96 495.24,234.14 494.17,234.14 493.10,234.14 ' style='stroke-width: 0.38; stroke: #F0804E; fill: #F0804E;' />
<polygon points='495.24,191.96 496.30,192.43 497.37,192.97 497.37,234.14 496.30,234.14 495.24,234.14 ' style='stroke-width: 0.38; stroke: #F1814D; fill: #F1814D;' />
<polygon points='497.37,192.97 498.44,193.57 498.44,234.14 497.37,234.14 ' style='stroke-width: 0.38; stroke: #F1824C; fill: #F1824C;' />
<polygon points='498.44,193.57 499.51,194.24 499.51,234.14 498.44,234.14 ' style='stroke-width: 0.38; stroke: #F1834C; fill: #F1834C;' />
<polygon points='499.51,194.24 500.57,195.00 501.64,195.82 501.64,234.14 500.57,234.14 499.51,234.14 ' style='stroke-width: 0.38; stroke: #F2844B; fill: #F2844B;' />
<polygon points='501.64,195.82 502.71,196.71 503.78,197.67 503.78,234.14 502.71,234.14 501.64,234.14 ' style='stroke-width: 0.38; stroke: #F3854B; fill: #F3854B;' />
<polygon points='503.78,197.67 504.84,198.69 504.84,234.14 503.78,234.14 ' style='stroke-width: 0.38; stroke: #F3864A; fill: #F3864A;' />
<polygon points='504.84,198.69 505.91,199.78 505.91,234.14 504.84,234.14 ' style='stroke-width: 0.38; stroke: #F3874A; fill: #F3874A;' />
<polygon points='505.91,199.78 506.98,200.92 508.05,202.11 508.05,234.14 506.98,234.14 505.91,234.14 ' style='stroke-width: 0.38; stroke: #F48849; fill: #F48849;' />
<polygon points='508.05,202.11 509.11,203.34 510.18,204.60 510.18,234.14 509.11,234.14 508.05,234.14 ' style='stroke-width: 0.38; stroke: #F48948; fill: #F48948;' />
<polygon points='510.18,204.60 511.25,205.91 511.25,234.14 510.18,234.14 ' style='stroke-width: 0.38; stroke: #F58A47; fill: #F58A47;' />
<polygon points='511.25,205.91 512.32,207.23 512.32,234.14 511.25,234.14 ' style='stroke-width: 0.38; stroke: #F58B47; fill: #F58B47;' />
<polygon points='512.32,207.23 513.38,208.57 514.45,209.92 514.45,234.14 513.38,234.14 512.32,234.14 ' style='stroke-width: 0.38; stroke: #F58C46; fill: #F58C46;' />
<polygon points='514.45,209.92 515.52,211.27 516.59,212.62 516.59,234.14 515.52,234.14 514.45,234.14 ' style='stroke-width: 0.38; stroke: #F68D45; fill: #F68D45;' />
<polygon points='516.59,212.62 517.65,213.95 517.65,234.14 516.59,234.14 ' style='stroke-width: 0.38; stroke: #F68E44; fill: #F68E44;' />
<polygon points='517.65,213.95 518.72,215.26 518.72,234.14 517.65,234.14 ' style='stroke-width: 0.38; stroke: #F68F44; fill: #F68F44;' />
<polygon points='518.72,215.26 519.79,216.55 520.86,217.80 520.86,234.14 519.79,234.14 518.72,234.14 ' style='stroke-width: 0.38; stroke: #F79044; fill: #F79044;' />
<polygon points='520.86,217.80 521.92,219.02 522.99,220.19 522.99,234.14 521.92,234.14 520.86,234.14 ' style='stroke-width: 0.38; stroke: #F79143; fill: #F79143;' />
<polygon points='522.99,220.19 524.06,221.31 524.06,234.14 522.99,234.14 ' style='stroke-width: 0.38; stroke: #F79242; fill: #F79242;' />
<polygon points='524.06,221.31 525.13,222.39 525.13,234.14 524.06,234.14 ' style='stroke-width: 0.38; stroke: #F79342; fill: #F79342;' />
<polygon points='525.13,222.39 526.19,223.42 527.26,224.39 527.26,234.14 526.19,234.14 525.13,234.14 ' style='stroke-width: 0.38; stroke: #F89441; fill: #F89441;' />
<polygon points='527.26,224.39 528.33,225.30 529.40,226.16 529.40,234.14 528.33,234.14 527.26,234.14 ' style='stroke-width: 0.38; stroke: #F89540; fill: #F89540;' />
<polygon points='529.40,226.16 530.46,226.96 530.46,234.14 529.40,234.14 ' style='stroke-width: 0.38; stroke: #F9963F; fill: #F9963F;' />
<polygon points='530.46,226.96 531.53,227.71 531.53,234.14 530.46,234.14 ' style='stroke-width: 0.38; stroke: #F9973F; fill: #F9973F;' />
<polygon points='531.53,227.71 532.60,228.40 533.67,229.03 533.67,234.14 532.60,234.14 531.53,234.14 ' style='stroke-width: 0.38; stroke: #F9983E; fill: #F9983E;' />
<polygon points='533.67,229.03 534.73,229.61 534.73,234.14 533.67,234.14 ' style='stroke-width: 0.38; stroke: #F9993E; fill: #F9993E;' />
<polygon points='534.73,229.61 535.80,230.14 535.80,234.14 534.73,234.14 ' style='stroke-width: 0.38; stroke: #F99A3E; fill: #F99A3E;' />
<polygon points='535.80,230.14 536.87,230.62 537.94,231.06 537.94,234.14 536.87,234.14 535.80,234.14 ' style='stroke-width: 0.38; stroke: #FA9B3D; fill: #FA9B3D;' />
<polygon points='537.94,231.06 539.00,231.45 540.07,231.80 540.07,234.14 539.00,234.14 537.94,234.14 ' style='stroke-width: 0.38; stroke: #FA9C3C; fill: #FA9C3C;' />
<polygon points='540.07,231.80 541.14,232.11 541.14,234.14 540.07,234.14 ' style='stroke-width: 0.38; stroke: #FA9D3B; fill: #FA9D3B;' />
<polygon points='541.14,232.11 542.21,232.39 542.21,234.14 541.14,234.14 ' style='stroke-width: 0.38; stroke: #FA9E3B; fill: #FA9E3B;' />
<polygon points='542.21,232.39 543.27,232.64 544.34,232.85 544.34,234.14 543.27,234.14 542.21,234.14 ' style='stroke-width: 0.38; stroke: #FB9F3A; fill: #FB9F3A;' />
<polygon points='544.34,232.85 545.41,233.04 545.41,234.14 544.34,234.14 ' style='stroke-width: 0.38; stroke: #FBA039; fill: #FBA039;' />
<polygon points='545.41,233.04 545.41,234.14 ' style='stroke-width: 0.38; stroke: #FBA139; fill: #FBA139;' />
<polyline points='337.24,233.03 338.31,232.89 339.38,232.73 340.44,232.57 341.51,232.38 342.58,232.19 343.65,231.98 344.71,231.76 345.78,231.52 346.85,231.27 347.92,231.01 348.98,230.73 350.05,230.44 351.12,230.14 352.19,229.83 353.25,229.51 354.32,229.18 355.39,228.83 356.46,228.48 357.52,228.12 358.59,227.75 359.66,227.36 360.73,226.97 361.79,226.56 362.86,226.15 363.93,225.71 365.00,225.26 366.06,224.79 367.13,224.30 368.20,223.78 369.27,223.23 370.33,222.65 371.40,222.03 372.47,221.37 373.54,220.67 374.60,219.91 375.67,219.10 376.74,218.23 377.81,217.30 378.87,216.31 379.94,215.23 381.01,214.08 382.08,212.86 383.14,211.57 384.21,210.20 385.28,208.74 386.35,207.20 387.42,205.59 388.48,203.91 389.55,202.17 390.62,200.36 391.69,198.48 392.75,196.56 393.82,194.59 394.89,192.59 395.96,190.57 397.02,188.53 398.09,186.49 399.16,184.45 400.23,182.43 401.29,180.43 402.36,178.49 403.43,176.59 404.50,174.75 405.56,172.98 406.63,171.28 407.70,169.68 408.77,168.18 409.83,166.77 410.90,165.47 411.97,164.26 413.04,163.19 414.10,162.23 415.17,161.38 416.24,160.63 417.31,159.99 418.37,159.47 419.44,159.06 420.51,158.74 421.58,158.51 422.64,158.36 423.71,158.32 424.78,158.35 425.85,158.45 426.91,158.61 427.98,158.83 429.05,159.12 430.12,159.46 431.18,159.85 432.25,160.28 433.32,160.75 434.39,161.27 435.45,161.83 436.52,162.42 437.59,163.05 438.66,163.71 439.72,164.41 440.79,165.15 441.86,165.92 442.93,166.72 443.99,167.55 445.06,168.41 446.13,169.31 447.20,170.23 448.26,171.17 449.33,172.13 450.40,173.11 451.47,174.10 452.53,175.11 453.60,176.11 454.67,177.12 455.74,178.12 456.80,179.10 457.87,180.06 458.94,181.00 460.01,181.92 461.07,182.80 462.14,183.63 463.21,184.42 464.28,185.17 465.34,185.87 466.41,186.51 467.48,187.10 468.55,187.62 469.61,188.09 470.68,188.51 471.75,188.88 472.82,189.18 473.88,189.43 474.95,189.64 476.02,189.81 477.09,189.94 478.15,190.03 479.22,190.09 480.29,190.13 481.36,190.15 482.42,190.17 483.49,190.17 484.56,190.19 485.63,190.21 486.69,190.25 487.76,190.31 488.83,190.41 489.90,190.54 490.97,190.72 492.03,190.95 493.10,191.22 494.17,191.55 495.24,191.96 496.30,192.43 497.37,192.97 498.44,193.57 499.51,194.24 500.57,195.00 501.64,195.82 502.71,196.71 503.78,197.67 504.84,198.69 505.91,199.78 506.98,200.92 508.05,202.11 509.11,203.34 510.18,204.60 511.25,205.91 512.32,207.23 513.38,208.57 514.45,209.92 515.52,211.27 516.59,212.62 517.65,213.95 518.72,215.26 519.79,216.55 520.86,217.80 521.92,219.02 522.99,220.19 524.06,221.31 525.13,222.39 526.19,223.42 527.26,224.39 528.33,225.30 529.40,226.16 530.46,226.96 531.53,227.71 532.60,228.40 533.67,229.03 534.73,229.61 535.80,230.14 536.87,230.62 537.94,231.06 539.00,231.45 540.07,231.80 541.14,232.11 542.21,232.39 543.27,232.64 544.34,232.85 545.41,233.04 ' style='stroke-width: 1.07;' />
<polygon points='376.74,266.42 377.81,266.23 377.81,267.55 376.74,267.55 ' style='stroke-width: 0.38; stroke: #C5407E; fill: #C5407E;' />
<polygon points='377.81,266.23 378.87,266.01 379.94,265.76 379.94,267.55 378.87,267.55 377.81,267.55 ' style='stroke-width: 0.38; stroke: #C6417D; fill: #C6417D;' />
<polygon points='379.94,265.76 381.01,265.47 382.08,265.15 382.08,267.55 381.01,267.55 379.94,267.55 ' style='stroke-width: 0.38; stroke: #C7427C; fill: #C7427C;' />
<polygon points='382.08,265.15 383.14,264.80 384.21,264.40 384.21,267.55 383.14,267.55 382.08,267.55 ' style='stroke-width: 0.38; stroke: #C8437B; fill: #C8437B;' />
<polygon points='384.21,264.40 385.28,263.96 386.35,263.46 386.35,267.55 385.28,267.55 384.21,267.55 ' style='stroke-width: 0.38; stroke: #C9447A; fill: #C9447A;' />
<polygon points='386.35,263.46 387.42,262.92 388.48,262.34 388.48,267.55 387.42,267.55 386.35,267.55 ' style='stroke-width: 0.38; stroke: #CA457A; fill: #CA457A;' />
<polygon points='388.48,262.34 389.55,261.71 390.62,261.01 390.62,267.55 389.55,267.55 388.48,267.55 ' style='stroke-width: 0.38; stroke: #CB4679; fill: #CB4679;' />
<polygon points='390.62,261.01 391.69,260.27 391.69,267.55 390.62,267.55 ' style='stroke-width: 0.38; stroke: #CC4778; fill: #CC4778;' />
<polygon points='391.69,260.27 392.75,259.47 392.75,267.55 391.69,267.55 ' style='stroke-width: 0.38; stroke: #CC4878; fill: #CC4878;' />
<polygon points='392.75,259.47 393.82,258.62 393.82,267.55 392.75,267.55 ' style='stroke-width: 0.38; stroke: #CC4877; fill: #CC4877;' />
<polygon points='393.82,258.62 394.89,257.72 394.89,267.55 393.82,267.55 ' style='stroke-width: 0.38; stroke: #CC4977; fill: #CC4977;' />
<polygon points='394.89,257.72 395.96,256.77 397.02,255.77 397.02,267.55 395.96,267.55 394.89,267.55 ' style='stroke-width: 0.38; stroke: #CD4A76; fill: #CD4A76;' />
<polygon points='397.02,255.77 398.09,254.72 399.16,253.65 399.16,267.55 398.09,267.55 397.02,267.55 ' style='stroke-width: 0.38; stroke: #CE4B75; fill: #CE4B75;' />
<polygon points='399.16,253.65 400.23,252.53 401.29,251.39 401.29,267.55 400.23,267.55 399.16,267.55 ' style='stroke-width: 0.38; stroke: #CF4C74; fill: #CF4C74;' />
<polygon points='401.29,251.39 402.36,250.22 403.43,249.04 403.43,267.55 402.36,267.55 401.29,267.55 ' style='stroke-width: 0.38; stroke: #D04D73; fill: #D04D73;' />
<polygon points='403.43,249.04 404.50,247.85 405.56,246.65 405.56,267.55 404.50,267.55 403.43,267.55 ' style='stroke-width: 0.38; stroke: #D14E72; fill: #D14E72;' />
<polygon points='405.56,246.65 406.63,245.47 407.70,244.29 407.70,267.55 406.63,267.55 405.56,267.55 ' style='stroke-width: 0.38; stroke: #D24F71; fill: #D24F71;' />
<polygon points='407.70,244.29 408.77,243.14 408.77,267.55 407.70,267.55 ' style='stroke-width: 0.38; stroke: #D35071; fill: #D35071;' />
<polygon points='408.77,243.14 409.83,242.02 409.83,267.55 408.77,267.55 ' style='stroke-width: 0.38; stroke: #D35171; fill: #D35171;' />
<polygon points='409.83,242.02 410.90,240.94 411.97,239.89 411.97,267.55 410.90,267.55 409.83,267.55 ' style='stroke-width: 0.38; stroke: #D45270; fill: #D45270;' />
<polygon points='411.97,239.89 413.04,238.90 414.10,237.97 414.10,267.55 413.04,267.55 411.97,267.55 ' style='stroke-width: 0.38; stroke: #D5536F; fill: #D5536F;' />
<polygon points='414.10,237.97 415.17,237.09 416.24,236.28 416.24,267.55 415.17,267.55 414.10,267.55 ' style='stroke-width: 0.38; stroke: #D5546E; fill: #D5546E;' />
<polygon points='416.24,236.28 417.31,235.52 418.37,234.85 418.37,267.55 417.31,267.55 416.24,267.55 ' style='stroke-width: 0.38; stroke: #D6556D; fill: #D6556D;' />
<polygon points='418.37,234.85 419.44,234.24 420.51,233.70 420.51,267.55 419.44,267.55 418.37,267.55 ' style='stroke-width: 0.38; stroke: #D7566C; fill: #D7566C;' />
<polygon points='420.51,233.70 421.58,233.21 422.64,232.78 422.64,267.55 421.58,267.55 420.51,267.55 ' style='stroke-width: 0.38; stroke: #D8576B; fill: #D8576B;' />
<polygon points='422.64,232.78 423.71,232.42 424.78,232.12 424.78,267.55 423.71,267.55 422.64,267.55 ' style='stroke-width: 0.38; stroke: #D9586A; fill: #D9586A;' />
<polygon points='424.78,232.12 425.85,231.85 425.85,267.55 424.78,267.55 ' style='stroke-width: 0.38; stroke: #DA596A; fill: #DA596A;' />
<polygon points='425.85,231.85 426.91,231.62 426.91,267.55 425.85,267.55 ' style='stroke-width: 0.38; stroke: #DA5A6A; fill: #DA5A6A;' />
<polygon points='426.91,231.62 427.98,231.41 429.05,231.24 429.05,267.55 427.98,267.55 426.91,267.55 ' style='stroke-width: 0.38; stroke: #DA5B69; fill: #DA5B69;' />
<polygon points='429.05,231.24 430.12,231.08 431.18,230.92 431.18,267.55 430.12,267.55 429.05,267.55 ' style='stroke-width: 0.38; stroke: #DB5C68; fill: #DB5C68;' />
<polygon points='431.18,230.92 432.25,230.76 433.32,230.59 433.32,267.55 432.25,267.55 431.18,267.55 ' style='stroke-width: 0.38; stroke: #DC5D67; fill: #DC5D67;' />
<polygon points='433.32,230.59 434.39,230.40 435.45,230.18 435.45,267.55 434.39,267.55 433.32,267.55 ' style='stroke-width: 0.38; stroke: #DD5E66; fill: #DD5E66;' />
<polygon points='435.45,230.18 436.52,229.93 437.59,229.64 437.59,267.55 436.52,267.55 435.45,267.55 ' style='stroke-width: 0.38; stroke: #DE5F65; fill: #DE5F65;' />
<polygon points='437.59,229.64 438.66,229.31 438.66,267.55 437.59,267.55 ' style='stroke-width: 0.38; stroke: #DE6064; fill: #DE6064;' />
<polygon points='438.66,229.31 439.72,228.93 439.72,267.55 438.66,267.55 ' style='stroke-width: 0.38; stroke: #DE6164; fill: #DE6164;' />
<polygon points='439.72,228.93 440.79,228.50 441.86,228.02 441.86,267.55 440.79,267.55 439.72,267.55 ' style='stroke-width: 0.38; stroke: #DF6263; fill: #DF6263;' />
<polygon points='441.86,228.02 442.93,227.49 443.99,226.91 443.99,267.55 442.93,267.55 441.86,267.55 ' style='stroke-width: 0.38; stroke: #E06363; fill: #E06363;' />
<polygon points='443.99,226.91 445.06,226.28 446.13,225.59 446.13,267.55 445.06,267.55 443.99,267.55 ' style='stroke-width: 0.38; stroke: #E16462; fill: #E16462;' />
<polygon points='446.13,225.59 447.20,224.87 448.26,224.12 448.26,267.55 447.20,267.55 446.13,267.55 ' style='stroke-width: 0.38; stroke: #E26561; fill: #E26561;' />
<polygon points='448.26,224.12 449.33,223.33 450.40,222.51 450.40,267.55 449.33,267.55 448.26,267.55 ' style='stroke-width: 0.38; stroke: #E26660; fill: #E26660;' />
<polygon points='450.40,222.51 451.47,221.68 451.47,267.55 450.40,267.55 ' style='stroke-width: 0.38; stroke: #E3675F; fill: #E3675F;' />
<polygon points='451.47,221.68 452.53,220.84 452.53,267.55 451.47,267.55 ' style='stroke-width: 0.38; stroke: #E3685F; fill: #E3685F;' />
<polygon points='452.53,220.84 453.60,219.99 454.67,219.15 454.67,267.55 453.60,267.55 452.53,267.55 ' style='stroke-width: 0.38; stroke: #E4695E; fill: #E4695E;' />
<polygon points='454.67,219.15 455.74,218.32 456.80,217.51 456.80,267.55 455.74,267.55 454.67,267.55 ' style='stroke-width: 0.38; stroke: #E56A5D; fill: #E56A5D;' />
<polygon points='456.80,217.51 457.87,216.74 458.94,216.00 458.94,267.55 457.87,267.55 456.80,267.55 ' style='stroke-width: 0.38; stroke: #E56B5D; fill: #E56B5D;' />
<polygon points='458.94,216.00 460.01,215.30 461.07,214.64 461.07,267.55 460.01,267.55 458.94,267.55 ' style='stroke-width: 0.38; stroke: #E66C5C; fill: #E66C5C;' />
<polygon points='461.07,214.64 462.14,214.05 462.14,267.55 461.07,267.55 ' style='stroke-width: 0.38; stroke: #E76D5B; fill: #E76D5B;' />
<polygon points='462.14,214.05 463.21,213.53 463.21,267.55 462.14,267.55 ' style='stroke-width: 0.38; stroke: #E76E5B; fill: #E76E5B;' />
<polygon points='463.21,213.53 464.28,213.06 465.34,212.66 465.34,267.55 464.28,267.55 463.21,267.55 ' style='stroke-width: 0.38; stroke: #E76F5A; fill: #E76F5A;' />
<polygon points='465.34,212.66 466.41,212.31 467.48,212.06 467.48,267.55 466.41,267.55 465.34,267.55 ' style='stroke-width: 0.38; stroke: #E87059; fill: #E87059;' />
<polygon points='467.48,212.06 468.55,211.86 469.61,211.74 469.61,267.55 468.55,267.55 467.48,267.55 ' style='stroke-width: 0.38; stroke: #E97158; fill: #E97158;' />
<polygon points='469.61,211.74 470.68,211.67 471.75,211.65 471.75,267.55 470.68,267.55 469.61,267.55 ' style='stroke-width: 0.38; stroke: #E97257; fill: #E97257;' />
<polygon points='471.75,211.65 472.82,211.70 472.82,267.55 471.75,267.55 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,211.70 473.88,211.80 473.88,267.55 472.82,267.55 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,211.80 474.95,211.93 476.02,212.10 476.02,267.55 474.95,267.55 473.88,267.55 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,212.10 477.09,212.29 478.15,212.49 478.15,267.55 477.09,267.55 476.02,267.55 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,212.49 479.22,212.70 480.29,212.91 480.29,267.55 479.22,267.55 478.15,267.55 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,212.91 481.36,213.09 481.36,267.55 480.29,267.55 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,213.09 482.42,213.26 482.42,267.55 481.36,267.55 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,213.26 483.49,213.39 484.56,213.47 484.56,267.55 483.49,267.55 482.42,267.55 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,213.47 485.63,213.50 486.69,213.47 486.69,267.55 485.63,267.55 484.56,267.55 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polygon points='486.69,213.47 487.76,213.39 488.83,213.23 488.83,267.55 487.76,267.55 486.69,267.55 ' style='stroke-width: 0.38; stroke: #EF7C51; fill: #EF7C51;' />
<polygon points='488.83,213.23 489.90,212.98 489.90,267.55 488.83,267.55 ' style='stroke-width: 0.38; stroke: #EF7D50; fill: #EF7D50;' />
<polygon points='489.90,212.98 490.97,212.66 490.97,267.55 489.90,267.55 ' style='stroke-width: 0.38; stroke: #EF7E50; fill: #EF7E50;' />
<polygon points='490.97,212.66 492.03,212.26 493.10,211.79 493.10,267.55 492.03,267.55 490.97,267.55 ' style='stroke-width: 0.38; stroke: #F07F4F; fill: #F07F4F;' />
<polygon points='493.10,211.79 494.17,211.23 495.24,210.59 495.24,267.55 494.17,267.55 493.10,267.55 ' style='stroke-width: 0.38; stroke: #F0804E; fill: #F0804E;' />
<polygon points='495.24,210.59 496.30,209.88 497.37,209.11 497.37,267.55 496.30,267.55 495.24,267.55 ' style='stroke-width: 0.38; stroke: #F1814D; fill: #F1814D;' />
<polygon points='497.37,209.11 498.44,208.28 498.44,267.55 497.37,267.55 ' style='stroke-width: 0.38; stroke: #F1824C; fill: #F1824C;' />
<polygon points='498.44,208.28 499.51,207.40 499.51,267.55 498.44,267.55 ' style='stroke-width: 0.38; stroke: #F1834C; fill: #F1834C;' />
<polygon points='499.51,207.40 500.57,206.47 501.64,205.51 501.64,267.55 500.57,267.55 499.51,267.55 ' style='stroke-width: 0.38; stroke: #F2844B; fill: #F2844B;' />
<polygon points='501.64,205.51 502.71,204.53 503.78,203.55 503.78,267.55 502.71,267.55 501.64,267.55 ' style='stroke-width: 0.38; stroke: #F3854B; fill: #F3854B;' />
<polygon points='503.78,203.55 504.84,202.57 504.84,267.55 503.78,267.55 ' style='stroke-width: 0.38; stroke: #F3864A; fill: #F3864A;' />
<polygon points='504.84,202.57 505.91,201.61 505.91,267.55 504.84,267.55 ' style='stroke-width: 0.38; stroke: #F3874A; fill: #F3874A;' />
<polygon points='505.91,201.61 506.98,200.68 508.05,199.80 508.05,267.55 506.98,267.55 505.91,267.55 ' style='stroke-width: 0.38; stroke: #F48849; fill: #F48849;' />
<polygon points='508.05,199.80 509.11,198.97 510.18,198.21 510.18,267.55 509.11,267.55 508.05,267.55 ' style='stroke-width: 0.38; stroke: #F48948; fill: #F48948;' />
<polygon points='510.18,198.21 511.25,197.54 511.25,267.55 510.18,267.55 ' style='stroke-width: 0.38; stroke: #F58A47; fill: #F58A47;' />
<polygon points='511.25,197.54 512.32,196.97 512.32,267.55 511.25,267.55 ' style='stroke-width: 0.38; stroke: #F58B47; fill: #F58B47;' />
<polygon points='512.32,196.97 513.38,196.50 514.45,196.14 514.45,267.55 513.38,267.55 512.32,267.55 ' style='stroke-width: 0.38; stroke: #F58C46; fill: #F58C46;' />
<polygon points='514.45,196.14 515.52,195.90 516.59,195.80 516.59,267.55 515.52,267.55 514.45,267.55 ' style='stroke-width: 0.38; stroke: #F68D45; fill: #F68D45;' />
<polygon points='516.59,195.80 517.65,195.85 517.65,267.55 516.59,267.55 ' style='stroke-width: 0.38; stroke: #F68E44; fill: #F68E44;' />
<polygon points='517.65,195.85 518.72,196.04 518.72,267.55 517.65,267.55 ' style='stroke-width: 0.38; stroke: #F68F44; fill: #F68F44;' />
<polygon points='518.72,196.04 519.79,196.37 520.86,196.83 520.86,267.55 519.79,267.55 518.72,267.55 ' style='stroke-width: 0.38; stroke: #F79044; fill: #F79044;' />
<polygon points='520.86,196.83 521.92,197.47 522.99,198.26 522.99,267.55 521.92,267.55 520.86,267.55 ' style='stroke-width: 0.38; stroke: #F79143; fill: #F79143;' />
<polygon points='522.99,198.26 524.06,199.20 524.06,267.55 522.99,267.55 ' style='stroke-width: 0.38; stroke: #F79242; fill: #F79242;' />
<polygon points='524.06,199.20 525.13,200.27 525.13,267.55 524.06,267.55 ' style='stroke-width: 0.38; stroke: #F79342; fill: #F79342;' />
<polygon points='525.13,200.27 526.19,201.47 527.26,202.82 527.26,267.55 526.19,267.55 525.13,267.55 ' style='stroke-width: 0.38; stroke: #F89441; fill: #F89441;' />
<polygon points='527.26,202.82 528.33,204.31 529.40,205.91 529.40,267.55 528.33,267.55 527.26,267.55 ' style='stroke-width: 0.38; stroke: #F89540; fill: #F89540;' />
<polygon points='529.40,205.91 530.46,207.61 530.46,267.55 529.40,267.55 ' style='stroke-width: 0.38; stroke: #F9963F; fill: #F9963F;' />
<polygon points='530.46,207.61 531.53,209.41 531.53,267.55 530.46,267.55 ' style='stroke-width: 0.38; stroke: #F9973F; fill: #F9973F;' />
<polygon points='531.53,209.41 532.60,211.30 533.67,213.28 533.67,267.55 532.60,267.55 531.53,267.55 ' style='stroke-width: 0.38; stroke: #F9983E; fill: #F9983E;' />
<polygon points='533.67,213.28 534.73,215.32 534.73,267.55 533.67,267.55 ' style='stroke-width: 0.38; stroke: #F9993E; fill: #F9993E;' />
<polygon points='534.73,215.32 535.80,217.41 535.80,267.55 534.73,267.55 ' style='stroke-width: 0.38; stroke: #F99A3E; fill: #F99A3E;' />
<polygon points='535.80,217.41 536.87,219.54 537.94,221.71 537.94,267.55 536.87,267.55 535.80,267.55 ' style='stroke-width: 0.38; stroke: #FA9B3D; fill: #FA9B3D;' />
<polygon points='537.94,221.71 539.00,223.90 540.07,226.10 540.07,267.55 539.00,267.55 537.94,267.55 ' style='stroke-width: 0.38; stroke: #FA9C3C; fill: #FA9C3C;' />
<polygon points='540.07,226.10 541.14,228.29 541.14,267.55 540.07,267.55 ' style='stroke-width: 0.38; stroke: #FA9D3B; fill: #FA9D3B;' />
<polygon points='541.14,228.29 542.21,230.47 542.21,267.55 541.14,267.55 ' style='stroke-width: 0.38; stroke: #FA9E3B; fill: #FA9E3B;' />
<polygon points='542.21,230.47 543.27,232.63 544.34,234.75 544.34,267.55 543.27,267.55 542.21,267.55 ' style='stroke-width: 0.38; stroke: #FB9F3A; fill: #FB9F3A;' />
<polygon points='544.34,234.75 545.41,236.82 545.41,267.55 544.34,267.55 ' style='stroke-width: 0.38; stroke: #FBA039; fill: #FBA039;' />
<polygon points='545.41,236.82 546.48,238.85 546.48,267.55 545.41,267.55 ' style='stroke-width: 0.38; stroke: #FBA139; fill: #FBA139;' />
<polygon points='546.48,238.85 547.54,240.83 548.61,242.75 548.61,267.55 547.54,267.55 546.48,267.55 ' style='stroke-width: 0.38; stroke: #FBA238; fill: #FBA238;' />
<polygon points='548.61,242.75 549.68,244.58 550.75,246.34 550.75,267.55 549.68,267.55 548.61,267.55 ' style='stroke-width: 0.38; stroke: #FCA338; fill: #FCA338;' />
<polygon points='550.75,246.34 551.81,248.03 551.81,267.55 550.75,267.55 ' style='stroke-width: 0.38; stroke: #FCA437; fill: #FCA437;' />
<polygon points='551.81,248.03 552.88,249.64 552.88,267.55 551.81,267.55 ' style='stroke-width: 0.38; stroke: #FCA537; fill: #FCA537;' />
<polygon points='552.88,249.64 553.95,251.18 555.02,252.61 555.02,267.55 553.95,267.55 552.88,267.55 ' style='stroke-width: 0.38; stroke: #FCA636; fill: #FCA636;' />
<polygon points='555.02,252.61 556.08,253.96 556.08,267.55 555.02,267.55 ' style='stroke-width: 0.38; stroke: #FCA735; fill: #FCA735;' />
<polygon points='556.08,253.96 557.15,255.24 557.15,267.55 556.08,267.55 ' style='stroke-width: 0.38; stroke: #FCA835; fill: #FCA835;' />
<polygon points='557.15,255.24 558.22,256.43 559.29,257.54 559.29,267.55 558.22,267.55 557.15,267.55 ' style='stroke-width: 0.38; stroke: #FCA934; fill: #FCA934;' />
<polygon points='559.29,257.54 560.35,258.56 560.35,267.55 559.29,267.55 ' style='stroke-width: 0.38; stroke: #FDAA33; fill: #FDAA33;' />
<polygon points='560.35,258.56 561.42,259.50 561.42,267.55 560.35,267.55 ' style='stroke-width: 0.38; stroke: #FDAB33; fill: #FDAB33;' />
<polygon points='561.42,259.50 562.49,260.37 563.56,261.17 563.56,267.55 562.49,267.55 561.42,267.55 ' style='stroke-width: 0.38; stroke: #FDAC33; fill: #FDAC33;' />
<polygon points='563.56,261.17 564.62,261.90 564.62,267.55 563.56,267.55 ' style='stroke-width: 0.38; stroke: #FDAD32; fill: #FDAD32;' />
<polygon points='564.62,261.90 565.69,262.56 565.69,267.55 564.62,267.55 ' style='stroke-width: 0.38; stroke: #FDAE32; fill: #FDAE32;' />
<polygon points='565.69,262.56 566.76,263.15 567.83,263.69 567.83,267.55 566.76,267.55 565.69,267.55 ' style='stroke-width: 0.38; stroke: #FDAF31; fill: #FDAF31;' />
<polygon points='567.83,263.69 568.89,264.18 568.89,267.55 567.83,267.55 ' style='stroke-width: 0.38; stroke: #FDB030; fill: #FDB030;' />
<polygon points='568.89,264.18 569.96,264.62 569.96,267.55 568.89,267.55 ' style='stroke-width: 0.38; stroke: #FDB130; fill: #FDB130;' />
<polygon points='569.96,264.62 571.03,265.00 572.10,265.34 572.10,267.55 571.03,267.55 569.96,267.55 ' style='stroke-width: 0.38; stroke: #FDB22F; fill: #FDB22F;' />
<polygon points='572.10,265.34 573.16,265.65 573.16,267.55 572.10,267.55 ' style='stroke-width: 0.38; stroke: #FDB32F; fill: #FDB32F;' />
<polygon points='573.16,265.65 574.23,265.92 574.23,267.55 573.16,267.55 ' style='stroke-width: 0.38; stroke: #FDB42F; fill: #FDB42F;' />
<polygon points='574.23,265.92 575.30,266.15 576.37,266.36 576.37,267.55 575.30,267.55 574.23,267.55 ' style='stroke-width: 0.38; stroke: #FDB52E; fill: #FDB52E;' />
<polygon points='576.37,266.36 577.43,266.54 577.43,267.55 576.37,267.55 ' style='stroke-width: 0.38; stroke: #FEB62D; fill: #FEB62D;' />
<polygon points='577.43,266.54 577.43,267.55 ' style='stroke-width: 0.38; stroke: #FEB72D; fill: #FEB72D;' />
<polyline points='376.74,266.42 377.81,266.23 378.87,266.01 379.94,265.76 381.01,265.47 382.08,265.15 383.14,264.80 384.21,264.40 385.28,263.96 386.35,263.46 387.42,262.92 388.48,262.34 389.55,261.71 390.62,261.01 391.69,260.27 392.75,259.47 393.82,258.62 394.89,257.72 395.96,256.77 397.02,255.77 398.09,254.72 399.16,253.65 400.23,252.53 401.29,251.39 402.36,250.22 403.43,249.04 404.50,247.85 405.56,246.65 406.63,245.47 407.70,244.29 408.77,243.14 409.83,242.02 410.90,240.94 411.97,239.89 413.04,238.90 414.10,237.97 415.17,237.09 416.24,236.28 417.31,235.52 418.37,234.85 419.44,234.24 420.51,233.70 421.58,233.21 422.64,232.78 423.71,232.42 424.78,232.12 425.85,231.85 426.91,231.62 427.98,231.41 429.05,231.24 430.12,231.08 431.18,230.92 432.25,230.76 433.32,230.59 434.39,230.40 435.45,230.18 436.52,229.93 437.59,229.64 438.66,229.31 439.72,228.93 440.79,228.50 441.86,228.02 442.93,227.49 443.99,226.91 445.06,226.28 446.13,225.59 447.20,224.87 448.26,224.12 449.33,223.33 450.40,222.51 451.47,221.68 452.53,220.84 453.60,219.99 454.67,219.15 455.74,218.32 456.80,217.51 457.87,216.74 458.94,216.00 460.01,215.30 461.07,214.64 462.14,214.05 463.21,213.53 464.28,213.06 465.34,212.66 466.41,212.31 467.48,212.06 468.55,211.86 469.61,211.74 470.68,211.67 471.75,211.65 472.82,211.70 473.88,211.80 474.95,211.93 476.02,212.10 477.09,212.29 478.15,212.49 479.22,212.70 480.29,212.91 481.36,213.09 482.42,213.26 483.49,213.39 484.56,213.47 485.63,213.50 486.69,213.47 487.76,213.39 488.83,213.23 489.90,212.98 490.97,212.66 492.03,212.26 493.10,211.79 494.17,211.23 495.24,210.59 496.30,209.88 497.37,209.11 498.44,208.28 499.51,207.40 500.57,206.47 501.64,205.51 502.71,204.53 503.78,203.55 504.84,202.57 505.91,201.61 506.98,200.68 508.05,199.80 509.11,198.97 510.18,198.21 511.25,197.54 512.32,196.97 513.38,196.50 514.45,196.14 515.52,195.90 516.59,195.80 517.65,195.85 518.72,196.04 519.79,196.37 520.86,196.83 521.92,197.47 522.99,198.26 524.06,199.20 525.13,200.27 526.19,201.47 527.26,202.82 528.33,204.31 529.40,205.91 530.46,207.61 531.53,209.41 532.60,211.30 533.67,213.28 534.73,215.32 535.80,217.41 536.87,219.54 537.94,221.71 539.00,223.90 540.07,226.10 541.14,228.29 542.21,230.47 543.27,232.63 544.34,234.75 545.41,236.82 546.48,238.85 547.54,240.83 548.61,242.75 549.68,244.58 550.75,246.34 551.81,248.03 552.88,249.64 553.95,251.18 555.02,252.61 556.08,253.96 557.15,255.24 558.22,256.43 559.29,257.54 560.35,258.56 561.42,259.50 562.49,260.37 563.56,261.17 564.62,261.90 565.69,262.56 566.76,263.15 567.83,263.69 568.89,264.18 569.96,264.62 571.03,265.00 572.10,265.34 573.16,265.65 574.23,265.92 575.30,266.15 576.37,266.36 577.43,266.54 ' style='stroke-width: 1.07;' />
<polygon points='471.75,299.81 472.82,299.63 472.82,300.95 471.75,300.95 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,299.63 473.88,299.43 473.88,300.95 472.82,300.95 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,299.43 474.95,299.20 476.02,298.95 476.02,300.95 474.95,300.95 473.88,300.95 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,298.95 477.09,298.67 478.15,298.35 478.15,300.95 477.09,300.95 476.02,300.95 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,298.35 479.22,298.01 480.29,297.62 480.29,300.95 479.22,300.95 478.15,300.95 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,297.62 481.36,297.21 481.36,300.95 480.29,300.95 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,297.21 482.42,296.75 482.42,300.95 481.36,300.95 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,296.75 483.49,296.25 484.56,295.71 484.56,300.95 483.49,300.95 482.42,300.95 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,295.71 485.63,295.12 486.69,294.49 486.69,300.95 485.63,300.95 484.56,300.95 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polygon points='486.69,294.49 487.76,293.81 488.83,293.09 488.83,300.95 487.76,300.95 486.69,300.95 ' style='stroke-width: 0.38; stroke: #EF7C51; fill: #EF7C51;' />
<polygon points='488.83,293.09 489.90,292.31 489.90,300.95 488.83,300.95 ' style='stroke-width: 0.38; stroke: #EF7D50; fill: #EF7D50;' />
<polygon points='489.90,292.31 490.97,291.48 490.97,300.95 489.90,300.95 ' style='stroke-width: 0.38; stroke: #EF7E50; fill: #EF7E50;' />
<polygon points='490.97,291.48 492.03,290.61 493.10,289.69 493.10,300.95 492.03,300.95 490.97,300.95 ' style='stroke-width: 0.38; stroke: #F07F4F; fill: #F07F4F;' />
<polygon points='493.10,289.69 494.17,288.72 495.24,287.69 495.24,300.95 494.17,300.95 493.10,300.95 ' style='stroke-width: 0.38; stroke: #F0804E; fill: #F0804E;' />
<polygon points='495.24,287.69 496.30,286.62 497.37,285.51 497.37,300.95 496.30,300.95 495.24,300.95 ' style='stroke-width: 0.38; stroke: #F1814D; fill: #F1814D;' />
<polygon points='497.37,285.51 498.44,284.36 498.44,300.95 497.37,300.95 ' style='stroke-width: 0.38; stroke: #F1824C; fill: #F1824C;' />
<polygon points='498.44,284.36 499.51,283.16 499.51,300.95 498.44,300.95 ' style='stroke-width: 0.38; stroke: #F1834C; fill: #F1834C;' />
<polygon points='499.51,283.16 500.57,281.91 501.64,280.63 501.64,300.95 500.57,300.95 499.51,300.95 ' style='stroke-width: 0.38; stroke: #F2844B; fill: #F2844B;' />
<polygon points='501.64,280.63 502.71,279.31 503.78,277.96 503.78,300.95 502.71,300.95 501.64,300.95 ' style='stroke-width: 0.38; stroke: #F3854B; fill: #F3854B;' />
<polygon points='503.78,277.96 504.84,276.58 504.84,300.95 503.78,300.95 ' style='stroke-width: 0.38; stroke: #F3864A; fill: #F3864A;' />
<polygon points='504.84,276.58 505.91,275.16 505.91,300.95 504.84,300.95 ' style='stroke-width: 0.38; stroke: #F3874A; fill: #F3874A;' />
<polygon points='505.91,275.16 506.98,273.71 508.05,272.24 508.05,300.95 506.98,300.95 505.91,300.95 ' style='stroke-width: 0.38; stroke: #F48849; fill: #F48849;' />
<polygon points='508.05,272.24 509.11,270.74 510.18,269.22 510.18,300.95 509.11,300.95 508.05,300.95 ' style='stroke-width: 0.38; stroke: #F48948; fill: #F48948;' />
<polygon points='510.18,269.22 511.25,267.67 511.25,300.95 510.18,300.95 ' style='stroke-width: 0.38; stroke: #F58A47; fill: #F58A47;' />
<polygon points='511.25,267.67 512.32,266.11 512.32,300.95 511.25,300.95 ' style='stroke-width: 0.38; stroke: #F58B47; fill: #F58B47;' />
<polygon points='512.32,266.11 513.38,264.52 514.45,262.92 514.45,300.95 513.38,300.95 512.32,300.95 ' style='stroke-width: 0.38; stroke: #F58C46; fill: #F58C46;' />
<polygon points='514.45,262.92 515.52,261.30 516.59,259.65 516.59,300.95 515.52,300.95 514.45,300.95 ' style='stroke-width: 0.38; stroke: #F68D45; fill: #F68D45;' />
<polygon points='516.59,259.65 517.65,257.98 517.65,300.95 516.59,300.95 ' style='stroke-width: 0.38; stroke: #F68E44; fill: #F68E44;' />
<polygon points='517.65,257.98 518.72,256.30 518.72,300.95 517.65,300.95 ' style='stroke-width: 0.38; stroke: #F68F44; fill: #F68F44;' />
<polygon points='518.72,256.30 519.79,254.60 520.86,252.88 520.86,300.95 519.79,300.95 518.72,300.95 ' style='stroke-width: 0.38; stroke: #F79044; fill: #F79044;' />
<polygon points='520.86,252.88 521.92,251.14 522.99,249.37 522.99,300.95 521.92,300.95 520.86,300.95 ' style='stroke-width: 0.38; stroke: #F79143; fill: #F79143;' />
<polygon points='522.99,249.37 524.06,247.59 524.06,300.95 522.99,300.95 ' style='stroke-width: 0.38; stroke: #F79242; fill: #F79242;' />
<polygon points='524.06,247.59 525.13,245.79 525.13,300.95 524.06,300.95 ' style='stroke-width: 0.38; stroke: #F79342; fill: #F79342;' />
<polygon points='525.13,245.79 526.19,243.98 527.26,242.15 527.26,300.95 526.19,300.95 525.13,300.95 ' style='stroke-width: 0.38; stroke: #F89441; fill: #F89441;' />
<polygon points='527.26,242.15 528.33,240.31 529.40,238.46 529.40,300.95 528.33,300.95 527.26,300.95 ' style='stroke-width: 0.38; stroke: #F89540; fill: #F89540;' />
<polygon points='529.40,238.46 530.46,236.60 530.46,300.95 529.40,300.95 ' style='stroke-width: 0.38; stroke: #F9963F; fill: #F9963F;' />
<polygon points='530.46,236.60 531.53,234.75 531.53,300.95 530.46,300.95 ' style='stroke-width: 0.38; stroke: #F9973F; fill: #F9973F;' />
<polygon points='531.53,234.75 532.60,232.90 533.67,231.07 533.67,300.95 532.60,300.95 531.53,300.95 ' style='stroke-width: 0.38; stroke: #F9983E; fill: #F9983E;' />
<polygon points='533.67,231.07 534.73,229.26 534.73,300.95 533.67,300.95 ' style='stroke-width: 0.38; stroke: #F9993E; fill: #F9993E;' />
<polygon points='534.73,229.26 535.80,227.48 535.80,300.95 534.73,300.95 ' style='stroke-width: 0.38; stroke: #F99A3E; fill: #F99A3E;' />
<polygon points='535.80,227.48 536.87,225.74 537.94,224.03 537.94,300.95 536.87,300.95 535.80,300.95 ' style='stroke-width: 0.38; stroke: #FA9B3D; fill: #FA9B3D;' />
<polygon points='537.94,224.03 539.00,222.40 540.07,220.83 540.07,300.95 539.00,300.95 537.94,300.95 ' style='stroke-width: 0.38; stroke: #FA9C3C; fill: #FA9C3C;' />
<polygon points='540.07,220.83 541.14,219.33 541.14,300.95 540.07,300.95 ' style='stroke-width: 0.38; stroke: #FA9D3B; fill: #FA9D3B;' />
<polygon points='541.14,219.33 542.21,217.92 542.21,300.95 541.14,300.95 ' style='stroke-width: 0.38; stroke: #FA9E3B; fill: #FA9E3B;' />
<polygon points='542.21,217.92 543.27,216.59 544.34,215.39 544.34,300.95 543.27,300.95 542.21,300.95 ' style='stroke-width: 0.38; stroke: #FB9F3A; fill: #FB9F3A;' />
<polygon points='544.34,215.39 545.41,214.30 545.41,300.95 544.34,300.95 ' style='stroke-width: 0.38; stroke: #FBA039; fill: #FBA039;' />
<polygon points='545.41,214.30 546.48,213.32 546.48,300.95 545.41,300.95 ' style='stroke-width: 0.38; stroke: #FBA139; fill: #FBA139;' />
<polygon points='546.48,213.32 547.54,212.46 548.61,211.71 548.61,300.95 547.54,300.95 546.48,300.95 ' style='stroke-width: 0.38; stroke: #FBA238; fill: #FBA238;' />
<polygon points='548.61,211.71 549.68,211.13 550.75,210.68 550.75,300.95 549.68,300.95 548.61,300.95 ' style='stroke-width: 0.38; stroke: #FCA338; fill: #FCA338;' />
<polygon points='550.75,210.68 551.81,210.36 551.81,300.95 550.75,300.95 ' style='stroke-width: 0.38; stroke: #FCA437; fill: #FCA437;' />
<polygon points='551.81,210.36 552.88,210.15 552.88,300.95 551.81,300.95 ' style='stroke-width: 0.38; stroke: #FCA537; fill: #FCA537;' />
<polygon points='552.88,210.15 553.95,210.07 555.02,210.14 555.02,300.95 553.95,300.95 552.88,300.95 ' style='stroke-width: 0.38; stroke: #FCA636; fill: #FCA636;' />
<polygon points='555.02,210.14 556.08,210.32 556.08,300.95 555.02,300.95 ' style='stroke-width: 0.38; stroke: #FCA735; fill: #FCA735;' />
<polygon points='556.08,210.32 557.15,210.61 557.15,300.95 556.08,300.95 ' style='stroke-width: 0.38; stroke: #FCA835; fill: #FCA835;' />
<polygon points='557.15,210.61 558.22,210.99 559.29,211.46 559.29,300.95 558.22,300.95 557.15,300.95 ' style='stroke-width: 0.38; stroke: #FCA934; fill: #FCA934;' />
<polygon points='559.29,211.46 560.35,212.01 560.35,300.95 559.29,300.95 ' style='stroke-width: 0.38; stroke: #FDAA33; fill: #FDAA33;' />
<polygon points='560.35,212.01 561.42,212.64 561.42,300.95 560.35,300.95 ' style='stroke-width: 0.38; stroke: #FDAB33; fill: #FDAB33;' />
<polygon points='561.42,212.64 562.49,213.32 563.56,214.04 563.56,300.95 562.49,300.95 561.42,300.95 ' style='stroke-width: 0.38; stroke: #FDAC33; fill: #FDAC33;' />
<polygon points='563.56,214.04 564.62,214.79 564.62,300.95 563.56,300.95 ' style='stroke-width: 0.38; stroke: #FDAD32; fill: #FDAD32;' />
<polygon points='564.62,214.79 565.69,215.57 565.69,300.95 564.62,300.95 ' style='stroke-width: 0.38; stroke: #FDAE32; fill: #FDAE32;' />
<polygon points='565.69,215.57 566.76,216.36 567.83,217.15 567.83,300.95 566.76,300.95 565.69,300.95 ' style='stroke-width: 0.38; stroke: #FDAF31; fill: #FDAF31;' />
<polygon points='567.83,217.15 568.89,217.94 568.89,300.95 567.83,300.95 ' style='stroke-width: 0.38; stroke: #FDB030; fill: #FDB030;' />
<polygon points='568.89,217.94 569.96,218.71 569.96,300.95 568.89,300.95 ' style='stroke-width: 0.38; stroke: #FDB130; fill: #FDB130;' />
<polygon points='569.96,218.71 571.03,219.47 572.10,220.20 572.10,300.95 571.03,300.95 569.96,300.95 ' style='stroke-width: 0.38; stroke: #FDB22F; fill: #FDB22F;' />
<polygon points='572.10,220.20 573.16,220.91 573.16,300.95 572.10,300.95 ' style='stroke-width: 0.38; stroke: #FDB32F; fill: #FDB32F;' />
<polygon points='573.16,220.91 574.23,221.59 574.23,300.95 573.16,300.95 ' style='stroke-width: 0.38; stroke: #FDB42F; fill: #FDB42F;' />
<polygon points='574.23,221.59 575.30,222.26 576.37,222.91 576.37,300.95 575.30,300.95 574.23,300.95 ' style='stroke-width: 0.38; stroke: #FDB52E; fill: #FDB52E;' />
<polygon points='576.37,222.91 577.43,223.55 577.43,300.95 576.37,300.95 ' style='stroke-width: 0.38; stroke: #FEB62D; fill: #FEB62D;' />
<polygon points='577.43,223.55 578.50,224.18 578.50,300.95 577.43,300.95 ' style='stroke-width: 0.38; stroke: #FEB72D; fill: #FEB72D;' />
<polygon points='578.50,224.18 579.57,224.82 580.64,225.47 580.64,300.95 579.57,300.95 578.50,300.95 ' style='stroke-width: 0.38; stroke: #FEB82C; fill: #FEB82C;' />
<polygon points='580.64,225.47 581.70,226.14 581.70,300.95 580.64,300.95 ' style='stroke-width: 0.38; stroke: #FEB92C; fill: #FEB92C;' />
<polygon points='581.70,226.14 582.77,226.85 582.77,300.95 581.70,300.95 ' style='stroke-width: 0.38; stroke: #FEBA2C; fill: #FEBA2C;' />
<polygon points='582.77,226.85 583.84,227.60 584.91,228.40 584.91,300.95 583.84,300.95 582.77,300.95 ' style='stroke-width: 0.38; stroke: #FEBB2B; fill: #FEBB2B;' />
<polygon points='584.91,228.40 585.97,229.26 585.97,300.95 584.91,300.95 ' style='stroke-width: 0.38; stroke: #FEBC2A; fill: #FEBC2A;' />
<polygon points='585.97,229.26 587.04,230.20 587.04,300.95 585.97,300.95 ' style='stroke-width: 0.38; stroke: #FEBD2A; fill: #FEBD2A;' />
<polygon points='587.04,230.20 588.11,231.23 589.18,232.35 589.18,300.95 588.11,300.95 587.04,300.95 ' style='stroke-width: 0.38; stroke: #FEBE2A; fill: #FEBE2A;' />
<polygon points='589.18,232.35 590.25,233.57 590.25,300.95 589.18,300.95 ' style='stroke-width: 0.38; stroke: #FEBF29; fill: #FEBF29;' />
<polygon points='590.25,233.57 591.31,234.87 591.31,300.95 590.25,300.95 ' style='stroke-width: 0.38; stroke: #FEC029; fill: #FEC029;' />
<polygon points='591.31,234.87 592.38,236.28 592.38,300.95 591.31,300.95 ' style='stroke-width: 0.38; stroke: #FDC129; fill: #FDC129;' />
<polygon points='592.38,236.28 593.45,237.82 593.45,300.95 592.38,300.95 ' style='stroke-width: 0.38; stroke: #FDC229; fill: #FDC229;' />
<polygon points='593.45,237.82 594.52,239.46 595.58,241.20 595.58,300.95 594.52,300.95 593.45,300.95 ' style='stroke-width: 0.38; stroke: #FDC328; fill: #FDC328;' />
<polygon points='595.58,241.20 596.65,243.03 596.65,300.95 595.58,300.95 ' style='stroke-width: 0.38; stroke: #FDC427; fill: #FDC427;' />
<polygon points='596.65,243.03 597.72,244.95 597.72,300.95 596.65,300.95 ' style='stroke-width: 0.38; stroke: #FDC527; fill: #FDC527;' />
<polygon points='597.72,244.95 598.79,246.97 599.85,249.06 599.85,300.95 598.79,300.95 597.72,300.95 ' style='stroke-width: 0.38; stroke: #FDC627; fill: #FDC627;' />
<polygon points='599.85,249.06 600.92,251.22 600.92,300.95 599.85,300.95 ' style='stroke-width: 0.38; stroke: #FDC727; fill: #FDC727;' />
<polygon points='600.92,251.22 601.99,253.43 601.99,300.95 600.92,300.95 ' style='stroke-width: 0.38; stroke: #FDC827; fill: #FDC827;' />
<polygon points='601.99,253.43 603.06,255.69 603.06,300.95 601.99,300.95 ' style='stroke-width: 0.38; stroke: #FDC926; fill: #FDC926;' />
<polygon points='603.06,255.69 604.12,257.98 604.12,300.95 603.06,300.95 ' style='stroke-width: 0.38; stroke: #FDCA26; fill: #FDCA26;' />
<polygon points='604.12,257.98 605.19,260.28 606.26,262.59 606.26,300.95 605.19,300.95 604.12,300.95 ' style='stroke-width: 0.38; stroke: #FDCB26; fill: #FDCB26;' />
<polygon points='606.26,262.59 607.33,264.89 607.33,300.95 606.26,300.95 ' style='stroke-width: 0.38; stroke: #FCCC25; fill: #FCCC25;' />
<polygon points='607.33,264.89 608.39,267.17 608.39,300.95 607.33,300.95 ' style='stroke-width: 0.38; stroke: #FCCD25; fill: #FCCD25;' />
<polygon points='608.39,267.17 609.46,269.41 610.53,271.60 610.53,300.95 609.46,300.95 608.39,300.95 ' style='stroke-width: 0.38; stroke: #FCCE25; fill: #FCCE25;' />
<polygon points='610.53,271.60 611.60,273.74 611.60,300.95 610.53,300.95 ' style='stroke-width: 0.38; stroke: #FCCF25; fill: #FCCF25;' />
<polygon points='611.60,273.74 612.66,275.82 612.66,300.95 611.60,300.95 ' style='stroke-width: 0.38; stroke: #FCD025; fill: #FCD025;' />
<polygon points='612.66,275.82 613.73,277.83 613.73,300.95 612.66,300.95 ' style='stroke-width: 0.38; stroke: #FCD125; fill: #FCD125;' />
<polygon points='613.73,277.83 614.80,279.75 614.80,300.95 613.73,300.95 ' style='stroke-width: 0.38; stroke: #FCD225; fill: #FCD225;' />
<polygon points='614.80,279.75 615.87,281.57 616.93,283.30 616.93,300.95 615.87,300.95 614.80,300.95 ' style='stroke-width: 0.38; stroke: #FBD324; fill: #FBD324;' />
<polygon points='616.93,283.30 618.00,284.95 618.00,300.95 616.93,300.95 ' style='stroke-width: 0.38; stroke: #FBD424; fill: #FBD424;' />
<polygon points='618.00,284.95 619.07,286.50 619.07,300.95 618.00,300.95 ' style='stroke-width: 0.38; stroke: #FBD524; fill: #FBD524;' />
<polygon points='619.07,286.50 620.14,287.94 620.14,300.95 619.07,300.95 ' style='stroke-width: 0.38; stroke: #FBD624; fill: #FBD624;' />
<polygon points='620.14,287.94 621.20,289.28 621.20,300.95 620.14,300.95 ' style='stroke-width: 0.38; stroke: #FBD724; fill: #FBD724;' />
<polygon points='621.20,289.28 622.27,290.52 623.34,291.67 623.34,300.95 622.27,300.95 621.20,300.95 ' style='stroke-width: 0.38; stroke: #FAD824; fill: #FAD824;' />
<polygon points='623.34,291.67 624.41,292.72 624.41,300.95 623.34,300.95 ' style='stroke-width: 0.38; stroke: #FAD924; fill: #FAD924;' />
<polygon points='624.41,292.72 625.47,293.69 625.47,300.95 624.41,300.95 ' style='stroke-width: 0.38; stroke: #FADA24; fill: #FADA24;' />
<polygon points='625.47,293.69 626.54,294.55 626.54,300.95 625.47,300.95 ' style='stroke-width: 0.38; stroke: #F9DB24; fill: #F9DB24;' />
<polygon points='626.54,294.55 627.61,295.34 627.61,300.95 626.54,300.95 ' style='stroke-width: 0.38; stroke: #F9DC24; fill: #F9DC24;' />
<polygon points='627.61,295.34 628.68,296.05 629.74,296.70 629.74,300.95 628.68,300.95 627.61,300.95 ' style='stroke-width: 0.38; stroke: #F9DD25; fill: #F9DD25;' />
<polygon points='629.74,296.70 630.81,297.27 630.81,300.95 629.74,300.95 ' style='stroke-width: 0.38; stroke: #F8DE25; fill: #F8DE25;' />
<polygon points='630.81,297.27 631.88,297.77 631.88,300.95 630.81,300.95 ' style='stroke-width: 0.38; stroke: #F8DF25; fill: #F8DF25;' />
<polygon points='631.88,297.77 632.95,298.21 632.95,300.95 631.88,300.95 ' style='stroke-width: 0.38; stroke: #F8E025; fill: #F8E025;' />
<polygon points='632.95,298.21 634.01,298.60 634.01,300.95 632.95,300.95 ' style='stroke-width: 0.38; stroke: #F8E125; fill: #F8E125;' />
<polygon points='634.01,298.60 635.08,298.95 636.15,299.26 636.15,300.95 635.08,300.95 634.01,300.95 ' style='stroke-width: 0.38; stroke: #F7E225; fill: #F7E225;' />
<polygon points='636.15,299.26 637.22,299.51 637.22,300.95 636.15,300.95 ' style='stroke-width: 0.38; stroke: #F7E325; fill: #F7E325;' />
<polygon points='637.22,299.51 638.28,299.74 638.28,300.95 637.22,300.95 ' style='stroke-width: 0.38; stroke: #F7E425; fill: #F7E425;' />
<polygon points='638.28,299.74 639.35,299.93 639.35,300.95 638.28,300.95 ' style='stroke-width: 0.38; stroke: #F6E526; fill: #F6E526;' />
<polygon points='639.35,299.93 639.35,300.95 ' style='stroke-width: 0.38; stroke: #F6E626; fill: #F6E626;' />
<polyline points='471.75,299.81 472.82,299.63 473.88,299.43 474.95,299.20 476.02,298.95 477.09,298.67 478.15,298.35 479.22,298.01 480.29,297.62 481.36,297.21 482.42,296.75 483.49,296.25 484.56,295.71 485.63,295.12 486.69,294.49 487.76,293.81 488.83,293.09 489.90,292.31 490.97,291.48 492.03,290.61 493.10,289.69 494.17,288.72 495.24,287.69 496.30,286.62 497.37,285.51 498.44,284.36 499.51,283.16 500.57,281.91 501.64,280.63 502.71,279.31 503.78,277.96 504.84,276.58 505.91,275.16 506.98,273.71 508.05,272.24 509.11,270.74 510.18,269.22 511.25,267.67 512.32,266.11 513.38,264.52 514.45,262.92 515.52,261.30 516.59,259.65 517.65,257.98 518.72,256.30 519.79,254.60 520.86,252.88 521.92,251.14 522.99,249.37 524.06,247.59 525.13,245.79 526.19,243.98 527.26,242.15 528.33,240.31 529.40,238.46 530.46,236.60 531.53,234.75 532.60,232.90 533.67,231.07 534.73,229.26 535.80,227.48 536.87,225.74 537.94,224.03 539.00,222.40 540.07,220.83 541.14,219.33 542.21,217.92 543.27,216.59 544.34,215.39 545.41,214.30 546.48,213.32 547.54,212.46 548.61,211.71 549.68,211.13 550.75,210.68 551.81,210.36 552.88,210.15 553.95,210.07 555.02,210.14 556.08,210.32 557.15,210.61 558.22,210.99 559.29,211.46 560.35,212.01 561.42,212.64 562.49,213.32 563.56,214.04 564.62,214.79 565.69,215.57 566.76,216.36 567.83,217.15 568.89,217.94 569.96,218.71 571.03,219.47 572.10,220.20 573.16,220.91 574.23,221.59 575.30,222.26 576.37,222.91 577.43,223.55 578.50,224.18 579.57,224.82 580.64,225.47 581.70,226.14 582.77,226.85 583.84,227.60 584.91,228.40 585.97,229.26 587.04,230.20 588.11,231.23 589.18,232.35 590.25,233.57 591.31,234.87 592.38,236.28 593.45,237.82 594.52,239.46 595.58,241.20 596.65,243.03 597.72,244.95 598.79,246.97 599.85,249.06 600.92,251.22 601.99,253.43 603.06,255.69 604.12,257.98 605.19,260.28 606.26,262.59 607.33,264.89 608.39,267.17 609.46,269.41 610.53,271.60 611.60,273.74 612.66,275.82 613.73,277.83 614.80,279.75 615.87,281.57 616.93,283.30 618.00,284.95 619.07,286.50 620.14,287.94 621.20,289.28 622.27,290.52 623.34,291.67 624.41,292.72 625.47,293.69 626.54,294.55 627.61,295.34 628.68,296.05 629.74,296.70 630.81,297.27 631.88,297.77 632.95,298.21 634.01,298.60 635.08,298.95 636.15,299.26 637.22,299.51 638.28,299.74 639.35,299.93 ' style='stroke-width: 1.07;' />
<polygon points='454.67,333.29 455.74,333.15 456.80,333.00 456.80,334.35 455.74,334.35 454.67,334.35 ' style='stroke-width: 0.38; stroke: #E56A5D; fill: #E56A5D;' />
<polygon points='456.80,333.00 457.87,332.84 458.94,332.66 458.94,334.35 457.87,334.35 456.80,334.35 ' style='stroke-width: 0.38; stroke: #E56B5D; fill: #E56B5D;' />
<polygon points='458.94,332.66 460.01,332.46 461.07,332.26 461.07,334.35 460.01,334.35 458.94,334.35 ' style='stroke-width: 0.38; stroke: #E66C5C; fill: #E66C5C;' />
<polygon points='461.07,332.26 462.14,332.03 462.14,334.35 461.07,334.35 ' style='stroke-width: 0.38; stroke: #E76D5B; fill: #E76D5B;' />
<polygon points='462.14,332.03 463.21,331.79 463.21,334.35 462.14,334.35 ' style='stroke-width: 0.38; stroke: #E76E5B; fill: #E76E5B;' />
<polygon points='463.21,331.79 464.28,331.54 465.34,331.28 465.34,334.35 464.28,334.35 463.21,334.35 ' style='stroke-width: 0.38; stroke: #E76F5A; fill: #E76F5A;' />
<polygon points='465.34,331.28 466.41,331.00 467.48,330.70 467.48,334.35 466.41,334.35 465.34,334.35 ' style='stroke-width: 0.38; stroke: #E87059; fill: #E87059;' />
<polygon points='467.48,330.70 468.55,330.39 469.61,330.07 469.61,334.35 468.55,334.35 467.48,334.35 ' style='stroke-width: 0.38; stroke: #E97158; fill: #E97158;' />
<polygon points='469.61,330.07 470.68,329.74 471.75,329.39 471.75,334.35 470.68,334.35 469.61,334.35 ' style='stroke-width: 0.38; stroke: #E97257; fill: #E97257;' />
<polygon points='471.75,329.39 472.82,329.04 472.82,334.35 471.75,334.35 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,329.04 473.88,328.67 473.88,334.35 472.82,334.35 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,328.67 474.95,328.29 476.02,327.91 476.02,334.35 474.95,334.35 473.88,334.35 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,327.91 477.09,327.51 478.15,327.11 478.15,334.35 477.09,334.35 476.02,334.35 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,327.11 479.22,326.70 480.29,326.28 480.29,334.35 479.22,334.35 478.15,334.35 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,326.28 481.36,325.85 481.36,334.35 480.29,334.35 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,325.85 482.42,325.42 482.42,334.35 481.36,334.35 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,325.42 483.49,324.98 484.56,324.54 484.56,334.35 483.49,334.35 482.42,334.35 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,324.54 485.63,324.08 486.69,323.63 486.69,334.35 485.63,334.35 484.56,334.35 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polygon points='486.69,323.63 487.76,323.16 488.83,322.68 488.83,334.35 487.76,334.35 486.69,334.35 ' style='stroke-width: 0.38; stroke: #EF7C51; fill: #EF7C51;' />
<polygon points='488.83,322.68 489.90,322.20 489.90,334.35 488.83,334.35 ' style='stroke-width: 0.38; stroke: #EF7D50; fill: #EF7D50;' />
<polygon points='489.90,322.20 490.97,321.71 490.97,334.35 489.90,334.35 ' style='stroke-width: 0.38; stroke: #EF7E50; fill: #EF7E50;' />
<polygon points='490.97,321.71 492.03,321.21 493.10,320.70 493.10,334.35 492.03,334.35 490.97,334.35 ' style='stroke-width: 0.38; stroke: #F07F4F; fill: #F07F4F;' />
<polygon points='493.10,320.70 494.17,320.18 495.24,319.64 495.24,334.35 494.17,334.35 493.10,334.35 ' style='stroke-width: 0.38; stroke: #F0804E; fill: #F0804E;' />
<polygon points='495.24,319.64 496.30,319.10 497.37,318.54 497.37,334.35 496.30,334.35 495.24,334.35 ' style='stroke-width: 0.38; stroke: #F1814D; fill: #F1814D;' />
<polygon points='497.37,318.54 498.44,317.97 498.44,334.35 497.37,334.35 ' style='stroke-width: 0.38; stroke: #F1824C; fill: #F1824C;' />
<polygon points='498.44,317.97 499.51,317.38 499.51,334.35 498.44,334.35 ' style='stroke-width: 0.38; stroke: #F1834C; fill: #F1834C;' />
<polygon points='499.51,317.38 500.57,316.77 501.64,316.15 501.64,334.35 500.57,334.35 499.51,334.35 ' style='stroke-width: 0.38; stroke: #F2844B; fill: #F2844B;' />
<polygon points='501.64,316.15 502.71,315.50 503.78,314.84 503.78,334.35 502.71,334.35 501.64,334.35 ' style='stroke-width: 0.38; stroke: #F3854B; fill: #F3854B;' />
<polygon points='503.78,314.84 504.84,314.15 504.84,334.35 503.78,334.35 ' style='stroke-width: 0.38; stroke: #F3864A; fill: #F3864A;' />
<polygon points='504.84,314.15 505.91,313.43 505.91,334.35 504.84,334.35 ' style='stroke-width: 0.38; stroke: #F3874A; fill: #F3874A;' />
<polygon points='505.91,313.43 506.98,312.68 508.05,311.90 508.05,334.35 506.98,334.35 505.91,334.35 ' style='stroke-width: 0.38; stroke: #F48849; fill: #F48849;' />
<polygon points='508.05,311.90 509.11,311.09 510.18,310.23 510.18,334.35 509.11,334.35 508.05,334.35 ' style='stroke-width: 0.38; stroke: #F48948; fill: #F48948;' />
<polygon points='510.18,310.23 511.25,309.33 511.25,334.35 510.18,334.35 ' style='stroke-width: 0.38; stroke: #F58A47; fill: #F58A47;' />
<polygon points='511.25,309.33 512.32,308.38 512.32,334.35 511.25,334.35 ' style='stroke-width: 0.38; stroke: #F58B47; fill: #F58B47;' />
<polygon points='512.32,308.38 513.38,307.38 514.45,306.32 514.45,334.35 513.38,334.35 512.32,334.35 ' style='stroke-width: 0.38; stroke: #F58C46; fill: #F58C46;' />
<polygon points='514.45,306.32 515.52,305.22 516.59,304.03 516.59,334.35 515.52,334.35 514.45,334.35 ' style='stroke-width: 0.38; stroke: #F68D45; fill: #F68D45;' />
<polygon points='516.59,304.03 517.65,302.78 517.65,334.35 516.59,334.35 ' style='stroke-width: 0.38; stroke: #F68E44; fill: #F68E44;' />
<polygon points='517.65,302.78 518.72,301.45 518.72,334.35 517.65,334.35 ' style='stroke-width: 0.38; stroke: #F68F44; fill: #F68F44;' />
<polygon points='518.72,301.45 519.79,300.06 520.86,298.59 520.86,334.35 519.79,334.35 518.72,334.35 ' style='stroke-width: 0.38; stroke: #F79044; fill: #F79044;' />
<polygon points='520.86,298.59 521.92,297.03 522.99,295.38 522.99,334.35 521.92,334.35 520.86,334.35 ' style='stroke-width: 0.38; stroke: #F79143; fill: #F79143;' />
<polygon points='522.99,295.38 524.06,293.66 524.06,334.35 522.99,334.35 ' style='stroke-width: 0.38; stroke: #F79242; fill: #F79242;' />
<polygon points='524.06,293.66 525.13,291.85 525.13,334.35 524.06,334.35 ' style='stroke-width: 0.38; stroke: #F79342; fill: #F79342;' />
<polygon points='525.13,291.85 526.19,289.97 527.26,288.01 527.26,334.35 526.19,334.35 525.13,334.35 ' style='stroke-width: 0.38; stroke: #F89441; fill: #F89441;' />
<polygon points='527.26,288.01 528.33,285.95 529.40,283.83 529.40,334.35 528.33,334.35 527.26,334.35 ' style='stroke-width: 0.38; stroke: #F89540; fill: #F89540;' />
<polygon points='529.40,283.83 530.46,281.65 530.46,334.35 529.40,334.35 ' style='stroke-width: 0.38; stroke: #F9963F; fill: #F9963F;' />
<polygon points='530.46,281.65 531.53,279.40 531.53,334.35 530.46,334.35 ' style='stroke-width: 0.38; stroke: #F9973F; fill: #F9973F;' />
<polygon points='531.53,279.40 532.60,277.10 533.67,274.75 533.67,334.35 532.60,334.35 531.53,334.35 ' style='stroke-width: 0.38; stroke: #F9983E; fill: #F9983E;' />
<polygon points='533.67,274.75 534.73,272.36 534.73,334.35 533.67,334.35 ' style='stroke-width: 0.38; stroke: #F9993E; fill: #F9993E;' />
<polygon points='534.73,272.36 535.80,269.95 535.80,334.35 534.73,334.35 ' style='stroke-width: 0.38; stroke: #F99A3E; fill: #F99A3E;' />
<polygon points='535.80,269.95 536.87,267.53 537.94,265.10 537.94,334.35 536.87,334.35 535.80,334.35 ' style='stroke-width: 0.38; stroke: #FA9B3D; fill: #FA9B3D;' />
<polygon points='537.94,265.10 539.00,262.68 540.07,260.29 540.07,334.35 539.00,334.35 537.94,334.35 ' style='stroke-width: 0.38; stroke: #FA9C3C; fill: #FA9C3C;' />
<polygon points='540.07,260.29 541.14,257.92 541.14,334.35 540.07,334.35 ' style='stroke-width: 0.38; stroke: #FA9D3B; fill: #FA9D3B;' />
<polygon points='541.14,257.92 542.21,255.61 542.21,334.35 541.14,334.35 ' style='stroke-width: 0.38; stroke: #FA9E3B; fill: #FA9E3B;' />
<polygon points='542.21,255.61 543.27,253.34 544.34,251.17 544.34,334.35 543.27,334.35 542.21,334.35 ' style='stroke-width: 0.38; stroke: #FB9F3A; fill: #FB9F3A;' />
<polygon points='544.34,251.17 545.41,249.09 545.41,334.35 544.34,334.35 ' style='stroke-width: 0.38; stroke: #FBA039; fill: #FBA039;' />
<polygon points='545.41,249.09 546.48,247.09 546.48,334.35 545.41,334.35 ' style='stroke-width: 0.38; stroke: #FBA139; fill: #FBA139;' />
<polygon points='546.48,247.09 547.54,245.20 548.61,243.43 548.61,334.35 547.54,334.35 546.48,334.35 ' style='stroke-width: 0.38; stroke: #FBA238; fill: #FBA238;' />
<polygon points='548.61,243.43 549.68,241.81 550.75,240.33 550.75,334.35 549.68,334.35 548.61,334.35 ' style='stroke-width: 0.38; stroke: #FCA338; fill: #FCA338;' />
<polygon points='550.75,240.33 551.81,238.99 551.81,334.35 550.75,334.35 ' style='stroke-width: 0.38; stroke: #FCA437; fill: #FCA437;' />
<polygon points='551.81,238.99 552.88,237.79 552.88,334.35 551.81,334.35 ' style='stroke-width: 0.38; stroke: #FCA537; fill: #FCA537;' />
<polygon points='552.88,237.79 553.95,236.75 555.02,235.90 555.02,334.35 553.95,334.35 552.88,334.35 ' style='stroke-width: 0.38; stroke: #FCA636; fill: #FCA636;' />
<polygon points='555.02,235.90 556.08,235.23 556.08,334.35 555.02,334.35 ' style='stroke-width: 0.38; stroke: #FCA735; fill: #FCA735;' />
<polygon points='556.08,235.23 557.15,234.71 557.15,334.35 556.08,334.35 ' style='stroke-width: 0.38; stroke: #FCA835; fill: #FCA835;' />
<polygon points='557.15,234.71 558.22,234.35 559.29,234.15 559.29,334.35 558.22,334.35 557.15,334.35 ' style='stroke-width: 0.38; stroke: #FCA934; fill: #FCA934;' />
<polygon points='559.29,234.15 560.35,234.14 560.35,334.35 559.29,334.35 ' style='stroke-width: 0.38; stroke: #FDAA33; fill: #FDAA33;' />
<polygon points='560.35,234.14 561.42,234.31 561.42,334.35 560.35,334.35 ' style='stroke-width: 0.38; stroke: #FDAB33; fill: #FDAB33;' />
<polygon points='561.42,234.31 562.49,234.62 563.56,235.08 563.56,334.35 562.49,334.35 561.42,334.35 ' style='stroke-width: 0.38; stroke: #FDAC33; fill: #FDAC33;' />
<polygon points='563.56,235.08 564.62,235.67 564.62,334.35 563.56,334.35 ' style='stroke-width: 0.38; stroke: #FDAD32; fill: #FDAD32;' />
<polygon points='564.62,235.67 565.69,236.42 565.69,334.35 564.62,334.35 ' style='stroke-width: 0.38; stroke: #FDAE32; fill: #FDAE32;' />
<polygon points='565.69,236.42 566.76,237.31 567.83,238.32 567.83,334.35 566.76,334.35 565.69,334.35 ' style='stroke-width: 0.38; stroke: #FDAF31; fill: #FDAF31;' />
<polygon points='567.83,238.32 568.89,239.43 568.89,334.35 567.83,334.35 ' style='stroke-width: 0.38; stroke: #FDB030; fill: #FDB030;' />
<polygon points='568.89,239.43 569.96,240.63 569.96,334.35 568.89,334.35 ' style='stroke-width: 0.38; stroke: #FDB130; fill: #FDB130;' />
<polygon points='569.96,240.63 571.03,241.94 572.10,243.34 572.10,334.35 571.03,334.35 569.96,334.35 ' style='stroke-width: 0.38; stroke: #FDB22F; fill: #FDB22F;' />
<polygon points='572.10,243.34 573.16,244.81 573.16,334.35 572.10,334.35 ' style='stroke-width: 0.38; stroke: #FDB32F; fill: #FDB32F;' />
<polygon points='573.16,244.81 574.23,246.34 574.23,334.35 573.16,334.35 ' style='stroke-width: 0.38; stroke: #FDB42F; fill: #FDB42F;' />
<polygon points='574.23,246.34 575.30,247.93 576.37,249.56 576.37,334.35 575.30,334.35 574.23,334.35 ' style='stroke-width: 0.38; stroke: #FDB52E; fill: #FDB52E;' />
<polygon points='576.37,249.56 577.43,251.24 577.43,334.35 576.37,334.35 ' style='stroke-width: 0.38; stroke: #FEB62D; fill: #FEB62D;' />
<polygon points='577.43,251.24 578.50,252.95 578.50,334.35 577.43,334.35 ' style='stroke-width: 0.38; stroke: #FEB72D; fill: #FEB72D;' />
<polygon points='578.50,252.95 579.57,254.69 580.64,256.44 580.64,334.35 579.57,334.35 578.50,334.35 ' style='stroke-width: 0.38; stroke: #FEB82C; fill: #FEB82C;' />
<polygon points='580.64,256.44 581.70,258.21 581.70,334.35 580.64,334.35 ' style='stroke-width: 0.38; stroke: #FEB92C; fill: #FEB92C;' />
<polygon points='581.70,258.21 582.77,259.99 582.77,334.35 581.70,334.35 ' style='stroke-width: 0.38; stroke: #FEBA2C; fill: #FEBA2C;' />
<polygon points='582.77,259.99 583.84,261.78 584.91,263.58 584.91,334.35 583.84,334.35 582.77,334.35 ' style='stroke-width: 0.38; stroke: #FEBB2B; fill: #FEBB2B;' />
<polygon points='584.91,263.58 585.97,265.37 585.97,334.35 584.91,334.35 ' style='stroke-width: 0.38; stroke: #FEBC2A; fill: #FEBC2A;' />
<polygon points='585.97,265.37 587.04,267.17 587.04,334.35 585.97,334.35 ' style='stroke-width: 0.38; stroke: #FEBD2A; fill: #FEBD2A;' />
<polygon points='587.04,267.17 588.11,268.97 589.18,270.77 589.18,334.35 588.11,334.35 587.04,334.35 ' style='stroke-width: 0.38; stroke: #FEBE2A; fill: #FEBE2A;' />
<polygon points='589.18,270.77 590.25,272.57 590.25,334.35 589.18,334.35 ' style='stroke-width: 0.38; stroke: #FEBF29; fill: #FEBF29;' />
<polygon points='590.25,272.57 591.31,274.37 591.31,334.35 590.25,334.35 ' style='stroke-width: 0.38; stroke: #FEC029; fill: #FEC029;' />
<polygon points='591.31,274.37 592.38,276.16 592.38,334.35 591.31,334.35 ' style='stroke-width: 0.38; stroke: #FDC129; fill: #FDC129;' />
<polygon points='592.38,276.16 593.45,277.96 593.45,334.35 592.38,334.35 ' style='stroke-width: 0.38; stroke: #FDC229; fill: #FDC229;' />
<polygon points='593.45,277.96 594.52,279.75 595.58,281.54 595.58,334.35 594.52,334.35 593.45,334.35 ' style='stroke-width: 0.38; stroke: #FDC328; fill: #FDC328;' />
<polygon points='595.58,281.54 596.65,283.32 596.65,334.35 595.58,334.35 ' style='stroke-width: 0.38; stroke: #FDC427; fill: #FDC427;' />
<polygon points='596.65,283.32 597.72,285.11 597.72,334.35 596.65,334.35 ' style='stroke-width: 0.38; stroke: #FDC527; fill: #FDC527;' />
<polygon points='597.72,285.11 598.79,286.89 599.85,288.66 599.85,334.35 598.79,334.35 597.72,334.35 ' style='stroke-width: 0.38; stroke: #FDC627; fill: #FDC627;' />
<polygon points='599.85,288.66 600.92,290.43 600.92,334.35 599.85,334.35 ' style='stroke-width: 0.38; stroke: #FDC727; fill: #FDC727;' />
<polygon points='600.92,290.43 601.99,292.19 601.99,334.35 600.92,334.35 ' style='stroke-width: 0.38; stroke: #FDC827; fill: #FDC827;' />
<polygon points='601.99,292.19 603.06,293.94 603.06,334.35 601.99,334.35 ' style='stroke-width: 0.38; stroke: #FDC926; fill: #FDC926;' />
<polygon points='603.06,293.94 604.12,295.68 604.12,334.35 603.06,334.35 ' style='stroke-width: 0.38; stroke: #FDCA26; fill: #FDCA26;' />
<polygon points='604.12,295.68 605.19,297.40 606.26,299.10 606.26,334.35 605.19,334.35 604.12,334.35 ' style='stroke-width: 0.38; stroke: #FDCB26; fill: #FDCB26;' />
<polygon points='606.26,299.10 607.33,300.79 607.33,334.35 606.26,334.35 ' style='stroke-width: 0.38; stroke: #FCCC25; fill: #FCCC25;' />
<polygon points='607.33,300.79 608.39,302.45 608.39,334.35 607.33,334.35 ' style='stroke-width: 0.38; stroke: #FCCD25; fill: #FCCD25;' />
<polygon points='608.39,302.45 609.46,304.08 610.53,305.68 610.53,334.35 609.46,334.35 608.39,334.35 ' style='stroke-width: 0.38; stroke: #FCCE25; fill: #FCCE25;' />
<polygon points='610.53,305.68 611.60,307.25 611.60,334.35 610.53,334.35 ' style='stroke-width: 0.38; stroke: #FCCF25; fill: #FCCF25;' />
<polygon points='611.60,307.25 612.66,308.79 612.66,334.35 611.60,334.35 ' style='stroke-width: 0.38; stroke: #FCD025; fill: #FCD025;' />
<polygon points='612.66,308.79 613.73,310.29 613.73,334.35 612.66,334.35 ' style='stroke-width: 0.38; stroke: #FCD125; fill: #FCD125;' />
<polygon points='613.73,310.29 614.80,311.75 614.80,334.35 613.73,334.35 ' style='stroke-width: 0.38; stroke: #FCD225; fill: #FCD225;' />
<polygon points='614.80,311.75 615.87,313.16 616.93,314.52 616.93,334.35 615.87,334.35 614.80,334.35 ' style='stroke-width: 0.38; stroke: #FBD324; fill: #FBD324;' />
<polygon points='616.93,314.52 618.00,315.85 618.00,334.35 616.93,334.35 ' style='stroke-width: 0.38; stroke: #FBD424; fill: #FBD424;' />
<polygon points='618.00,315.85 619.07,317.12 619.07,334.35 618.00,334.35 ' style='stroke-width: 0.38; stroke: #FBD524; fill: #FBD524;' />
<polygon points='619.07,317.12 620.14,318.34 620.14,334.35 619.07,334.35 ' style='stroke-width: 0.38; stroke: #FBD624; fill: #FBD624;' />
<polygon points='620.14,318.34 621.20,319.51 621.20,334.35 620.14,334.35 ' style='stroke-width: 0.38; stroke: #FBD724; fill: #FBD724;' />
<polygon points='621.20,319.51 622.27,320.62 623.34,321.69 623.34,334.35 622.27,334.35 621.20,334.35 ' style='stroke-width: 0.38; stroke: #FAD824; fill: #FAD824;' />
<polygon points='623.34,321.69 624.41,322.70 624.41,334.35 623.34,334.35 ' style='stroke-width: 0.38; stroke: #FAD924; fill: #FAD924;' />
<polygon points='624.41,322.70 625.47,323.66 625.47,334.35 624.41,334.35 ' style='stroke-width: 0.38; stroke: #FADA24; fill: #FADA24;' />
<polygon points='625.47,323.66 626.54,324.56 626.54,334.35 625.47,334.35 ' style='stroke-width: 0.38; stroke: #F9DB24; fill: #F9DB24;' />
<polygon points='626.54,324.56 627.61,325.41 627.61,334.35 626.54,334.35 ' style='stroke-width: 0.38; stroke: #F9DC24; fill: #F9DC24;' />
<polygon points='627.61,325.41 628.68,326.20 629.74,326.95 629.74,334.35 628.68,334.35 627.61,334.35 ' style='stroke-width: 0.38; stroke: #F9DD25; fill: #F9DD25;' />
<polygon points='629.74,326.95 630.81,327.66 630.81,334.35 629.74,334.35 ' style='stroke-width: 0.38; stroke: #F8DE25; fill: #F8DE25;' />
<polygon points='630.81,327.66 631.88,328.30 631.88,334.35 630.81,334.35 ' style='stroke-width: 0.38; stroke: #F8DF25; fill: #F8DF25;' />
<polygon points='631.88,328.30 632.95,328.90 632.95,334.35 631.88,334.35 ' style='stroke-width: 0.38; stroke: #F8E025; fill: #F8E025;' />
<polygon points='632.95,328.90 634.01,329.45 634.01,334.35 632.95,334.35 ' style='stroke-width: 0.38; stroke: #F8E125; fill: #F8E125;' />
<polygon points='634.01,329.45 635.08,329.96 636.15,330.44 636.15,334.35 635.08,334.35 634.01,334.35 ' style='stroke-width: 0.38; stroke: #F7E225; fill: #F7E225;' />
<polygon points='636.15,330.44 637.22,330.86 637.22,334.35 636.15,334.35 ' style='stroke-width: 0.38; stroke: #F7E325; fill: #F7E325;' />
<polygon points='637.22,330.86 638.28,331.25 638.28,334.35 637.22,334.35 ' style='stroke-width: 0.38; stroke: #F7E425; fill: #F7E425;' />
<polygon points='638.28,331.25 639.35,331.61 639.35,334.35 638.28,334.35 ' style='stroke-width: 0.38; stroke: #F6E526; fill: #F6E526;' />
<polygon points='639.35,331.61 640.42,331.94 640.42,334.35 639.35,334.35 ' style='stroke-width: 0.38; stroke: #F6E626; fill: #F6E626;' />
<polygon points='640.42,331.94 641.49,332.23 641.49,334.35 640.42,334.35 ' style='stroke-width: 0.38; stroke: #F6E726; fill: #F6E726;' />
<polygon points='641.49,332.23 642.55,332.49 642.55,334.35 641.49,334.35 ' style='stroke-width: 0.38; stroke: #F6E826; fill: #F6E826;' />
<polygon points='642.55,332.49 643.62,332.72 644.69,332.93 644.69,334.35 643.62,334.35 642.55,334.35 ' style='stroke-width: 0.38; stroke: #F5E926; fill: #F5E926;' />
<polygon points='644.69,332.93 645.76,333.12 645.76,334.35 644.69,334.35 ' style='stroke-width: 0.38; stroke: #F5EA27; fill: #F5EA27;' />
<polygon points='645.76,333.12 646.82,333.29 646.82,334.35 645.76,334.35 ' style='stroke-width: 0.38; stroke: #F5EB27; fill: #F5EB27;' />
<polygon points='646.82,333.29 646.82,334.35 ' style='stroke-width: 0.38; stroke: #F4EC27; fill: #F4EC27;' />
<polyline points='454.67,333.29 455.74,333.15 456.80,333.00 457.87,332.84 458.94,332.66 460.01,332.46 461.07,332.26 462.14,332.03 463.21,331.79 464.28,331.54 465.34,331.28 466.41,331.00 467.48,330.70 468.55,330.39 469.61,330.07 470.68,329.74 471.75,329.39 472.82,329.04 473.88,328.67 474.95,328.29 476.02,327.91 477.09,327.51 478.15,327.11 479.22,326.70 480.29,326.28 481.36,325.85 482.42,325.42 483.49,324.98 484.56,324.54 485.63,324.08 486.69,323.63 487.76,323.16 488.83,322.68 489.90,322.20 490.97,321.71 492.03,321.21 493.10,320.70 494.17,320.18 495.24,319.64 496.30,319.10 497.37,318.54 498.44,317.97 499.51,317.38 500.57,316.77 501.64,316.15 502.71,315.50 503.78,314.84 504.84,314.15 505.91,313.43 506.98,312.68 508.05,311.90 509.11,311.09 510.18,310.23 511.25,309.33 512.32,308.38 513.38,307.38 514.45,306.32 515.52,305.22 516.59,304.03 517.65,302.78 518.72,301.45 519.79,300.06 520.86,298.59 521.92,297.03 522.99,295.38 524.06,293.66 525.13,291.85 526.19,289.97 527.26,288.01 528.33,285.95 529.40,283.83 530.46,281.65 531.53,279.40 532.60,277.10 533.67,274.75 534.73,272.36 535.80,269.95 536.87,267.53 537.94,265.10 539.00,262.68 540.07,260.29 541.14,257.92 542.21,255.61 543.27,253.34 544.34,251.17 545.41,249.09 546.48,247.09 547.54,245.20 548.61,243.43 549.68,241.81 550.75,240.33 551.81,238.99 552.88,237.79 553.95,236.75 555.02,235.90 556.08,235.23 557.15,234.71 558.22,234.35 559.29,234.15 560.35,234.14 561.42,234.31 562.49,234.62 563.56,235.08 564.62,235.67 565.69,236.42 566.76,237.31 567.83,238.32 568.89,239.43 569.96,240.63 571.03,241.94 572.10,243.34 573.16,244.81 574.23,246.34 575.30,247.93 576.37,249.56 577.43,251.24 578.50,252.95 579.57,254.69 580.64,256.44 581.70,258.21 582.77,259.99 583.84,261.78 584.91,263.58 585.97,265.37 587.04,267.17 588.11,268.97 589.18,270.77 590.25,272.57 591.31,274.37 592.38,276.16 593.45,277.96 594.52,279.75 595.58,281.54 596.65,283.32 597.72,285.11 598.79,286.89 599.85,288.66 600.92,290.43 601.99,292.19 603.06,293.94 604.12,295.68 605.19,297.40 606.26,299.10 607.33,300.79 608.39,302.45 609.46,304.08 610.53,305.68 611.60,307.25 612.66,308.79 613.73,310.29 614.80,311.75 615.87,313.16 616.93,314.52 618.00,315.85 619.07,317.12 620.14,318.34 621.20,319.51 622.27,320.62 623.34,321.69 624.41,322.70 625.47,323.66 626.54,324.56 627.61,325.41 628.68,326.20 629.74,326.95 630.81,327.66 631.88,328.30 632.95,328.90 634.01,329.45 635.08,329.96 636.15,330.44 637.22,330.86 638.28,331.25 639.35,331.61 640.42,331.94 641.49,332.23 642.55,332.49 643.62,332.72 644.69,332.93 645.76,333.12 646.82,333.29 ' style='stroke-width: 1.07;' />
<polygon points='465.34,366.59 466.41,366.41 467.48,366.20 467.48,367.76 466.41,367.76 465.34,367.76 ' style='stroke-width: 0.38; stroke: #E87059; fill: #E87059;' />
<polygon points='467.48,366.20 468.55,365.95 469.61,365.69 469.61,367.76 468.55,367.76 467.48,367.76 ' style='stroke-width: 0.38; stroke: #E97158; fill: #E97158;' />
<polygon points='469.61,365.69 470.68,365.39 471.75,365.06 471.75,367.76 470.68,367.76 469.61,367.76 ' style='stroke-width: 0.38; stroke: #E97257; fill: #E97257;' />
<polygon points='471.75,365.06 472.82,364.69 472.82,367.76 471.75,367.76 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,364.69 473.88,364.28 473.88,367.76 472.82,367.76 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,364.28 474.95,363.83 476.02,363.35 476.02,367.76 474.95,367.76 473.88,367.76 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,363.35 477.09,362.82 478.15,362.24 478.15,367.76 477.09,367.76 476.02,367.76 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,362.24 479.22,361.61 480.29,360.93 480.29,367.76 479.22,367.76 478.15,367.76 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,360.93 481.36,360.21 481.36,367.76 480.29,367.76 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,360.21 482.42,359.44 482.42,367.76 481.36,367.76 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,359.44 483.49,358.62 484.56,357.74 484.56,367.76 483.49,367.76 482.42,367.76 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,357.74 485.63,356.81 486.69,355.83 486.69,367.76 485.63,367.76 484.56,367.76 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polygon points='486.69,355.83 487.76,354.81 488.83,353.73 488.83,367.76 487.76,367.76 486.69,367.76 ' style='stroke-width: 0.38; stroke: #EF7C51; fill: #EF7C51;' />
<polygon points='488.83,353.73 489.90,352.61 489.90,367.76 488.83,367.76 ' style='stroke-width: 0.38; stroke: #EF7D50; fill: #EF7D50;' />
<polygon points='489.90,352.61 490.97,351.43 490.97,367.76 489.90,367.76 ' style='stroke-width: 0.38; stroke: #EF7E50; fill: #EF7E50;' />
<polygon points='490.97,351.43 492.03,350.22 493.10,348.97 493.10,367.76 492.03,367.76 490.97,367.76 ' style='stroke-width: 0.38; stroke: #F07F4F; fill: #F07F4F;' />
<polygon points='493.10,348.97 494.17,347.67 495.24,346.33 495.24,367.76 494.17,367.76 493.10,367.76 ' style='stroke-width: 0.38; stroke: #F0804E; fill: #F0804E;' />
<polygon points='495.24,346.33 496.30,344.96 497.37,343.55 497.37,367.76 496.30,367.76 495.24,367.76 ' style='stroke-width: 0.38; stroke: #F1814D; fill: #F1814D;' />
<polygon points='497.37,343.55 498.44,342.12 498.44,367.76 497.37,367.76 ' style='stroke-width: 0.38; stroke: #F1824C; fill: #F1824C;' />
<polygon points='498.44,342.12 499.51,340.65 499.51,367.76 498.44,367.76 ' style='stroke-width: 0.38; stroke: #F1834C; fill: #F1834C;' />
<polygon points='499.51,340.65 500.57,339.15 501.64,337.63 501.64,367.76 500.57,367.76 499.51,367.76 ' style='stroke-width: 0.38; stroke: #F2844B; fill: #F2844B;' />
<polygon points='501.64,337.63 502.71,336.08 503.78,334.51 503.78,367.76 502.71,367.76 501.64,367.76 ' style='stroke-width: 0.38; stroke: #F3854B; fill: #F3854B;' />
<polygon points='503.78,334.51 504.84,332.92 504.84,367.76 503.78,367.76 ' style='stroke-width: 0.38; stroke: #F3864A; fill: #F3864A;' />
<polygon points='504.84,332.92 505.91,331.31 505.91,367.76 504.84,367.76 ' style='stroke-width: 0.38; stroke: #F3874A; fill: #F3874A;' />
<polygon points='505.91,331.31 506.98,329.67 508.05,328.02 508.05,367.76 506.98,367.76 505.91,367.76 ' style='stroke-width: 0.38; stroke: #F48849; fill: #F48849;' />
<polygon points='508.05,328.02 509.11,326.34 510.18,324.65 510.18,367.76 509.11,367.76 508.05,367.76 ' style='stroke-width: 0.38; stroke: #F48948; fill: #F48948;' />
<polygon points='510.18,324.65 511.25,322.94 511.25,367.76 510.18,367.76 ' style='stroke-width: 0.38; stroke: #F58A47; fill: #F58A47;' />
<polygon points='511.25,322.94 512.32,321.21 512.32,367.76 511.25,367.76 ' style='stroke-width: 0.38; stroke: #F58B47; fill: #F58B47;' />
<polygon points='512.32,321.21 513.38,319.47 514.45,317.71 514.45,367.76 513.38,367.76 512.32,367.76 ' style='stroke-width: 0.38; stroke: #F58C46; fill: #F58C46;' />
<polygon points='514.45,317.71 515.52,315.94 516.59,314.15 516.59,367.76 515.52,367.76 514.45,367.76 ' style='stroke-width: 0.38; stroke: #F68D45; fill: #F68D45;' />
<polygon points='516.59,314.15 517.65,312.34 517.65,367.76 516.59,367.76 ' style='stroke-width: 0.38; stroke: #F68E44; fill: #F68E44;' />
<polygon points='517.65,312.34 518.72,310.53 518.72,367.76 517.65,367.76 ' style='stroke-width: 0.38; stroke: #F68F44; fill: #F68F44;' />
<polygon points='518.72,310.53 519.79,308.71 520.86,306.88 520.86,367.76 519.79,367.76 518.72,367.76 ' style='stroke-width: 0.38; stroke: #F79044; fill: #F79044;' />
<polygon points='520.86,306.88 521.92,305.05 522.99,303.22 522.99,367.76 521.92,367.76 520.86,367.76 ' style='stroke-width: 0.38; stroke: #F79143; fill: #F79143;' />
<polygon points='522.99,303.22 524.06,301.40 524.06,367.76 522.99,367.76 ' style='stroke-width: 0.38; stroke: #F79242; fill: #F79242;' />
<polygon points='524.06,301.40 525.13,299.59 525.13,367.76 524.06,367.76 ' style='stroke-width: 0.38; stroke: #F79342; fill: #F79342;' />
<polygon points='525.13,299.59 526.19,297.79 527.26,296.02 527.26,367.76 526.19,367.76 525.13,367.76 ' style='stroke-width: 0.38; stroke: #F89441; fill: #F89441;' />
<polygon points='527.26,296.02 528.33,294.27 529.40,292.56 529.40,367.76 528.33,367.76 527.26,367.76 ' style='stroke-width: 0.38; stroke: #F89540; fill: #F89540;' />
<polygon points='529.40,292.56 530.46,290.89 530.46,367.76 529.40,367.76 ' style='stroke-width: 0.38; stroke: #F9963F; fill: #F9963F;' />
<polygon points='530.46,290.89 531.53,289.26 531.53,367.76 530.46,367.76 ' style='stroke-width: 0.38; stroke: #F9973F; fill: #F9973F;' />
<polygon points='531.53,289.26 532.60,287.69 533.67,286.18 533.67,367.76 532.60,367.76 531.53,367.76 ' style='stroke-width: 0.38; stroke: #F9983E; fill: #F9983E;' />
<polygon points='533.67,286.18 534.73,284.74 534.73,367.76 533.67,367.76 ' style='stroke-width: 0.38; stroke: #F9993E; fill: #F9993E;' />
<polygon points='534.73,284.74 535.80,283.37 535.80,367.76 534.73,367.76 ' style='stroke-width: 0.38; stroke: #F99A3E; fill: #F99A3E;' />
<polygon points='535.80,283.37 536.87,282.07 537.94,280.85 537.94,367.76 536.87,367.76 535.80,367.76 ' style='stroke-width: 0.38; stroke: #FA9B3D; fill: #FA9B3D;' />
<polygon points='537.94,280.85 539.00,279.74 540.07,278.71 540.07,367.76 539.00,367.76 537.94,367.76 ' style='stroke-width: 0.38; stroke: #FA9C3C; fill: #FA9C3C;' />
<polygon points='540.07,278.71 541.14,277.77 541.14,367.76 540.07,367.76 ' style='stroke-width: 0.38; stroke: #FA9D3B; fill: #FA9D3B;' />
<polygon points='541.14,277.77 542.21,276.92 542.21,367.76 541.14,367.76 ' style='stroke-width: 0.38; stroke: #FA9E3B; fill: #FA9E3B;' />
<polygon points='542.21,276.92 543.27,276.17 544.34,275.53 544.34,367.76 543.27,367.76 542.21,367.76 ' style='stroke-width: 0.38; stroke: #FB9F3A; fill: #FB9F3A;' />
<polygon points='544.34,275.53 545.41,274.99 545.41,367.76 544.34,367.76 ' style='stroke-width: 0.38; stroke: #FBA039; fill: #FBA039;' />
<polygon points='545.41,274.99 546.48,274.54 546.48,367.76 545.41,367.76 ' style='stroke-width: 0.38; stroke: #FBA139; fill: #FBA139;' />
<polygon points='546.48,274.54 547.54,274.17 548.61,273.89 548.61,367.76 547.54,367.76 546.48,367.76 ' style='stroke-width: 0.38; stroke: #FBA238; fill: #FBA238;' />
<polygon points='548.61,273.89 549.68,273.72 550.75,273.62 550.75,367.76 549.68,367.76 548.61,367.76 ' style='stroke-width: 0.38; stroke: #FCA338; fill: #FCA338;' />
<polygon points='550.75,273.62 551.81,273.60 551.81,367.76 550.75,367.76 ' style='stroke-width: 0.38; stroke: #FCA437; fill: #FCA437;' />
<polygon points='551.81,273.60 552.88,273.66 552.88,367.76 551.81,367.76 ' style='stroke-width: 0.38; stroke: #FCA537; fill: #FCA537;' />
<polygon points='552.88,273.66 553.95,273.78 555.02,273.98 555.02,367.76 553.95,367.76 552.88,367.76 ' style='stroke-width: 0.38; stroke: #FCA636; fill: #FCA636;' />
<polygon points='555.02,273.98 556.08,274.25 556.08,367.76 555.02,367.76 ' style='stroke-width: 0.38; stroke: #FCA735; fill: #FCA735;' />
<polygon points='556.08,274.25 557.15,274.58 557.15,367.76 556.08,367.76 ' style='stroke-width: 0.38; stroke: #FCA835; fill: #FCA835;' />
<polygon points='557.15,274.58 558.22,274.96 559.29,275.39 559.29,367.76 558.22,367.76 557.15,367.76 ' style='stroke-width: 0.38; stroke: #FCA934; fill: #FCA934;' />
<polygon points='559.29,275.39 560.35,275.89 560.35,367.76 559.29,367.76 ' style='stroke-width: 0.38; stroke: #FDAA33; fill: #FDAA33;' />
<polygon points='560.35,275.89 561.42,276.45 561.42,367.76 560.35,367.76 ' style='stroke-width: 0.38; stroke: #FDAB33; fill: #FDAB33;' />
<polygon points='561.42,276.45 562.49,277.06 563.56,277.73 563.56,367.76 562.49,367.76 561.42,367.76 ' style='stroke-width: 0.38; stroke: #FDAC33; fill: #FDAC33;' />
<polygon points='563.56,277.73 564.62,278.45 564.62,367.76 563.56,367.76 ' style='stroke-width: 0.38; stroke: #FDAD32; fill: #FDAD32;' />
<polygon points='564.62,278.45 565.69,279.23 565.69,367.76 564.62,367.76 ' style='stroke-width: 0.38; stroke: #FDAE32; fill: #FDAE32;' />
<polygon points='565.69,279.23 566.76,280.09 567.83,281.00 567.83,367.76 566.76,367.76 565.69,367.76 ' style='stroke-width: 0.38; stroke: #FDAF31; fill: #FDAF31;' />
<polygon points='567.83,281.00 568.89,281.99 568.89,367.76 567.83,367.76 ' style='stroke-width: 0.38; stroke: #FDB030; fill: #FDB030;' />
<polygon points='568.89,281.99 569.96,283.04 569.96,367.76 568.89,367.76 ' style='stroke-width: 0.38; stroke: #FDB130; fill: #FDB130;' />
<polygon points='569.96,283.04 571.03,284.17 572.10,285.40 572.10,367.76 571.03,367.76 569.96,367.76 ' style='stroke-width: 0.38; stroke: #FDB22F; fill: #FDB22F;' />
<polygon points='572.10,285.40 573.16,286.70 573.16,367.76 572.10,367.76 ' style='stroke-width: 0.38; stroke: #FDB32F; fill: #FDB32F;' />
<polygon points='573.16,286.70 574.23,288.08 574.23,367.76 573.16,367.76 ' style='stroke-width: 0.38; stroke: #FDB42F; fill: #FDB42F;' />
<polygon points='574.23,288.08 575.30,289.54 576.37,291.10 576.37,367.76 575.30,367.76 574.23,367.76 ' style='stroke-width: 0.38; stroke: #FDB52E; fill: #FDB52E;' />
<polygon points='576.37,291.10 577.43,292.76 577.43,367.76 576.37,367.76 ' style='stroke-width: 0.38; stroke: #FEB62D; fill: #FEB62D;' />
<polygon points='577.43,292.76 578.50,294.50 578.50,367.76 577.43,367.76 ' style='stroke-width: 0.38; stroke: #FEB72D; fill: #FEB72D;' />
<polygon points='578.50,294.50 579.57,296.32 580.64,298.22 580.64,367.76 579.57,367.76 578.50,367.76 ' style='stroke-width: 0.38; stroke: #FEB82C; fill: #FEB82C;' />
<polygon points='580.64,298.22 581.70,300.20 581.70,367.76 580.64,367.76 ' style='stroke-width: 0.38; stroke: #FEB92C; fill: #FEB92C;' />
<polygon points='581.70,300.20 582.77,302.27 582.77,367.76 581.70,367.76 ' style='stroke-width: 0.38; stroke: #FEBA2C; fill: #FEBA2C;' />
<polygon points='582.77,302.27 583.84,304.40 584.91,306.60 584.91,367.76 583.84,367.76 582.77,367.76 ' style='stroke-width: 0.38; stroke: #FEBB2B; fill: #FEBB2B;' />
<polygon points='584.91,306.60 585.97,308.84 585.97,367.76 584.91,367.76 ' style='stroke-width: 0.38; stroke: #FEBC2A; fill: #FEBC2A;' />
<polygon points='585.97,308.84 587.04,311.13 587.04,367.76 585.97,367.76 ' style='stroke-width: 0.38; stroke: #FEBD2A; fill: #FEBD2A;' />
<polygon points='587.04,311.13 588.11,313.47 589.18,315.83 589.18,367.76 588.11,367.76 587.04,367.76 ' style='stroke-width: 0.38; stroke: #FEBE2A; fill: #FEBE2A;' />
<polygon points='589.18,315.83 590.25,318.21 590.25,367.76 589.18,367.76 ' style='stroke-width: 0.38; stroke: #FEBF29; fill: #FEBF29;' />
<polygon points='590.25,318.21 591.31,320.60 591.31,367.76 590.25,367.76 ' style='stroke-width: 0.38; stroke: #FEC029; fill: #FEC029;' />
<polygon points='591.31,320.60 592.38,322.99 592.38,367.76 591.31,367.76 ' style='stroke-width: 0.38; stroke: #FDC129; fill: #FDC129;' />
<polygon points='592.38,322.99 593.45,325.37 593.45,367.76 592.38,367.76 ' style='stroke-width: 0.38; stroke: #FDC229; fill: #FDC229;' />
<polygon points='593.45,325.37 594.52,327.72 595.58,330.05 595.58,367.76 594.52,367.76 593.45,367.76 ' style='stroke-width: 0.38; stroke: #FDC328; fill: #FDC328;' />
<polygon points='595.58,330.05 596.65,332.34 596.65,367.76 595.58,367.76 ' style='stroke-width: 0.38; stroke: #FDC427; fill: #FDC427;' />
<polygon points='596.65,332.34 597.72,334.58 597.72,367.76 596.65,367.76 ' style='stroke-width: 0.38; stroke: #FDC527; fill: #FDC527;' />
<polygon points='597.72,334.58 598.79,336.76 599.85,338.88 599.85,367.76 598.79,367.76 597.72,367.76 ' style='stroke-width: 0.38; stroke: #FDC627; fill: #FDC627;' />
<polygon points='599.85,338.88 600.92,340.93 600.92,367.76 599.85,367.76 ' style='stroke-width: 0.38; stroke: #FDC727; fill: #FDC727;' />
<polygon points='600.92,340.93 601.99,342.91 601.99,367.76 600.92,367.76 ' style='stroke-width: 0.38; stroke: #FDC827; fill: #FDC827;' />
<polygon points='601.99,342.91 603.06,344.82 603.06,367.76 601.99,367.76 ' style='stroke-width: 0.38; stroke: #FDC926; fill: #FDC926;' />
<polygon points='603.06,344.82 604.12,346.63 604.12,367.76 603.06,367.76 ' style='stroke-width: 0.38; stroke: #FDCA26; fill: #FDCA26;' />
<polygon points='604.12,346.63 605.19,348.35 606.26,349.99 606.26,367.76 605.19,367.76 604.12,367.76 ' style='stroke-width: 0.38; stroke: #FDCB26; fill: #FDCB26;' />
<polygon points='606.26,349.99 607.33,351.54 607.33,367.76 606.26,367.76 ' style='stroke-width: 0.38; stroke: #FCCC25; fill: #FCCC25;' />
<polygon points='607.33,351.54 608.39,353.01 608.39,367.76 607.33,367.76 ' style='stroke-width: 0.38; stroke: #FCCD25; fill: #FCCD25;' />
<polygon points='608.39,353.01 609.46,354.37 610.53,355.64 610.53,367.76 609.46,367.76 608.39,367.76 ' style='stroke-width: 0.38; stroke: #FCCE25; fill: #FCCE25;' />
<polygon points='610.53,355.64 611.60,356.83 611.60,367.76 610.53,367.76 ' style='stroke-width: 0.38; stroke: #FCCF25; fill: #FCCF25;' />
<polygon points='611.60,356.83 612.66,357.94 612.66,367.76 611.60,367.76 ' style='stroke-width: 0.38; stroke: #FCD025; fill: #FCD025;' />
<polygon points='612.66,357.94 613.73,358.97 613.73,367.76 612.66,367.76 ' style='stroke-width: 0.38; stroke: #FCD125; fill: #FCD125;' />
<polygon points='613.73,358.97 614.80,359.91 614.80,367.76 613.73,367.76 ' style='stroke-width: 0.38; stroke: #FCD225; fill: #FCD225;' />
<polygon points='614.80,359.91 615.87,360.76 616.93,361.54 616.93,367.76 615.87,367.76 614.80,367.76 ' style='stroke-width: 0.38; stroke: #FBD324; fill: #FBD324;' />
<polygon points='616.93,361.54 618.00,362.26 618.00,367.76 616.93,367.76 ' style='stroke-width: 0.38; stroke: #FBD424; fill: #FBD424;' />
<polygon points='618.00,362.26 619.07,362.91 619.07,367.76 618.00,367.76 ' style='stroke-width: 0.38; stroke: #FBD524; fill: #FBD524;' />
<polygon points='619.07,362.91 620.14,363.50 620.14,367.76 619.07,367.76 ' style='stroke-width: 0.38; stroke: #FBD624; fill: #FBD624;' />
<polygon points='620.14,363.50 621.20,364.02 621.20,367.76 620.14,367.76 ' style='stroke-width: 0.38; stroke: #FBD724; fill: #FBD724;' />
<polygon points='621.20,364.02 622.27,364.50 623.34,364.92 623.34,367.76 622.27,367.76 621.20,367.76 ' style='stroke-width: 0.38; stroke: #FAD824; fill: #FAD824;' />
<polygon points='623.34,364.92 624.41,365.30 624.41,367.76 623.34,367.76 ' style='stroke-width: 0.38; stroke: #FAD924; fill: #FAD924;' />
<polygon points='624.41,365.30 625.47,365.64 625.47,367.76 624.41,367.76 ' style='stroke-width: 0.38; stroke: #FADA24; fill: #FADA24;' />
<polygon points='625.47,365.64 626.54,365.93 626.54,367.76 625.47,367.76 ' style='stroke-width: 0.38; stroke: #F9DB24; fill: #F9DB24;' />
<polygon points='626.54,365.93 627.61,366.18 627.61,367.76 626.54,367.76 ' style='stroke-width: 0.38; stroke: #F9DC24; fill: #F9DC24;' />
<polygon points='627.61,366.18 628.68,366.41 629.74,366.61 629.74,367.76 628.68,367.76 627.61,367.76 ' style='stroke-width: 0.38; stroke: #F9DD25; fill: #F9DD25;' />
<polygon points='629.74,366.61 629.74,367.76 ' style='stroke-width: 0.38; stroke: #F8DE25; fill: #F8DE25;' />
<polyline points='465.34,366.59 466.41,366.41 467.48,366.20 468.55,365.95 469.61,365.69 470.68,365.39 471.75,365.06 472.82,364.69 473.88,364.28 474.95,363.83 476.02,363.35 477.09,362.82 478.15,362.24 479.22,361.61 480.29,360.93 481.36,360.21 482.42,359.44 483.49,358.62 484.56,357.74 485.63,356.81 486.69,355.83 487.76,354.81 488.83,353.73 489.90,352.61 490.97,351.43 492.03,350.22 493.10,348.97 494.17,347.67 495.24,346.33 496.30,344.96 497.37,343.55 498.44,342.12 499.51,340.65 500.57,339.15 501.64,337.63 502.71,336.08 503.78,334.51 504.84,332.92 505.91,331.31 506.98,329.67 508.05,328.02 509.11,326.34 510.18,324.65 511.25,322.94 512.32,321.21 513.38,319.47 514.45,317.71 515.52,315.94 516.59,314.15 517.65,312.34 518.72,310.53 519.79,308.71 520.86,306.88 521.92,305.05 522.99,303.22 524.06,301.40 525.13,299.59 526.19,297.79 527.26,296.02 528.33,294.27 529.40,292.56 530.46,290.89 531.53,289.26 532.60,287.69 533.67,286.18 534.73,284.74 535.80,283.37 536.87,282.07 537.94,280.85 539.00,279.74 540.07,278.71 541.14,277.77 542.21,276.92 543.27,276.17 544.34,275.53 545.41,274.99 546.48,274.54 547.54,274.17 548.61,273.89 549.68,273.72 550.75,273.62 551.81,273.60 552.88,273.66 553.95,273.78 555.02,273.98 556.08,274.25 557.15,274.58 558.22,274.96 559.29,275.39 560.35,275.89 561.42,276.45 562.49,277.06 563.56,277.73 564.62,278.45 565.69,279.23 566.76,280.09 567.83,281.00 568.89,281.99 569.96,283.04 571.03,284.17 572.10,285.40 573.16,286.70 574.23,288.08 575.30,289.54 576.37,291.10 577.43,292.76 578.50,294.50 579.57,296.32 580.64,298.22 581.70,300.20 582.77,302.27 583.84,304.40 584.91,306.60 585.97,308.84 587.04,311.13 588.11,313.47 589.18,315.83 590.25,318.21 591.31,320.60 592.38,322.99 593.45,325.37 594.52,327.72 595.58,330.05 596.65,332.34 597.72,334.58 598.79,336.76 599.85,338.88 600.92,340.93 601.99,342.91 603.06,344.82 604.12,346.63 605.19,348.35 606.26,349.99 607.33,351.54 608.39,353.01 609.46,354.37 610.53,355.64 611.60,356.83 612.66,357.94 613.73,358.97 614.80,359.91 615.87,360.76 616.93,361.54 618.00,362.26 619.07,362.91 620.14,363.50 621.20,364.02 622.27,364.50 623.34,364.92 624.41,365.30 625.47,365.64 626.54,365.93 627.61,366.18 628.68,366.41 629.74,366.61 ' style='stroke-width: 1.07;' />
<polygon points='415.17,400.00 416.24,399.80 416.24,401.16 415.17,401.16 ' style='stroke-width: 0.38; stroke: #D5546E; fill: #D5546E;' />
<polygon points='416.24,399.80 417.31,399.58 418.37,399.33 418.37,401.16 417.31,401.16 416.24,401.16 ' style='stroke-width: 0.38; stroke: #D6556D; fill: #D6556D;' />
<polygon points='418.37,399.33 419.44,399.04 420.51,398.72 420.51,401.16 419.44,401.16 418.37,401.16 ' style='stroke-width: 0.38; stroke: #D7566C; fill: #D7566C;' />
<polygon points='420.51,398.72 421.58,398.36 422.64,397.96 422.64,401.16 421.58,401.16 420.51,401.16 ' style='stroke-width: 0.38; stroke: #D8576B; fill: #D8576B;' />
<polygon points='422.64,397.96 423.71,397.51 424.78,397.01 424.78,401.16 423.71,401.16 422.64,401.16 ' style='stroke-width: 0.38; stroke: #D9586A; fill: #D9586A;' />
<polygon points='424.78,397.01 425.85,396.47 425.85,401.16 424.78,401.16 ' style='stroke-width: 0.38; stroke: #DA596A; fill: #DA596A;' />
<polygon points='425.85,396.47 426.91,395.88 426.91,401.16 425.85,401.16 ' style='stroke-width: 0.38; stroke: #DA5A6A; fill: #DA5A6A;' />
<polygon points='426.91,395.88 427.98,395.23 429.05,394.52 429.05,401.16 427.98,401.16 426.91,401.16 ' style='stroke-width: 0.38; stroke: #DA5B69; fill: #DA5B69;' />
<polygon points='429.05,394.52 430.12,393.75 431.18,392.93 431.18,401.16 430.12,401.16 429.05,401.16 ' style='stroke-width: 0.38; stroke: #DB5C68; fill: #DB5C68;' />
<polygon points='431.18,392.93 432.25,392.04 433.32,391.11 433.32,401.16 432.25,401.16 431.18,401.16 ' style='stroke-width: 0.38; stroke: #DC5D67; fill: #DC5D67;' />
<polygon points='433.32,391.11 434.39,390.10 435.45,389.04 435.45,401.16 434.39,401.16 433.32,401.16 ' style='stroke-width: 0.38; stroke: #DD5E66; fill: #DD5E66;' />
<polygon points='435.45,389.04 436.52,387.92 437.59,386.74 437.59,401.16 436.52,401.16 435.45,401.16 ' style='stroke-width: 0.38; stroke: #DE5F65; fill: #DE5F65;' />
<polygon points='437.59,386.74 438.66,385.53 438.66,401.16 437.59,401.16 ' style='stroke-width: 0.38; stroke: #DE6064; fill: #DE6064;' />
<polygon points='438.66,385.53 439.72,384.26 439.72,401.16 438.66,401.16 ' style='stroke-width: 0.38; stroke: #DE6164; fill: #DE6164;' />
<polygon points='439.72,384.26 440.79,382.94 441.86,381.59 441.86,401.16 440.79,401.16 439.72,401.16 ' style='stroke-width: 0.38; stroke: #DF6263; fill: #DF6263;' />
<polygon points='441.86,381.59 442.93,380.21 443.99,378.81 443.99,401.16 442.93,401.16 441.86,401.16 ' style='stroke-width: 0.38; stroke: #E06363; fill: #E06363;' />
<polygon points='443.99,378.81 445.06,377.39 446.13,375.95 446.13,401.16 445.06,401.16 443.99,401.16 ' style='stroke-width: 0.38; stroke: #E16462; fill: #E16462;' />
<polygon points='446.13,375.95 447.20,374.52 448.26,373.09 448.26,401.16 447.20,401.16 446.13,401.16 ' style='stroke-width: 0.38; stroke: #E26561; fill: #E26561;' />
<polygon points='448.26,373.09 449.33,371.68 450.40,370.28 450.40,401.16 449.33,401.16 448.26,401.16 ' style='stroke-width: 0.38; stroke: #E26660; fill: #E26660;' />
<polygon points='450.40,370.28 451.47,368.93 451.47,401.16 450.40,401.16 ' style='stroke-width: 0.38; stroke: #E3675F; fill: #E3675F;' />
<polygon points='451.47,368.93 452.53,367.61 452.53,401.16 451.47,401.16 ' style='stroke-width: 0.38; stroke: #E3685F; fill: #E3685F;' />
<polygon points='452.53,367.61 453.60,366.34 454.67,365.11 454.67,401.16 453.60,401.16 452.53,401.16 ' style='stroke-width: 0.38; stroke: #E4695E; fill: #E4695E;' />
<polygon points='454.67,365.11 455.74,363.95 456.80,362.86 456.80,401.16 455.74,401.16 454.67,401.16 ' style='stroke-width: 0.38; stroke: #E56A5D; fill: #E56A5D;' />
<polygon points='456.80,362.86 457.87,361.84 458.94,360.90 458.94,401.16 457.87,401.16 456.80,401.16 ' style='stroke-width: 0.38; stroke: #E56B5D; fill: #E56B5D;' />
<polygon points='458.94,360.90 460.01,360.02 461.07,359.22 461.07,401.16 460.01,401.16 458.94,401.16 ' style='stroke-width: 0.38; stroke: #E66C5C; fill: #E66C5C;' />
<polygon points='461.07,359.22 462.14,358.52 462.14,401.16 461.07,401.16 ' style='stroke-width: 0.38; stroke: #E76D5B; fill: #E76D5B;' />
<polygon points='462.14,358.52 463.21,357.90 463.21,401.16 462.14,401.16 ' style='stroke-width: 0.38; stroke: #E76E5B; fill: #E76E5B;' />
<polygon points='463.21,357.90 464.28,357.35 465.34,356.87 465.34,401.16 464.28,401.16 463.21,401.16 ' style='stroke-width: 0.38; stroke: #E76F5A; fill: #E76F5A;' />
<polygon points='465.34,356.87 466.41,356.46 467.48,356.13 467.48,401.16 466.41,401.16 465.34,401.16 ' style='stroke-width: 0.38; stroke: #E87059; fill: #E87059;' />
<polygon points='467.48,356.13 468.55,355.86 469.61,355.64 469.61,401.16 468.55,401.16 467.48,401.16 ' style='stroke-width: 0.38; stroke: #E97158; fill: #E97158;' />
<polygon points='469.61,355.64 470.68,355.47 471.75,355.33 471.75,401.16 470.68,401.16 469.61,401.16 ' style='stroke-width: 0.38; stroke: #E97257; fill: #E97257;' />
<polygon points='471.75,355.33 472.82,355.23 472.82,401.16 471.75,401.16 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,355.23 473.88,355.14 473.88,401.16 472.82,401.16 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,355.14 474.95,355.07 476.02,355.00 476.02,401.16 474.95,401.16 473.88,401.16 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,355.00 477.09,354.93 478.15,354.84 478.15,401.16 477.09,401.16 476.02,401.16 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,354.84 479.22,354.72 480.29,354.57 480.29,401.16 479.22,401.16 478.15,401.16 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,354.57 481.36,354.38 481.36,401.16 480.29,401.16 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,354.38 482.42,354.15 482.42,401.16 481.36,401.16 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,354.15 483.49,353.87 484.56,353.52 484.56,401.16 483.49,401.16 482.42,401.16 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,353.52 485.63,353.10 486.69,352.63 486.69,401.16 485.63,401.16 484.56,401.16 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polygon points='486.69,352.63 487.76,352.09 488.83,351.47 488.83,401.16 487.76,401.16 486.69,401.16 ' style='stroke-width: 0.38; stroke: #EF7C51; fill: #EF7C51;' />
<polygon points='488.83,351.47 489.90,350.78 489.90,401.16 488.83,401.16 ' style='stroke-width: 0.38; stroke: #EF7D50; fill: #EF7D50;' />
<polygon points='489.90,350.78 490.97,350.01 490.97,401.16 489.90,401.16 ' style='stroke-width: 0.38; stroke: #EF7E50; fill: #EF7E50;' />
<polygon points='490.97,350.01 492.03,349.18 493.10,348.28 493.10,401.16 492.03,401.16 490.97,401.16 ' style='stroke-width: 0.38; stroke: #F07F4F; fill: #F07F4F;' />
<polygon points='493.10,348.28 494.17,347.31 495.24,346.26 495.24,401.16 494.17,401.16 493.10,401.16 ' style='stroke-width: 0.38; stroke: #F0804E; fill: #F0804E;' />
<polygon points='495.24,346.26 496.30,345.16 497.37,344.01 497.37,401.16 496.30,401.16 495.24,401.16 ' style='stroke-width: 0.38; stroke: #F1814D; fill: #F1814D;' />
<polygon points='497.37,344.01 498.44,342.81 498.44,401.16 497.37,401.16 ' style='stroke-width: 0.38; stroke: #F1824C; fill: #F1824C;' />
<polygon points='498.44,342.81 499.51,341.56 499.51,401.16 498.44,401.16 ' style='stroke-width: 0.38; stroke: #F1834C; fill: #F1834C;' />
<polygon points='499.51,341.56 500.57,340.27 501.64,338.95 501.64,401.16 500.57,401.16 499.51,401.16 ' style='stroke-width: 0.38; stroke: #F2844B; fill: #F2844B;' />
<polygon points='501.64,338.95 502.71,337.61 503.78,336.26 503.78,401.16 502.71,401.16 501.64,401.16 ' style='stroke-width: 0.38; stroke: #F3854B; fill: #F3854B;' />
<polygon points='503.78,336.26 504.84,334.89 504.84,401.16 503.78,401.16 ' style='stroke-width: 0.38; stroke: #F3864A; fill: #F3864A;' />
<polygon points='504.84,334.89 505.91,333.53 505.91,401.16 504.84,401.16 ' style='stroke-width: 0.38; stroke: #F3874A; fill: #F3874A;' />
<polygon points='505.91,333.53 506.98,332.18 508.05,330.86 508.05,401.16 506.98,401.16 505.91,401.16 ' style='stroke-width: 0.38; stroke: #F48849; fill: #F48849;' />
<polygon points='508.05,330.86 509.11,329.56 510.18,328.30 510.18,401.16 509.11,401.16 508.05,401.16 ' style='stroke-width: 0.38; stroke: #F48948; fill: #F48948;' />
<polygon points='510.18,328.30 511.25,327.10 511.25,401.16 510.18,401.16 ' style='stroke-width: 0.38; stroke: #F58A47; fill: #F58A47;' />
<polygon points='511.25,327.10 512.32,325.96 512.32,401.16 511.25,401.16 ' style='stroke-width: 0.38; stroke: #F58B47; fill: #F58B47;' />
<polygon points='512.32,325.96 513.38,324.89 514.45,323.90 514.45,401.16 513.38,401.16 512.32,401.16 ' style='stroke-width: 0.38; stroke: #F58C46; fill: #F58C46;' />
<polygon points='514.45,323.90 515.52,322.99 516.59,322.19 516.59,401.16 515.52,401.16 514.45,401.16 ' style='stroke-width: 0.38; stroke: #F68D45; fill: #F68D45;' />
<polygon points='516.59,322.19 517.65,321.50 517.65,401.16 516.59,401.16 ' style='stroke-width: 0.38; stroke: #F68E44; fill: #F68E44;' />
<polygon points='517.65,321.50 518.72,320.92 518.72,401.16 517.65,401.16 ' style='stroke-width: 0.38; stroke: #F68F44; fill: #F68F44;' />
<polygon points='518.72,320.92 519.79,320.46 520.86,320.11 520.86,401.16 519.79,401.16 518.72,401.16 ' style='stroke-width: 0.38; stroke: #F79044; fill: #F79044;' />
<polygon points='520.86,320.11 521.92,319.90 522.99,319.84 522.99,401.16 521.92,401.16 520.86,401.16 ' style='stroke-width: 0.38; stroke: #F79143; fill: #F79143;' />
<polygon points='522.99,319.84 524.06,319.90 524.06,401.16 522.99,401.16 ' style='stroke-width: 0.38; stroke: #F79242; fill: #F79242;' />
<polygon points='524.06,319.90 525.13,320.09 525.13,401.16 524.06,401.16 ' style='stroke-width: 0.38; stroke: #F79342; fill: #F79342;' />
<polygon points='525.13,320.09 526.19,320.40 527.26,320.86 527.26,401.16 526.19,401.16 525.13,401.16 ' style='stroke-width: 0.38; stroke: #F89441; fill: #F89441;' />
<polygon points='527.26,320.86 528.33,321.45 529.40,322.16 529.40,401.16 528.33,401.16 527.26,401.16 ' style='stroke-width: 0.38; stroke: #F89540; fill: #F89540;' />
<polygon points='529.40,322.16 530.46,322.98 530.46,401.16 529.40,401.16 ' style='stroke-width: 0.38; stroke: #F9963F; fill: #F9963F;' />
<polygon points='530.46,322.98 531.53,323.91 531.53,401.16 530.46,401.16 ' style='stroke-width: 0.38; stroke: #F9973F; fill: #F9973F;' />
<polygon points='531.53,323.91 532.60,324.94 533.67,326.08 533.67,401.16 532.60,401.16 531.53,401.16 ' style='stroke-width: 0.38; stroke: #F9983E; fill: #F9983E;' />
<polygon points='533.67,326.08 534.73,327.30 534.73,401.16 533.67,401.16 ' style='stroke-width: 0.38; stroke: #F9993E; fill: #F9993E;' />
<polygon points='534.73,327.30 535.80,328.58 535.80,401.16 534.73,401.16 ' style='stroke-width: 0.38; stroke: #F99A3E; fill: #F99A3E;' />
<polygon points='535.80,328.58 536.87,329.93 537.94,331.33 537.94,401.16 536.87,401.16 535.80,401.16 ' style='stroke-width: 0.38; stroke: #FA9B3D; fill: #FA9B3D;' />
<polygon points='537.94,331.33 539.00,332.79 540.07,334.27 540.07,401.16 539.00,401.16 537.94,401.16 ' style='stroke-width: 0.38; stroke: #FA9C3C; fill: #FA9C3C;' />
<polygon points='540.07,334.27 541.14,335.77 541.14,401.16 540.07,401.16 ' style='stroke-width: 0.38; stroke: #FA9D3B; fill: #FA9D3B;' />
<polygon points='541.14,335.77 542.21,337.29 542.21,401.16 541.14,401.16 ' style='stroke-width: 0.38; stroke: #FA9E3B; fill: #FA9E3B;' />
<polygon points='542.21,337.29 543.27,338.82 544.34,340.34 544.34,401.16 543.27,401.16 542.21,401.16 ' style='stroke-width: 0.38; stroke: #FB9F3A; fill: #FB9F3A;' />
<polygon points='544.34,340.34 545.41,341.86 545.41,401.16 544.34,401.16 ' style='stroke-width: 0.38; stroke: #FBA039; fill: #FBA039;' />
<polygon points='545.41,341.86 546.48,343.36 546.48,401.16 545.41,401.16 ' style='stroke-width: 0.38; stroke: #FBA139; fill: #FBA139;' />
<polygon points='546.48,343.36 547.54,344.85 548.61,346.31 548.61,401.16 547.54,401.16 546.48,401.16 ' style='stroke-width: 0.38; stroke: #FBA238; fill: #FBA238;' />
<polygon points='548.61,346.31 549.68,347.74 550.75,349.14 550.75,401.16 549.68,401.16 548.61,401.16 ' style='stroke-width: 0.38; stroke: #FCA338; fill: #FCA338;' />
<polygon points='550.75,349.14 551.81,350.52 551.81,401.16 550.75,401.16 ' style='stroke-width: 0.38; stroke: #FCA437; fill: #FCA437;' />
<polygon points='551.81,350.52 552.88,351.87 552.88,401.16 551.81,401.16 ' style='stroke-width: 0.38; stroke: #FCA537; fill: #FCA537;' />
<polygon points='552.88,351.87 553.95,353.19 555.02,354.48 555.02,401.16 553.95,401.16 552.88,401.16 ' style='stroke-width: 0.38; stroke: #FCA636; fill: #FCA636;' />
<polygon points='555.02,354.48 556.08,355.74 556.08,401.16 555.02,401.16 ' style='stroke-width: 0.38; stroke: #FCA735; fill: #FCA735;' />
<polygon points='556.08,355.74 557.15,356.99 557.15,401.16 556.08,401.16 ' style='stroke-width: 0.38; stroke: #FCA835; fill: #FCA835;' />
<polygon points='557.15,356.99 558.22,358.21 559.29,359.41 559.29,401.16 558.22,401.16 557.15,401.16 ' style='stroke-width: 0.38; stroke: #FCA934; fill: #FCA934;' />
<polygon points='559.29,359.41 560.35,360.60 560.35,401.16 559.29,401.16 ' style='stroke-width: 0.38; stroke: #FDAA33; fill: #FDAA33;' />
<polygon points='560.35,360.60 561.42,361.78 561.42,401.16 560.35,401.16 ' style='stroke-width: 0.38; stroke: #FDAB33; fill: #FDAB33;' />
<polygon points='561.42,361.78 562.49,362.95 563.56,364.11 563.56,401.16 562.49,401.16 561.42,401.16 ' style='stroke-width: 0.38; stroke: #FDAC33; fill: #FDAC33;' />
<polygon points='563.56,364.11 564.62,365.27 564.62,401.16 563.56,401.16 ' style='stroke-width: 0.38; stroke: #FDAD32; fill: #FDAD32;' />
<polygon points='564.62,365.27 565.69,366.43 565.69,401.16 564.62,401.16 ' style='stroke-width: 0.38; stroke: #FDAE32; fill: #FDAE32;' />
<polygon points='565.69,366.43 566.76,367.59 567.83,368.75 567.83,401.16 566.76,401.16 565.69,401.16 ' style='stroke-width: 0.38; stroke: #FDAF31; fill: #FDAF31;' />
<polygon points='567.83,368.75 568.89,369.91 568.89,401.16 567.83,401.16 ' style='stroke-width: 0.38; stroke: #FDB030; fill: #FDB030;' />
<polygon points='568.89,369.91 569.96,371.08 569.96,401.16 568.89,401.16 ' style='stroke-width: 0.38; stroke: #FDB130; fill: #FDB130;' />
<polygon points='569.96,371.08 571.03,372.26 572.10,373.43 572.10,401.16 571.03,401.16 569.96,401.16 ' style='stroke-width: 0.38; stroke: #FDB22F; fill: #FDB22F;' />
<polygon points='572.10,373.43 573.16,374.61 573.16,401.16 572.10,401.16 ' style='stroke-width: 0.38; stroke: #FDB32F; fill: #FDB32F;' />
<polygon points='573.16,374.61 574.23,375.79 574.23,401.16 573.16,401.16 ' style='stroke-width: 0.38; stroke: #FDB42F; fill: #FDB42F;' />
<polygon points='574.23,375.79 575.30,376.97 576.37,378.14 576.37,401.16 575.30,401.16 574.23,401.16 ' style='stroke-width: 0.38; stroke: #FDB52E; fill: #FDB52E;' />
<polygon points='576.37,378.14 577.43,379.31 577.43,401.16 576.37,401.16 ' style='stroke-width: 0.38; stroke: #FEB62D; fill: #FEB62D;' />
<polygon points='577.43,379.31 578.50,380.47 578.50,401.16 577.43,401.16 ' style='stroke-width: 0.38; stroke: #FEB72D; fill: #FEB72D;' />
<polygon points='578.50,380.47 579.57,381.61 580.64,382.75 580.64,401.16 579.57,401.16 578.50,401.16 ' style='stroke-width: 0.38; stroke: #FEB82C; fill: #FEB82C;' />
<polygon points='580.64,382.75 581.70,383.86 581.70,401.16 580.64,401.16 ' style='stroke-width: 0.38; stroke: #FEB92C; fill: #FEB92C;' />
<polygon points='581.70,383.86 582.77,384.95 582.77,401.16 581.70,401.16 ' style='stroke-width: 0.38; stroke: #FEBA2C; fill: #FEBA2C;' />
<polygon points='582.77,384.95 583.84,386.01 584.91,387.04 584.91,401.16 583.84,401.16 582.77,401.16 ' style='stroke-width: 0.38; stroke: #FEBB2B; fill: #FEBB2B;' />
<polygon points='584.91,387.04 585.97,388.05 585.97,401.16 584.91,401.16 ' style='stroke-width: 0.38; stroke: #FEBC2A; fill: #FEBC2A;' />
<polygon points='585.97,388.05 587.04,389.02 587.04,401.16 585.97,401.16 ' style='stroke-width: 0.38; stroke: #FEBD2A; fill: #FEBD2A;' />
<polygon points='587.04,389.02 588.11,389.94 589.18,390.83 589.18,401.16 588.11,401.16 587.04,401.16 ' style='stroke-width: 0.38; stroke: #FEBE2A; fill: #FEBE2A;' />
<polygon points='589.18,390.83 590.25,391.68 590.25,401.16 589.18,401.16 ' style='stroke-width: 0.38; stroke: #FEBF29; fill: #FEBF29;' />
<polygon points='590.25,391.68 591.31,392.50 591.31,401.16 590.25,401.16 ' style='stroke-width: 0.38; stroke: #FEC029; fill: #FEC029;' />
<polygon points='591.31,392.50 592.38,393.27 592.38,401.16 591.31,401.16 ' style='stroke-width: 0.38; stroke: #FDC129; fill: #FDC129;' />
<polygon points='592.38,393.27 593.45,393.99 593.45,401.16 592.38,401.16 ' style='stroke-width: 0.38; stroke: #FDC229; fill: #FDC229;' />
<polygon points='593.45,393.99 594.52,394.66 595.58,395.29 595.58,401.16 594.52,401.16 593.45,401.16 ' style='stroke-width: 0.38; stroke: #FDC328; fill: #FDC328;' />
<polygon points='595.58,395.29 596.65,395.89 596.65,401.16 595.58,401.16 ' style='stroke-width: 0.38; stroke: #FDC427; fill: #FDC427;' />
<polygon points='596.65,395.89 597.72,396.44 597.72,401.16 596.65,401.16 ' style='stroke-width: 0.38; stroke: #FDC527; fill: #FDC527;' />
<polygon points='597.72,396.44 598.79,396.94 599.85,397.40 599.85,401.16 598.79,401.16 597.72,401.16 ' style='stroke-width: 0.38; stroke: #FDC627; fill: #FDC627;' />
<polygon points='599.85,397.40 600.92,397.83 600.92,401.16 599.85,401.16 ' style='stroke-width: 0.38; stroke: #FDC727; fill: #FDC727;' />
<polygon points='600.92,397.83 601.99,398.22 601.99,401.16 600.92,401.16 ' style='stroke-width: 0.38; stroke: #FDC827; fill: #FDC827;' />
<polygon points='601.99,398.22 603.06,398.57 603.06,401.16 601.99,401.16 ' style='stroke-width: 0.38; stroke: #FDC926; fill: #FDC926;' />
<polygon points='603.06,398.57 604.12,398.89 604.12,401.16 603.06,401.16 ' style='stroke-width: 0.38; stroke: #FDCA26; fill: #FDCA26;' />
<polygon points='604.12,398.89 605.19,399.17 606.26,399.43 606.26,401.16 605.19,401.16 604.12,401.16 ' style='stroke-width: 0.38; stroke: #FDCB26; fill: #FDCB26;' />
<polygon points='606.26,399.43 607.33,399.66 607.33,401.16 606.26,401.16 ' style='stroke-width: 0.38; stroke: #FCCC25; fill: #FCCC25;' />
<polygon points='607.33,399.66 608.39,399.87 608.39,401.16 607.33,401.16 ' style='stroke-width: 0.38; stroke: #FCCD25; fill: #FCCD25;' />
<polygon points='608.39,399.87 609.46,400.04 609.46,401.16 608.39,401.16 ' style='stroke-width: 0.38; stroke: #FCCE25; fill: #FCCE25;' />
<polyline points='415.17,400.00 416.24,399.80 417.31,399.58 418.37,399.33 419.44,399.04 420.51,398.72 421.58,398.36 422.64,397.96 423.71,397.51 424.78,397.01 425.85,396.47 426.91,395.88 427.98,395.23 429.05,394.52 430.12,393.75 431.18,392.93 432.25,392.04 433.32,391.11 434.39,390.10 435.45,389.04 436.52,387.92 437.59,386.74 438.66,385.53 439.72,384.26 440.79,382.94 441.86,381.59 442.93,380.21 443.99,378.81 445.06,377.39 446.13,375.95 447.20,374.52 448.26,373.09 449.33,371.68 450.40,370.28 451.47,368.93 452.53,367.61 453.60,366.34 454.67,365.11 455.74,363.95 456.80,362.86 457.87,361.84 458.94,360.90 460.01,360.02 461.07,359.22 462.14,358.52 463.21,357.90 464.28,357.35 465.34,356.87 466.41,356.46 467.48,356.13 468.55,355.86 469.61,355.64 470.68,355.47 471.75,355.33 472.82,355.23 473.88,355.14 474.95,355.07 476.02,355.00 477.09,354.93 478.15,354.84 479.22,354.72 480.29,354.57 481.36,354.38 482.42,354.15 483.49,353.87 484.56,353.52 485.63,353.10 486.69,352.63 487.76,352.09 488.83,351.47 489.90,350.78 490.97,350.01 492.03,349.18 493.10,348.28 494.17,347.31 495.24,346.26 496.30,345.16 497.37,344.01 498.44,342.81 499.51,341.56 500.57,340.27 501.64,338.95 502.71,337.61 503.78,336.26 504.84,334.89 505.91,333.53 506.98,332.18 508.05,330.86 509.11,329.56 510.18,328.30 511.25,327.10 512.32,325.96 513.38,324.89 514.45,323.90 515.52,322.99 516.59,322.19 517.65,321.50 518.72,320.92 519.79,320.46 520.86,320.11 521.92,319.90 522.99,319.84 524.06,319.90 525.13,320.09 526.19,320.40 527.26,320.86 528.33,321.45 529.40,322.16 530.46,322.98 531.53,323.91 532.60,324.94 533.67,326.08 534.73,327.30 535.80,328.58 536.87,329.93 537.94,331.33 539.00,332.79 540.07,334.27 541.14,335.77 542.21,337.29 543.27,338.82 544.34,340.34 545.41,341.86 546.48,343.36 547.54,344.85 548.61,346.31 549.68,347.74 550.75,349.14 551.81,350.52 552.88,351.87 553.95,353.19 555.02,354.48 556.08,355.74 557.15,356.99 558.22,358.21 559.29,359.41 560.35,360.60 561.42,361.78 562.49,362.95 563.56,364.11 564.62,365.27 565.69,366.43 566.76,367.59 567.83,368.75 568.89,369.91 569.96,371.08 571.03,372.26 572.10,373.43 573.16,374.61 574.23,375.79 575.30,376.97 576.37,378.14 577.43,379.31 578.50,380.47 579.57,381.61 580.64,382.75 581.70,383.86 582.77,384.95 583.84,386.01 584.91,387.04 585.97,388.05 587.04,389.02 588.11,389.94 589.18,390.83 590.25,391.68 591.31,392.50 592.38,393.27 593.45,393.99 594.52,394.66 595.58,395.29 596.65,395.89 597.72,396.44 598.79,396.94 599.85,397.40 600.92,397.83 601.99,398.22 603.06,398.57 604.12,398.89 605.19,399.17 606.26,399.43 607.33,399.66 608.39,399.87 609.46,400.04 ' style='stroke-width: 1.07;' />
<polygon points='346.85,433.52 347.92,433.39 347.92,434.56 346.85,434.56 ' style='stroke-width: 0.38; stroke: #B6308B; fill: #B6308B;' />
<polygon points='347.92,433.39 348.98,433.25 350.05,433.09 350.05,434.56 348.98,434.56 347.92,434.56 ' style='stroke-width: 0.38; stroke: #B7318A; fill: #B7318A;' />
<polygon points='350.05,433.09 351.12,432.92 351.12,434.56 350.05,434.56 ' style='stroke-width: 0.38; stroke: #B83289; fill: #B83289;' />
<polygon points='351.12,432.92 352.19,432.74 352.19,434.56 351.12,434.56 ' style='stroke-width: 0.38; stroke: #B93289; fill: #B93289;' />
<polygon points='352.19,432.74 353.25,432.55 354.32,432.34 354.32,434.56 353.25,434.56 352.19,434.56 ' style='stroke-width: 0.38; stroke: #BA3388; fill: #BA3388;' />
<polygon points='354.32,432.34 355.39,432.13 356.46,431.90 356.46,434.56 355.39,434.56 354.32,434.56 ' style='stroke-width: 0.38; stroke: #BB3488; fill: #BB3488;' />
<polygon points='356.46,431.90 357.52,431.66 357.52,434.56 356.46,434.56 ' style='stroke-width: 0.38; stroke: #BC3587; fill: #BC3587;' />
<polygon points='357.52,431.66 358.59,431.41 358.59,434.56 357.52,434.56 ' style='stroke-width: 0.38; stroke: #BC3687; fill: #BC3687;' />
<polygon points='358.59,431.41 359.66,431.15 360.73,430.88 360.73,434.56 359.66,434.56 358.59,434.56 ' style='stroke-width: 0.38; stroke: #BD3786; fill: #BD3786;' />
<polygon points='360.73,430.88 361.79,430.60 362.86,430.32 362.86,434.56 361.79,434.56 360.73,434.56 ' style='stroke-width: 0.38; stroke: #BE3885; fill: #BE3885;' />
<polygon points='362.86,430.32 363.93,430.03 365.00,429.73 365.00,434.56 363.93,434.56 362.86,434.56 ' style='stroke-width: 0.38; stroke: #BF3984; fill: #BF3984;' />
<polygon points='365.00,429.73 366.06,429.42 367.13,429.11 367.13,434.56 366.06,434.56 365.00,434.56 ' style='stroke-width: 0.38; stroke: #C03A83; fill: #C03A83;' />
<polygon points='367.13,429.11 368.20,428.80 369.27,428.48 369.27,434.56 368.20,434.56 367.13,434.56 ' style='stroke-width: 0.38; stroke: #C13B82; fill: #C13B82;' />
<polygon points='369.27,428.48 370.33,428.16 371.40,427.83 371.40,434.56 370.33,434.56 369.27,434.56 ' style='stroke-width: 0.38; stroke: #C23C81; fill: #C23C81;' />
<polygon points='371.40,427.83 372.47,427.49 373.54,427.15 373.54,434.56 372.47,434.56 371.40,434.56 ' style='stroke-width: 0.38; stroke: #C33D80; fill: #C33D80;' />
<polygon points='373.54,427.15 374.60,426.79 374.60,434.56 373.54,434.56 ' style='stroke-width: 0.38; stroke: #C43E7F; fill: #C43E7F;' />
<polygon points='374.60,426.79 375.67,426.43 375.67,434.56 374.60,434.56 ' style='stroke-width: 0.38; stroke: #C43F7F; fill: #C43F7F;' />
<polygon points='375.67,426.43 376.74,426.05 377.81,425.66 377.81,434.56 376.74,434.56 375.67,434.56 ' style='stroke-width: 0.38; stroke: #C5407E; fill: #C5407E;' />
<polygon points='377.81,425.66 378.87,425.26 379.94,424.83 379.94,434.56 378.87,434.56 377.81,434.56 ' style='stroke-width: 0.38; stroke: #C6417D; fill: #C6417D;' />
<polygon points='379.94,424.83 381.01,424.38 382.08,423.90 382.08,434.56 381.01,434.56 379.94,434.56 ' style='stroke-width: 0.38; stroke: #C7427C; fill: #C7427C;' />
<polygon points='382.08,423.90 383.14,423.39 384.21,422.86 384.21,434.56 383.14,434.56 382.08,434.56 ' style='stroke-width: 0.38; stroke: #C8437B; fill: #C8437B;' />
<polygon points='384.21,422.86 385.28,422.28 386.35,421.67 386.35,434.56 385.28,434.56 384.21,434.56 ' style='stroke-width: 0.38; stroke: #C9447A; fill: #C9447A;' />
<polygon points='386.35,421.67 387.42,421.01 388.48,420.32 388.48,434.56 387.42,434.56 386.35,434.56 ' style='stroke-width: 0.38; stroke: #CA457A; fill: #CA457A;' />
<polygon points='388.48,420.32 389.55,419.58 390.62,418.79 390.62,434.56 389.55,434.56 388.48,434.56 ' style='stroke-width: 0.38; stroke: #CB4679; fill: #CB4679;' />
<polygon points='390.62,418.79 391.69,417.95 391.69,434.56 390.62,434.56 ' style='stroke-width: 0.38; stroke: #CC4778; fill: #CC4778;' />
<polygon points='391.69,417.95 392.75,417.06 392.75,434.56 391.69,434.56 ' style='stroke-width: 0.38; stroke: #CC4878; fill: #CC4878;' />
<polygon points='392.75,417.06 393.82,416.13 393.82,434.56 392.75,434.56 ' style='stroke-width: 0.38; stroke: #CC4877; fill: #CC4877;' />
<polygon points='393.82,416.13 394.89,415.15 394.89,434.56 393.82,434.56 ' style='stroke-width: 0.38; stroke: #CC4977; fill: #CC4977;' />
<polygon points='394.89,415.15 395.96,414.13 397.02,413.05 397.02,434.56 395.96,434.56 394.89,434.56 ' style='stroke-width: 0.38; stroke: #CD4A76; fill: #CD4A76;' />
<polygon points='397.02,413.05 398.09,411.94 399.16,410.79 399.16,434.56 398.09,434.56 397.02,434.56 ' style='stroke-width: 0.38; stroke: #CE4B75; fill: #CE4B75;' />
<polygon points='399.16,410.79 400.23,409.61 401.29,408.40 401.29,434.56 400.23,434.56 399.16,434.56 ' style='stroke-width: 0.38; stroke: #CF4C74; fill: #CF4C74;' />
<polygon points='401.29,408.40 402.36,407.16 403.43,405.90 403.43,434.56 402.36,434.56 401.29,434.56 ' style='stroke-width: 0.38; stroke: #D04D73; fill: #D04D73;' />
<polygon points='403.43,405.90 404.50,404.63 405.56,403.36 405.56,434.56 404.50,434.56 403.43,434.56 ' style='stroke-width: 0.38; stroke: #D14E72; fill: #D14E72;' />
<polygon points='405.56,403.36 406.63,402.08 407.70,400.80 407.70,434.56 406.63,434.56 405.56,434.56 ' style='stroke-width: 0.38; stroke: #D24F71; fill: #D24F71;' />
<polygon points='407.70,400.80 408.77,399.54 408.77,434.56 407.70,434.56 ' style='stroke-width: 0.38; stroke: #D35071; fill: #D35071;' />
<polygon points='408.77,399.54 409.83,398.30 409.83,434.56 408.77,434.56 ' style='stroke-width: 0.38; stroke: #D35171; fill: #D35171;' />
<polygon points='409.83,398.30 410.90,397.07 411.97,395.88 411.97,434.56 410.90,434.56 409.83,434.56 ' style='stroke-width: 0.38; stroke: #D45270; fill: #D45270;' />
<polygon points='411.97,395.88 413.04,394.73 414.10,393.61 414.10,434.56 413.04,434.56 411.97,434.56 ' style='stroke-width: 0.38; stroke: #D5536F; fill: #D5536F;' />
<polygon points='414.10,393.61 415.17,392.54 416.24,391.51 416.24,434.56 415.17,434.56 414.10,434.56 ' style='stroke-width: 0.38; stroke: #D5546E; fill: #D5546E;' />
<polygon points='416.24,391.51 417.31,390.53 418.37,389.62 418.37,434.56 417.31,434.56 416.24,434.56 ' style='stroke-width: 0.38; stroke: #D6556D; fill: #D6556D;' />
<polygon points='418.37,389.62 419.44,388.76 420.51,387.96 420.51,434.56 419.44,434.56 418.37,434.56 ' style='stroke-width: 0.38; stroke: #D7566C; fill: #D7566C;' />
<polygon points='420.51,387.96 421.58,387.21 422.64,386.51 422.64,434.56 421.58,434.56 420.51,434.56 ' style='stroke-width: 0.38; stroke: #D8576B; fill: #D8576B;' />
<polygon points='422.64,386.51 423.71,385.89 424.78,385.32 424.78,434.56 423.71,434.56 422.64,434.56 ' style='stroke-width: 0.38; stroke: #D9586A; fill: #D9586A;' />
<polygon points='424.78,385.32 425.85,384.80 425.85,434.56 424.78,434.56 ' style='stroke-width: 0.38; stroke: #DA596A; fill: #DA596A;' />
<polygon points='425.85,384.80 426.91,384.33 426.91,434.56 425.85,434.56 ' style='stroke-width: 0.38; stroke: #DA5A6A; fill: #DA5A6A;' />
<polygon points='426.91,384.33 427.98,383.91 429.05,383.53 429.05,434.56 427.98,434.56 426.91,434.56 ' style='stroke-width: 0.38; stroke: #DA5B69; fill: #DA5B69;' />
<polygon points='429.05,383.53 430.12,383.19 431.18,382.89 431.18,434.56 430.12,434.56 429.05,434.56 ' style='stroke-width: 0.38; stroke: #DB5C68; fill: #DB5C68;' />
<polygon points='431.18,382.89 432.25,382.61 433.32,382.35 433.32,434.56 432.25,434.56 431.18,434.56 ' style='stroke-width: 0.38; stroke: #DC5D67; fill: #DC5D67;' />
<polygon points='433.32,382.35 434.39,382.11 435.45,381.87 435.45,434.56 434.39,434.56 433.32,434.56 ' style='stroke-width: 0.38; stroke: #DD5E66; fill: #DD5E66;' />
<polygon points='435.45,381.87 436.52,381.63 437.59,381.39 437.59,434.56 436.52,434.56 435.45,434.56 ' style='stroke-width: 0.38; stroke: #DE5F65; fill: #DE5F65;' />
<polygon points='437.59,381.39 438.66,381.14 438.66,434.56 437.59,434.56 ' style='stroke-width: 0.38; stroke: #DE6064; fill: #DE6064;' />
<polygon points='438.66,381.14 439.72,380.87 439.72,434.56 438.66,434.56 ' style='stroke-width: 0.38; stroke: #DE6164; fill: #DE6164;' />
<polygon points='439.72,380.87 440.79,380.57 441.86,380.24 441.86,434.56 440.79,434.56 439.72,434.56 ' style='stroke-width: 0.38; stroke: #DF6263; fill: #DF6263;' />
<polygon points='441.86,380.24 442.93,379.88 443.99,379.48 443.99,434.56 442.93,434.56 441.86,434.56 ' style='stroke-width: 0.38; stroke: #E06363; fill: #E06363;' />
<polygon points='443.99,379.48 445.06,379.04 446.13,378.55 446.13,434.56 445.06,434.56 443.99,434.56 ' style='stroke-width: 0.38; stroke: #E16462; fill: #E16462;' />
<polygon points='446.13,378.55 447.20,378.01 448.26,377.43 448.26,434.56 447.20,434.56 446.13,434.56 ' style='stroke-width: 0.38; stroke: #E26561; fill: #E26561;' />
<polygon points='448.26,377.43 449.33,376.80 450.40,376.13 450.40,434.56 449.33,434.56 448.26,434.56 ' style='stroke-width: 0.38; stroke: #E26660; fill: #E26660;' />
<polygon points='450.40,376.13 451.47,375.40 451.47,434.56 450.40,434.56 ' style='stroke-width: 0.38; stroke: #E3675F; fill: #E3675F;' />
<polygon points='451.47,375.40 452.53,374.63 452.53,434.56 451.47,434.56 ' style='stroke-width: 0.38; stroke: #E3685F; fill: #E3685F;' />
<polygon points='452.53,374.63 453.60,373.83 454.67,373.00 454.67,434.56 453.60,434.56 452.53,434.56 ' style='stroke-width: 0.38; stroke: #E4695E; fill: #E4695E;' />
<polygon points='454.67,373.00 455.74,372.14 456.80,371.25 456.80,434.56 455.74,434.56 454.67,434.56 ' style='stroke-width: 0.38; stroke: #E56A5D; fill: #E56A5D;' />
<polygon points='456.80,371.25 457.87,370.35 458.94,369.45 458.94,434.56 457.87,434.56 456.80,434.56 ' style='stroke-width: 0.38; stroke: #E56B5D; fill: #E56B5D;' />
<polygon points='458.94,369.45 460.01,368.54 461.07,367.64 461.07,434.56 460.01,434.56 458.94,434.56 ' style='stroke-width: 0.38; stroke: #E66C5C; fill: #E66C5C;' />
<polygon points='461.07,367.64 462.14,366.76 462.14,434.56 461.07,434.56 ' style='stroke-width: 0.38; stroke: #E76D5B; fill: #E76D5B;' />
<polygon points='462.14,366.76 463.21,365.90 463.21,434.56 462.14,434.56 ' style='stroke-width: 0.38; stroke: #E76E5B; fill: #E76E5B;' />
<polygon points='463.21,365.90 464.28,365.07 465.34,364.27 465.34,434.56 464.28,434.56 463.21,434.56 ' style='stroke-width: 0.38; stroke: #E76F5A; fill: #E76F5A;' />
<polygon points='465.34,364.27 466.41,363.51 467.48,362.81 467.48,434.56 466.41,434.56 465.34,434.56 ' style='stroke-width: 0.38; stroke: #E87059; fill: #E87059;' />
<polygon points='467.48,362.81 468.55,362.17 469.61,361.58 469.61,434.56 468.55,434.56 467.48,434.56 ' style='stroke-width: 0.38; stroke: #E97158; fill: #E97158;' />
<polygon points='469.61,361.58 470.68,361.06 471.75,360.60 471.75,434.56 470.68,434.56 469.61,434.56 ' style='stroke-width: 0.38; stroke: #E97257; fill: #E97257;' />
<polygon points='471.75,360.60 472.82,360.23 472.82,434.56 471.75,434.56 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,360.23 473.88,359.93 473.88,434.56 472.82,434.56 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,359.93 474.95,359.71 476.02,359.56 476.02,434.56 474.95,434.56 473.88,434.56 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,359.56 477.09,359.49 478.15,359.52 478.15,434.56 477.09,434.56 476.02,434.56 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,359.52 479.22,359.63 480.29,359.82 480.29,434.56 479.22,434.56 478.15,434.56 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,359.82 481.36,360.08 481.36,434.56 480.29,434.56 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,360.08 482.42,360.43 482.42,434.56 481.36,434.56 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,360.43 483.49,360.85 484.56,361.37 484.56,434.56 483.49,434.56 482.42,434.56 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,361.37 485.63,361.96 486.69,362.63 486.69,434.56 485.63,434.56 484.56,434.56 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polygon points='486.69,362.63 487.76,363.36 488.83,364.17 488.83,434.56 487.76,434.56 486.69,434.56 ' style='stroke-width: 0.38; stroke: #EF7C51; fill: #EF7C51;' />
<polygon points='488.83,364.17 489.90,365.05 489.90,434.56 488.83,434.56 ' style='stroke-width: 0.38; stroke: #EF7D50; fill: #EF7D50;' />
<polygon points='489.90,365.05 490.97,366.00 490.97,434.56 489.90,434.56 ' style='stroke-width: 0.38; stroke: #EF7E50; fill: #EF7E50;' />
<polygon points='490.97,366.00 492.03,367.01 493.10,368.08 493.10,434.56 492.03,434.56 490.97,434.56 ' style='stroke-width: 0.38; stroke: #F07F4F; fill: #F07F4F;' />
<polygon points='493.10,368.08 494.17,369.21 495.24,370.41 495.24,434.56 494.17,434.56 493.10,434.56 ' style='stroke-width: 0.38; stroke: #F0804E; fill: #F0804E;' />
<polygon points='495.24,370.41 496.30,371.65 497.37,372.94 497.37,434.56 496.30,434.56 495.24,434.56 ' style='stroke-width: 0.38; stroke: #F1814D; fill: #F1814D;' />
<polygon points='497.37,372.94 498.44,374.28 498.44,434.56 497.37,434.56 ' style='stroke-width: 0.38; stroke: #F1824C; fill: #F1824C;' />
<polygon points='498.44,374.28 499.51,375.65 499.51,434.56 498.44,434.56 ' style='stroke-width: 0.38; stroke: #F1834C; fill: #F1834C;' />
<polygon points='499.51,375.65 500.57,377.07 501.64,378.52 501.64,434.56 500.57,434.56 499.51,434.56 ' style='stroke-width: 0.38; stroke: #F2844B; fill: #F2844B;' />
<polygon points='501.64,378.52 502.71,379.99 503.78,381.49 503.78,434.56 502.71,434.56 501.64,434.56 ' style='stroke-width: 0.38; stroke: #F3854B; fill: #F3854B;' />
<polygon points='503.78,381.49 504.84,383.00 504.84,434.56 503.78,434.56 ' style='stroke-width: 0.38; stroke: #F3864A; fill: #F3864A;' />
<polygon points='504.84,383.00 505.91,384.54 505.91,434.56 504.84,434.56 ' style='stroke-width: 0.38; stroke: #F3874A; fill: #F3874A;' />
<polygon points='505.91,384.54 506.98,386.08 508.05,387.63 508.05,434.56 506.98,434.56 505.91,434.56 ' style='stroke-width: 0.38; stroke: #F48849; fill: #F48849;' />
<polygon points='508.05,387.63 509.11,389.18 510.18,390.72 510.18,434.56 509.11,434.56 508.05,434.56 ' style='stroke-width: 0.38; stroke: #F48948; fill: #F48948;' />
<polygon points='510.18,390.72 511.25,392.26 511.25,434.56 510.18,434.56 ' style='stroke-width: 0.38; stroke: #F58A47; fill: #F58A47;' />
<polygon points='511.25,392.26 512.32,393.79 512.32,434.56 511.25,434.56 ' style='stroke-width: 0.38; stroke: #F58B47; fill: #F58B47;' />
<polygon points='512.32,393.79 513.38,395.31 514.45,396.81 514.45,434.56 513.38,434.56 512.32,434.56 ' style='stroke-width: 0.38; stroke: #F58C46; fill: #F58C46;' />
<polygon points='514.45,396.81 515.52,398.29 516.59,399.75 516.59,434.56 515.52,434.56 514.45,434.56 ' style='stroke-width: 0.38; stroke: #F68D45; fill: #F68D45;' />
<polygon points='516.59,399.75 517.65,401.18 517.65,434.56 516.59,434.56 ' style='stroke-width: 0.38; stroke: #F68E44; fill: #F68E44;' />
<polygon points='517.65,401.18 518.72,402.59 518.72,434.56 517.65,434.56 ' style='stroke-width: 0.38; stroke: #F68F44; fill: #F68F44;' />
<polygon points='518.72,402.59 519.79,403.97 520.86,405.33 520.86,434.56 519.79,434.56 518.72,434.56 ' style='stroke-width: 0.38; stroke: #F79044; fill: #F79044;' />
<polygon points='520.86,405.33 521.92,406.66 522.99,407.96 522.99,434.56 521.92,434.56 520.86,434.56 ' style='stroke-width: 0.38; stroke: #F79143; fill: #F79143;' />
<polygon points='522.99,407.96 524.06,409.23 524.06,434.56 522.99,434.56 ' style='stroke-width: 0.38; stroke: #F79242; fill: #F79242;' />
<polygon points='524.06,409.23 525.13,410.47 525.13,434.56 524.06,434.56 ' style='stroke-width: 0.38; stroke: #F79342; fill: #F79342;' />
<polygon points='525.13,410.47 526.19,411.68 527.26,412.86 527.26,434.56 526.19,434.56 525.13,434.56 ' style='stroke-width: 0.38; stroke: #F89441; fill: #F89441;' />
<polygon points='527.26,412.86 528.33,414.01 529.40,415.13 529.40,434.56 528.33,434.56 527.26,434.56 ' style='stroke-width: 0.38; stroke: #F89540; fill: #F89540;' />
<polygon points='529.40,415.13 530.46,416.22 530.46,434.56 529.40,434.56 ' style='stroke-width: 0.38; stroke: #F9963F; fill: #F9963F;' />
<polygon points='530.46,416.22 531.53,417.28 531.53,434.56 530.46,434.56 ' style='stroke-width: 0.38; stroke: #F9973F; fill: #F9973F;' />
<polygon points='531.53,417.28 532.60,418.31 533.67,419.31 533.67,434.56 532.60,434.56 531.53,434.56 ' style='stroke-width: 0.38; stroke: #F9983E; fill: #F9983E;' />
<polygon points='533.67,419.31 534.73,420.27 534.73,434.56 533.67,434.56 ' style='stroke-width: 0.38; stroke: #F9993E; fill: #F9993E;' />
<polygon points='534.73,420.27 535.80,421.21 535.80,434.56 534.73,434.56 ' style='stroke-width: 0.38; stroke: #F99A3E; fill: #F99A3E;' />
<polygon points='535.80,421.21 536.87,422.11 537.94,422.98 537.94,434.56 536.87,434.56 535.80,434.56 ' style='stroke-width: 0.38; stroke: #FA9B3D; fill: #FA9B3D;' />
<polygon points='537.94,422.98 539.00,423.81 540.07,424.61 540.07,434.56 539.00,434.56 537.94,434.56 ' style='stroke-width: 0.38; stroke: #FA9C3C; fill: #FA9C3C;' />
<polygon points='540.07,424.61 541.14,425.37 541.14,434.56 540.07,434.56 ' style='stroke-width: 0.38; stroke: #FA9D3B; fill: #FA9D3B;' />
<polygon points='541.14,425.37 542.21,426.11 542.21,434.56 541.14,434.56 ' style='stroke-width: 0.38; stroke: #FA9E3B; fill: #FA9E3B;' />
<polygon points='542.21,426.11 543.27,426.80 544.34,427.46 544.34,434.56 543.27,434.56 542.21,434.56 ' style='stroke-width: 0.38; stroke: #FB9F3A; fill: #FB9F3A;' />
<polygon points='544.34,427.46 545.41,428.07 545.41,434.56 544.34,434.56 ' style='stroke-width: 0.38; stroke: #FBA039; fill: #FBA039;' />
<polygon points='545.41,428.07 546.48,428.66 546.48,434.56 545.41,434.56 ' style='stroke-width: 0.38; stroke: #FBA139; fill: #FBA139;' />
<polygon points='546.48,428.66 547.54,429.21 548.61,429.73 548.61,434.56 547.54,434.56 546.48,434.56 ' style='stroke-width: 0.38; stroke: #FBA238; fill: #FBA238;' />
<polygon points='548.61,429.73 549.68,430.21 550.75,430.65 550.75,434.56 549.68,434.56 548.61,434.56 ' style='stroke-width: 0.38; stroke: #FCA338; fill: #FCA338;' />
<polygon points='550.75,430.65 551.81,431.06 551.81,434.56 550.75,434.56 ' style='stroke-width: 0.38; stroke: #FCA437; fill: #FCA437;' />
<polygon points='551.81,431.06 552.88,431.44 552.88,434.56 551.81,434.56 ' style='stroke-width: 0.38; stroke: #FCA537; fill: #FCA537;' />
<polygon points='552.88,431.44 553.95,431.79 555.02,432.11 555.02,434.56 553.95,434.56 552.88,434.56 ' style='stroke-width: 0.38; stroke: #FCA636; fill: #FCA636;' />
<polygon points='555.02,432.11 556.08,432.39 556.08,434.56 555.02,434.56 ' style='stroke-width: 0.38; stroke: #FCA735; fill: #FCA735;' />
<polygon points='556.08,432.39 557.15,432.66 557.15,434.56 556.08,434.56 ' style='stroke-width: 0.38; stroke: #FCA835; fill: #FCA835;' />
<polygon points='557.15,432.66 558.22,432.89 559.29,433.11 559.29,434.56 558.22,434.56 557.15,434.56 ' style='stroke-width: 0.38; stroke: #FCA934; fill: #FCA934;' />
<polygon points='559.29,433.11 560.35,433.30 560.35,434.56 559.29,434.56 ' style='stroke-width: 0.38; stroke: #FDAA33; fill: #FDAA33;' />
<polygon points='560.35,433.30 561.42,433.47 561.42,434.56 560.35,434.56 ' style='stroke-width: 0.38; stroke: #FDAB33; fill: #FDAB33;' />
<polygon points='561.42,433.47 561.42,434.56 ' style='stroke-width: 0.38; stroke: #FDAC33; fill: #FDAC33;' />
<polyline points='346.85,433.52 347.92,433.39 348.98,433.25 350.05,433.09 351.12,432.92 352.19,432.74 353.25,432.55 354.32,432.34 355.39,432.13 356.46,431.90 357.52,431.66 358.59,431.41 359.66,431.15 360.73,430.88 361.79,430.60 362.86,430.32 363.93,430.03 365.00,429.73 366.06,429.42 367.13,429.11 368.20,428.80 369.27,428.48 370.33,428.16 371.40,427.83 372.47,427.49 373.54,427.15 374.60,426.79 375.67,426.43 376.74,426.05 377.81,425.66 378.87,425.26 379.94,424.83 381.01,424.38 382.08,423.90 383.14,423.39 384.21,422.86 385.28,422.28 386.35,421.67 387.42,421.01 388.48,420.32 389.55,419.58 390.62,418.79 391.69,417.95 392.75,417.06 393.82,416.13 394.89,415.15 395.96,414.13 397.02,413.05 398.09,411.94 399.16,410.79 400.23,409.61 401.29,408.40 402.36,407.16 403.43,405.90 404.50,404.63 405.56,403.36 406.63,402.08 407.70,400.80 408.77,399.54 409.83,398.30 410.90,397.07 411.97,395.88 413.04,394.73 414.10,393.61 415.17,392.54 416.24,391.51 417.31,390.53 418.37,389.62 419.44,388.76 420.51,387.96 421.58,387.21 422.64,386.51 423.71,385.89 424.78,385.32 425.85,384.80 426.91,384.33 427.98,383.91 429.05,383.53 430.12,383.19 431.18,382.89 432.25,382.61 433.32,382.35 434.39,382.11 435.45,381.87 436.52,381.63 437.59,381.39 438.66,381.14 439.72,380.87 440.79,380.57 441.86,380.24 442.93,379.88 443.99,379.48 445.06,379.04 446.13,378.55 447.20,378.01 448.26,377.43 449.33,376.80 450.40,376.13 451.47,375.40 452.53,374.63 453.60,373.83 454.67,373.00 455.74,372.14 456.80,371.25 457.87,370.35 458.94,369.45 460.01,368.54 461.07,367.64 462.14,366.76 463.21,365.90 464.28,365.07 465.34,364.27 466.41,363.51 467.48,362.81 468.55,362.17 469.61,361.58 470.68,361.06 471.75,360.60 472.82,360.23 473.88,359.93 474.95,359.71 476.02,359.56 477.09,359.49 478.15,359.52 479.22,359.63 480.29,359.82 481.36,360.08 482.42,360.43 483.49,360.85 484.56,361.37 485.63,361.96 486.69,362.63 487.76,363.36 488.83,364.17 489.90,365.05 490.97,366.00 492.03,367.01 493.10,368.08 494.17,369.21 495.24,370.41 496.30,371.65 497.37,372.94 498.44,374.28 499.51,375.65 500.57,377.07 501.64,378.52 502.71,379.99 503.78,381.49 504.84,383.00 505.91,384.54 506.98,386.08 508.05,387.63 509.11,389.18 510.18,390.72 511.25,392.26 512.32,393.79 513.38,395.31 514.45,396.81 515.52,398.29 516.59,399.75 517.65,401.18 518.72,402.59 519.79,403.97 520.86,405.33 521.92,406.66 522.99,407.96 524.06,409.23 525.13,410.47 526.19,411.68 527.26,412.86 528.33,414.01 529.40,415.13 530.46,416.22 531.53,417.28 532.60,418.31 533.67,419.31 534.73,420.27 535.80,421.21 536.87,422.11 537.94,422.98 539.00,423.81 540.07,424.61 541.14,425.37 542.21,426.11 543.27,426.80 544.34,427.46 545.41,428.07 546.48,428.66 547.54,429.21 548.61,429.73 549.68,430.21 550.75,430.65 551.81,431.06 552.88,431.44 553.95,431.79 555.02,432.11 556.08,432.39 557.15,432.66 558.22,432.89 559.29,433.11 560.35,433.30 561.42,433.47 ' style='stroke-width: 1.07;' />
<polygon points='286.00,466.87 287.07,466.71 288.14,466.53 288.14,467.97 287.07,467.97 286.00,467.97 ' style='stroke-width: 0.38; stroke: #9410A2; fill: #9410A2;' />
<polygon points='288.14,466.53 289.20,466.33 289.20,467.97 288.14,467.97 ' style='stroke-width: 0.38; stroke: #9511A1; fill: #9511A1;' />
<polygon points='289.20,466.33 290.27,466.11 290.27,467.97 289.20,467.97 ' style='stroke-width: 0.38; stroke: #9512A1; fill: #9512A1;' />
<polygon points='290.27,466.11 291.34,465.87 291.34,467.97 290.27,467.97 ' style='stroke-width: 0.38; stroke: #9613A1; fill: #9613A1;' />
<polygon points='291.34,465.87 292.41,465.60 292.41,467.97 291.34,467.97 ' style='stroke-width: 0.38; stroke: #9713A1; fill: #9713A1;' />
<polygon points='292.41,465.60 293.47,465.31 294.54,465.00 294.54,467.97 293.47,467.97 292.41,467.97 ' style='stroke-width: 0.38; stroke: #9814A0; fill: #9814A0;' />
<polygon points='294.54,465.00 295.61,464.66 296.68,464.30 296.68,467.97 295.61,467.97 294.54,467.97 ' style='stroke-width: 0.38; stroke: #99159F; fill: #99159F;' />
<polygon points='296.68,464.30 297.74,463.91 297.74,467.97 296.68,467.97 ' style='stroke-width: 0.38; stroke: #9A169F; fill: #9A169F;' />
<polygon points='297.74,463.91 298.81,463.49 298.81,467.97 297.74,467.97 ' style='stroke-width: 0.38; stroke: #9B169F; fill: #9B169F;' />
<polygon points='298.81,463.49 299.88,463.05 300.95,462.59 300.95,467.97 299.88,467.97 298.81,467.97 ' style='stroke-width: 0.38; stroke: #9C179E; fill: #9C179E;' />
<polygon points='300.95,462.59 302.01,462.10 303.08,461.59 303.08,467.97 302.01,467.97 300.95,467.97 ' style='stroke-width: 0.38; stroke: #9D189D; fill: #9D189D;' />
<polygon points='303.08,461.59 304.15,461.05 304.15,467.97 303.08,467.97 ' style='stroke-width: 0.38; stroke: #9E199D; fill: #9E199D;' />
<polygon points='304.15,461.05 305.22,460.49 305.22,467.97 304.15,467.97 ' style='stroke-width: 0.38; stroke: #9F199D; fill: #9F199D;' />
<polygon points='305.22,460.49 306.28,459.91 307.35,459.32 307.35,467.97 306.28,467.97 305.22,467.97 ' style='stroke-width: 0.38; stroke: #A01A9C; fill: #A01A9C;' />
<polygon points='307.35,459.32 308.42,458.71 308.42,467.97 307.35,467.97 ' style='stroke-width: 0.38; stroke: #A11B9B; fill: #A11B9B;' />
<polygon points='308.42,458.71 309.49,458.09 309.49,467.97 308.42,467.97 ' style='stroke-width: 0.38; stroke: #A11C9B; fill: #A11C9B;' />
<polygon points='309.49,458.09 310.55,457.46 311.62,456.82 311.62,467.97 310.55,467.97 309.49,467.97 ' style='stroke-width: 0.38; stroke: #A21D9A; fill: #A21D9A;' />
<polygon points='311.62,456.82 312.69,456.17 312.69,467.97 311.62,467.97 ' style='stroke-width: 0.38; stroke: #A31E9A; fill: #A31E9A;' />
<polygon points='312.69,456.17 313.76,455.52 313.76,467.97 312.69,467.97 ' style='stroke-width: 0.38; stroke: #A41E9A; fill: #A41E9A;' />
<polygon points='313.76,455.52 314.82,454.87 315.89,454.22 315.89,467.97 314.82,467.97 313.76,467.97 ' style='stroke-width: 0.38; stroke: #A51F99; fill: #A51F99;' />
<polygon points='315.89,454.22 316.96,453.57 318.03,452.93 318.03,467.97 316.96,467.97 315.89,467.97 ' style='stroke-width: 0.38; stroke: #A62098; fill: #A62098;' />
<polygon points='318.03,452.93 319.09,452.29 320.16,451.66 320.16,467.97 319.09,467.97 318.03,467.97 ' style='stroke-width: 0.38; stroke: #A72197; fill: #A72197;' />
<polygon points='320.16,451.66 321.23,451.05 321.23,467.97 320.16,467.97 ' style='stroke-width: 0.38; stroke: #A82296; fill: #A82296;' />
<polygon points='321.23,451.05 322.30,450.44 322.30,467.97 321.23,467.97 ' style='stroke-width: 0.38; stroke: #A92296; fill: #A92296;' />
<polygon points='322.30,450.44 323.36,449.84 324.43,449.25 324.43,467.97 323.36,467.97 322.30,467.97 ' style='stroke-width: 0.38; stroke: #AA2395; fill: #AA2395;' />
<polygon points='324.43,449.25 325.50,448.67 325.50,467.97 324.43,467.97 ' style='stroke-width: 0.38; stroke: #AB2494; fill: #AB2494;' />
<polygon points='325.50,448.67 326.57,448.10 326.57,467.97 325.50,467.97 ' style='stroke-width: 0.38; stroke: #AB2594; fill: #AB2594;' />
<polygon points='326.57,448.10 327.63,447.53 328.70,446.97 328.70,467.97 327.63,467.97 326.57,467.97 ' style='stroke-width: 0.38; stroke: #AC2694; fill: #AC2694;' />
<polygon points='328.70,446.97 329.77,446.42 330.84,445.87 330.84,467.97 329.77,467.97 328.70,467.97 ' style='stroke-width: 0.38; stroke: #AD2793; fill: #AD2793;' />
<polygon points='330.84,445.87 331.90,445.32 331.90,467.97 330.84,467.97 ' style='stroke-width: 0.38; stroke: #AE2892; fill: #AE2892;' />
<polygon points='331.90,445.32 332.97,444.76 332.97,467.97 331.90,467.97 ' style='stroke-width: 0.38; stroke: #AF2892; fill: #AF2892;' />
<polygon points='332.97,444.76 334.04,444.20 335.11,443.63 335.11,467.97 334.04,467.97 332.97,467.97 ' style='stroke-width: 0.38; stroke: #B02991; fill: #B02991;' />
<polygon points='335.11,443.63 336.17,443.05 337.24,442.45 337.24,467.97 336.17,467.97 335.11,467.97 ' style='stroke-width: 0.38; stroke: #B12A90; fill: #B12A90;' />
<polygon points='337.24,442.45 338.31,441.84 339.38,441.21 339.38,467.97 338.31,467.97 337.24,467.97 ' style='stroke-width: 0.38; stroke: #B22B8F; fill: #B22B8F;' />
<polygon points='339.38,441.21 340.44,440.56 340.44,467.97 339.38,467.97 ' style='stroke-width: 0.38; stroke: #B32C8E; fill: #B32C8E;' />
<polygon points='340.44,440.56 341.51,439.88 341.51,467.97 340.44,467.97 ' style='stroke-width: 0.38; stroke: #B32D8E; fill: #B32D8E;' />
<polygon points='341.51,439.88 342.58,439.17 343.65,438.44 343.65,467.97 342.58,467.97 341.51,467.97 ' style='stroke-width: 0.38; stroke: #B42E8D; fill: #B42E8D;' />
<polygon points='343.65,438.44 344.71,437.69 345.78,436.91 345.78,467.97 344.71,467.97 343.65,467.97 ' style='stroke-width: 0.38; stroke: #B52F8C; fill: #B52F8C;' />
<polygon points='345.78,436.91 346.85,436.10 347.92,435.26 347.92,467.97 346.85,467.97 345.78,467.97 ' style='stroke-width: 0.38; stroke: #B6308B; fill: #B6308B;' />
<polygon points='347.92,435.26 348.98,434.39 350.05,433.51 350.05,467.97 348.98,467.97 347.92,467.97 ' style='stroke-width: 0.38; stroke: #B7318A; fill: #B7318A;' />
<polygon points='350.05,433.51 351.12,432.60 351.12,467.97 350.05,467.97 ' style='stroke-width: 0.38; stroke: #B83289; fill: #B83289;' />
<polygon points='351.12,432.60 352.19,431.67 352.19,467.97 351.12,467.97 ' style='stroke-width: 0.38; stroke: #B93289; fill: #B93289;' />
<polygon points='352.19,431.67 353.25,430.71 354.32,429.75 354.32,467.97 353.25,467.97 352.19,467.97 ' style='stroke-width: 0.38; stroke: #BA3388; fill: #BA3388;' />
<polygon points='354.32,429.75 355.39,428.77 356.46,427.79 356.46,467.97 355.39,467.97 354.32,467.97 ' style='stroke-width: 0.38; stroke: #BB3488; fill: #BB3488;' />
<polygon points='356.46,427.79 357.52,426.80 357.52,467.97 356.46,467.97 ' style='stroke-width: 0.38; stroke: #BC3587; fill: #BC3587;' />
<polygon points='357.52,426.80 358.59,425.81 358.59,467.97 357.52,467.97 ' style='stroke-width: 0.38; stroke: #BC3687; fill: #BC3687;' />
<polygon points='358.59,425.81 359.66,424.82 360.73,423.84 360.73,467.97 359.66,467.97 358.59,467.97 ' style='stroke-width: 0.38; stroke: #BD3786; fill: #BD3786;' />
<polygon points='360.73,423.84 361.79,422.87 362.86,421.92 362.86,467.97 361.79,467.97 360.73,467.97 ' style='stroke-width: 0.38; stroke: #BE3885; fill: #BE3885;' />
<polygon points='362.86,421.92 363.93,420.98 365.00,420.07 365.00,467.97 363.93,467.97 362.86,467.97 ' style='stroke-width: 0.38; stroke: #BF3984; fill: #BF3984;' />
<polygon points='365.00,420.07 366.06,419.18 367.13,418.32 367.13,467.97 366.06,467.97 365.00,467.97 ' style='stroke-width: 0.38; stroke: #C03A83; fill: #C03A83;' />
<polygon points='367.13,418.32 368.20,417.49 369.27,416.71 369.27,467.97 368.20,467.97 367.13,467.97 ' style='stroke-width: 0.38; stroke: #C13B82; fill: #C13B82;' />
<polygon points='369.27,416.71 370.33,415.97 371.40,415.26 371.40,467.97 370.33,467.97 369.27,467.97 ' style='stroke-width: 0.38; stroke: #C23C81; fill: #C23C81;' />
<polygon points='371.40,415.26 372.47,414.60 373.54,413.98 373.54,467.97 372.47,467.97 371.40,467.97 ' style='stroke-width: 0.38; stroke: #C33D80; fill: #C33D80;' />
<polygon points='373.54,413.98 374.60,413.43 374.60,467.97 373.54,467.97 ' style='stroke-width: 0.38; stroke: #C43E7F; fill: #C43E7F;' />
<polygon points='374.60,413.43 375.67,412.92 375.67,467.97 374.60,467.97 ' style='stroke-width: 0.38; stroke: #C43F7F; fill: #C43F7F;' />
<polygon points='375.67,412.92 376.74,412.47 377.81,412.08 377.81,467.97 376.74,467.97 375.67,467.97 ' style='stroke-width: 0.38; stroke: #C5407E; fill: #C5407E;' />
<polygon points='377.81,412.08 378.87,411.74 379.94,411.47 379.94,467.97 378.87,467.97 377.81,467.97 ' style='stroke-width: 0.38; stroke: #C6417D; fill: #C6417D;' />
<polygon points='379.94,411.47 381.01,411.27 382.08,411.12 382.08,467.97 381.01,467.97 379.94,467.97 ' style='stroke-width: 0.38; stroke: #C7427C; fill: #C7427C;' />
<polygon points='382.08,411.12 383.14,411.04 384.21,411.02 384.21,467.97 383.14,467.97 382.08,467.97 ' style='stroke-width: 0.38; stroke: #C8437B; fill: #C8437B;' />
<polygon points='384.21,411.02 385.28,411.08 386.35,411.20 386.35,467.97 385.28,467.97 384.21,467.97 ' style='stroke-width: 0.38; stroke: #C9447A; fill: #C9447A;' />
<polygon points='386.35,411.20 387.42,411.39 388.48,411.64 388.48,467.97 387.42,467.97 386.35,467.97 ' style='stroke-width: 0.38; stroke: #CA457A; fill: #CA457A;' />
<polygon points='388.48,411.64 389.55,411.94 390.62,412.32 390.62,467.97 389.55,467.97 388.48,467.97 ' style='stroke-width: 0.38; stroke: #CB4679; fill: #CB4679;' />
<polygon points='390.62,412.32 391.69,412.76 391.69,467.97 390.62,467.97 ' style='stroke-width: 0.38; stroke: #CC4778; fill: #CC4778;' />
<polygon points='391.69,412.76 392.75,413.25 392.75,467.97 391.69,467.97 ' style='stroke-width: 0.38; stroke: #CC4878; fill: #CC4878;' />
<polygon points='392.75,413.25 393.82,413.79 393.82,467.97 392.75,467.97 ' style='stroke-width: 0.38; stroke: #CC4877; fill: #CC4877;' />
<polygon points='393.82,413.79 394.89,414.38 394.89,467.97 393.82,467.97 ' style='stroke-width: 0.38; stroke: #CC4977; fill: #CC4977;' />
<polygon points='394.89,414.38 395.96,415.01 397.02,415.69 397.02,467.97 395.96,467.97 394.89,467.97 ' style='stroke-width: 0.38; stroke: #CD4A76; fill: #CD4A76;' />
<polygon points='397.02,415.69 398.09,416.40 399.16,417.13 399.16,467.97 398.09,467.97 397.02,467.97 ' style='stroke-width: 0.38; stroke: #CE4B75; fill: #CE4B75;' />
<polygon points='399.16,417.13 400.23,417.88 401.29,418.65 401.29,467.97 400.23,467.97 399.16,467.97 ' style='stroke-width: 0.38; stroke: #CF4C74; fill: #CF4C74;' />
<polygon points='401.29,418.65 402.36,419.43 403.43,420.20 403.43,467.97 402.36,467.97 401.29,467.97 ' style='stroke-width: 0.38; stroke: #D04D73; fill: #D04D73;' />
<polygon points='403.43,420.20 404.50,420.96 405.56,421.70 405.56,467.97 404.50,467.97 403.43,467.97 ' style='stroke-width: 0.38; stroke: #D14E72; fill: #D14E72;' />
<polygon points='405.56,421.70 406.63,422.43 407.70,423.11 407.70,467.97 406.63,467.97 405.56,467.97 ' style='stroke-width: 0.38; stroke: #D24F71; fill: #D24F71;' />
<polygon points='407.70,423.11 408.77,423.74 408.77,467.97 407.70,467.97 ' style='stroke-width: 0.38; stroke: #D35071; fill: #D35071;' />
<polygon points='408.77,423.74 409.83,424.33 409.83,467.97 408.77,467.97 ' style='stroke-width: 0.38; stroke: #D35171; fill: #D35171;' />
<polygon points='409.83,424.33 410.90,424.87 411.97,425.34 411.97,467.97 410.90,467.97 409.83,467.97 ' style='stroke-width: 0.38; stroke: #D45270; fill: #D45270;' />
<polygon points='411.97,425.34 413.04,425.73 414.10,426.03 414.10,467.97 413.04,467.97 411.97,467.97 ' style='stroke-width: 0.38; stroke: #D5536F; fill: #D5536F;' />
<polygon points='414.10,426.03 415.17,426.26 416.24,426.40 416.24,467.97 415.17,467.97 414.10,467.97 ' style='stroke-width: 0.38; stroke: #D5546E; fill: #D5546E;' />
<polygon points='416.24,426.40 417.31,426.45 418.37,426.37 418.37,467.97 417.31,467.97 416.24,467.97 ' style='stroke-width: 0.38; stroke: #D6556D; fill: #D6556D;' />
<polygon points='418.37,426.37 419.44,426.20 420.51,425.93 420.51,467.97 419.44,467.97 418.37,467.97 ' style='stroke-width: 0.38; stroke: #D7566C; fill: #D7566C;' />
<polygon points='420.51,425.93 421.58,425.56 422.64,425.09 422.64,467.97 421.58,467.97 420.51,467.97 ' style='stroke-width: 0.38; stroke: #D8576B; fill: #D8576B;' />
<polygon points='422.64,425.09 423.71,424.50 424.78,423.80 424.78,467.97 423.71,467.97 422.64,467.97 ' style='stroke-width: 0.38; stroke: #D9586A; fill: #D9586A;' />
<polygon points='424.78,423.80 425.85,423.02 425.85,467.97 424.78,467.97 ' style='stroke-width: 0.38; stroke: #DA596A; fill: #DA596A;' />
<polygon points='425.85,423.02 426.91,422.15 426.91,467.97 425.85,467.97 ' style='stroke-width: 0.38; stroke: #DA5A6A; fill: #DA5A6A;' />
<polygon points='426.91,422.15 427.98,421.19 429.05,420.15 429.05,467.97 427.98,467.97 426.91,467.97 ' style='stroke-width: 0.38; stroke: #DA5B69; fill: #DA5B69;' />
<polygon points='429.05,420.15 430.12,419.03 431.18,417.87 431.18,467.97 430.12,467.97 429.05,467.97 ' style='stroke-width: 0.38; stroke: #DB5C68; fill: #DB5C68;' />
<polygon points='431.18,417.87 432.25,416.66 433.32,415.41 433.32,467.97 432.25,467.97 431.18,467.97 ' style='stroke-width: 0.38; stroke: #DC5D67; fill: #DC5D67;' />
<polygon points='433.32,415.41 434.39,414.14 435.45,412.87 435.45,467.97 434.39,467.97 433.32,467.97 ' style='stroke-width: 0.38; stroke: #DD5E66; fill: #DD5E66;' />
<polygon points='435.45,412.87 436.52,411.60 437.59,410.36 437.59,467.97 436.52,467.97 435.45,467.97 ' style='stroke-width: 0.38; stroke: #DE5F65; fill: #DE5F65;' />
<polygon points='437.59,410.36 438.66,409.16 438.66,467.97 437.59,467.97 ' style='stroke-width: 0.38; stroke: #DE6064; fill: #DE6064;' />
<polygon points='438.66,409.16 439.72,408.01 439.72,467.97 438.66,467.97 ' style='stroke-width: 0.38; stroke: #DE6164; fill: #DE6164;' />
<polygon points='439.72,408.01 440.79,406.94 441.86,405.96 441.86,467.97 440.79,467.97 439.72,467.97 ' style='stroke-width: 0.38; stroke: #DF6263; fill: #DF6263;' />
<polygon points='441.86,405.96 442.93,405.08 443.99,404.30 443.99,467.97 442.93,467.97 441.86,467.97 ' style='stroke-width: 0.38; stroke: #E06363; fill: #E06363;' />
<polygon points='443.99,404.30 445.06,403.65 446.13,403.16 446.13,467.97 445.06,467.97 443.99,467.97 ' style='stroke-width: 0.38; stroke: #E16462; fill: #E16462;' />
<polygon points='446.13,403.16 447.20,402.82 448.26,402.62 448.26,467.97 447.20,467.97 446.13,467.97 ' style='stroke-width: 0.38; stroke: #E26561; fill: #E26561;' />
<polygon points='448.26,402.62 449.33,402.58 450.40,402.71 450.40,467.97 449.33,467.97 448.26,467.97 ' style='stroke-width: 0.38; stroke: #E26660; fill: #E26660;' />
<polygon points='450.40,402.71 451.47,403.04 451.47,467.97 450.40,467.97 ' style='stroke-width: 0.38; stroke: #E3675F; fill: #E3675F;' />
<polygon points='451.47,403.04 452.53,403.54 452.53,467.97 451.47,467.97 ' style='stroke-width: 0.38; stroke: #E3685F; fill: #E3685F;' />
<polygon points='452.53,403.54 453.60,404.21 454.67,405.03 454.67,467.97 453.60,467.97 452.53,467.97 ' style='stroke-width: 0.38; stroke: #E4695E; fill: #E4695E;' />
<polygon points='454.67,405.03 455.74,406.02 456.80,407.20 456.80,467.97 455.74,467.97 454.67,467.97 ' style='stroke-width: 0.38; stroke: #E56A5D; fill: #E56A5D;' />
<polygon points='456.80,407.20 457.87,408.52 458.94,409.98 458.94,467.97 457.87,467.97 456.80,467.97 ' style='stroke-width: 0.38; stroke: #E56B5D; fill: #E56B5D;' />
<polygon points='458.94,409.98 460.01,411.56 461.07,413.26 461.07,467.97 460.01,467.97 458.94,467.97 ' style='stroke-width: 0.38; stroke: #E66C5C; fill: #E66C5C;' />
<polygon points='461.07,413.26 462.14,415.09 462.14,467.97 461.07,467.97 ' style='stroke-width: 0.38; stroke: #E76D5B; fill: #E76D5B;' />
<polygon points='462.14,415.09 463.21,417.01 463.21,467.97 462.14,467.97 ' style='stroke-width: 0.38; stroke: #E76E5B; fill: #E76E5B;' />
<polygon points='463.21,417.01 464.28,419.00 465.34,421.04 465.34,467.97 464.28,467.97 463.21,467.97 ' style='stroke-width: 0.38; stroke: #E76F5A; fill: #E76F5A;' />
<polygon points='465.34,421.04 466.41,423.14 467.48,425.28 467.48,467.97 466.41,467.97 465.34,467.97 ' style='stroke-width: 0.38; stroke: #E87059; fill: #E87059;' />
<polygon points='467.48,425.28 468.55,427.44 469.61,429.61 469.61,467.97 468.55,467.97 467.48,467.97 ' style='stroke-width: 0.38; stroke: #E97158; fill: #E97158;' />
<polygon points='469.61,429.61 470.68,431.76 471.75,433.91 471.75,467.97 470.68,467.97 469.61,467.97 ' style='stroke-width: 0.38; stroke: #E97257; fill: #E97257;' />
<polygon points='471.75,433.91 472.82,436.02 472.82,467.97 471.75,467.97 ' style='stroke-width: 0.38; stroke: #EA7357; fill: #EA7357;' />
<polygon points='472.82,436.02 473.88,438.08 473.88,467.97 472.82,467.97 ' style='stroke-width: 0.38; stroke: #EA7457; fill: #EA7457;' />
<polygon points='473.88,438.08 474.95,440.09 476.02,442.05 476.02,467.97 474.95,467.97 473.88,467.97 ' style='stroke-width: 0.38; stroke: #EB7556; fill: #EB7556;' />
<polygon points='476.02,442.05 477.09,443.95 478.15,445.77 478.15,467.97 477.09,467.97 476.02,467.97 ' style='stroke-width: 0.38; stroke: #EB7655; fill: #EB7655;' />
<polygon points='478.15,445.77 479.22,447.51 480.29,449.16 480.29,467.97 479.22,467.97 478.15,467.97 ' style='stroke-width: 0.38; stroke: #EC7754; fill: #EC7754;' />
<polygon points='480.29,449.16 481.36,450.74 481.36,467.97 480.29,467.97 ' style='stroke-width: 0.38; stroke: #ED7853; fill: #ED7853;' />
<polygon points='481.36,450.74 482.42,452.24 482.42,467.97 481.36,467.97 ' style='stroke-width: 0.38; stroke: #ED7953; fill: #ED7953;' />
<polygon points='482.42,452.24 483.49,453.65 484.56,454.95 484.56,467.97 483.49,467.97 482.42,467.97 ' style='stroke-width: 0.38; stroke: #ED7A52; fill: #ED7A52;' />
<polygon points='484.56,454.95 485.63,456.18 486.69,457.33 486.69,467.97 485.63,467.97 484.56,467.97 ' style='stroke-width: 0.38; stroke: #EE7B51; fill: #EE7B51;' />
<polygon points='486.69,457.33 487.76,458.39 488.83,459.38 488.83,467.97 487.76,467.97 486.69,467.97 ' style='stroke-width: 0.38; stroke: #EF7C51; fill: #EF7C51;' />
<polygon points='488.83,459.38 489.90,460.27 489.90,467.97 488.83,467.97 ' style='stroke-width: 0.38; stroke: #EF7D50; fill: #EF7D50;' />
<polygon points='489.90,460.27 490.97,461.10 490.97,467.97 489.90,467.97 ' style='stroke-width: 0.38; stroke: #EF7E50; fill: #EF7E50;' />
<polygon points='490.97,461.10 492.03,461.86 493.10,462.55 493.10,467.97 492.03,467.97 490.97,467.97 ' style='stroke-width: 0.38; stroke: #F07F4F; fill: #F07F4F;' />
<polygon points='493.10,462.55 494.17,463.18 495.24,463.74 495.24,467.97 494.17,467.97 493.10,467.97 ' style='stroke-width: 0.38; stroke: #F0804E; fill: #F0804E;' />
<polygon points='495.24,463.74 496.30,464.25 497.37,464.71 497.37,467.97 496.30,467.97 495.24,467.97 ' style='stroke-width: 0.38; stroke: #F1814D; fill: #F1814D;' />
<polygon points='497.37,464.71 498.44,465.12 498.44,467.97 497.37,467.97 ' style='stroke-width: 0.38; stroke: #F1824C; fill: #F1824C;' />
<polygon points='498.44,465.12 499.51,465.49 499.51,467.97 498.44,467.97 ' style='stroke-width: 0.38; stroke: #F1834C; fill: #F1834C;' />
<polygon points='499.51,465.49 500.57,465.81 501.64,466.10 501.64,467.97 500.57,467.97 499.51,467.97 ' style='stroke-width: 0.38; stroke: #F2844B; fill: #F2844B;' />
<polygon points='501.64,466.10 502.71,466.35 503.78,466.58 503.78,467.97 502.71,467.97 501.64,467.97 ' style='stroke-width: 0.38; stroke: #F3854B; fill: #F3854B;' />
<polygon points='503.78,466.58 504.84,466.78 504.84,467.97 503.78,467.97 ' style='stroke-width: 0.38; stroke: #F3864A; fill: #F3864A;' />
<polygon points='504.84,466.78 505.91,466.95 505.91,467.97 504.84,467.97 ' style='stroke-width: 0.38; stroke: #F3874A; fill: #F3874A;' />
<polygon points='505.91,466.95 505.91,467.97 ' style='stroke-width: 0.38; stroke: #F48849; fill: #F48849;' />
<polyline points='286.00,466.87 287.07,466.71 288.14,466.53 289.20,466.33 290.27,466.11 291.34,465.87 292.41,465.60 293.47,465.31 294.54,465.00 295.61,464.66 296.68,464.30 297.74,463.91 298.81,463.49 299.88,463.05 300.95,462.59 302.01,462.10 303.08,461.59 304.15,461.05 305.22,460.49 306.28,459.91 307.35,459.32 308.42,458.71 309.49,458.09 310.55,457.46 311.62,456.82 312.69,456.17 313.76,455.52 314.82,454.87 315.89,454.22 316.96,453.57 318.03,452.93 319.09,452.29 320.16,451.66 321.23,451.05 322.30,450.44 323.36,449.84 324.43,449.25 325.50,448.67 326.57,448.10 327.63,447.53 328.70,446.97 329.77,446.42 330.84,445.87 331.90,445.32 332.97,444.76 334.04,444.20 335.11,443.63 336.17,443.05 337.24,442.45 338.31,441.84 339.38,441.21 340.44,440.56 341.51,439.88 342.58,439.17 343.65,438.44 344.71,437.69 345.78,436.91 346.85,436.10 347.92,435.26 348.98,434.39 350.05,433.51 351.12,432.60 352.19,431.67 353.25,430.71 354.32,429.75 355.39,428.77 356.46,427.79 357.52,426.80 358.59,425.81 359.66,424.82 360.73,423.84 361.79,422.87 362.86,421.92 363.93,420.98 365.00,420.07 366.06,419.18 367.13,418.32 368.20,417.49 369.27,416.71 370.33,415.97 371.40,415.26 372.47,414.60 373.54,413.98 374.60,413.43 375.67,412.92 376.74,412.47 377.81,412.08 378.87,411.74 379.94,411.47 381.01,411.27 382.08,411.12 383.14,411.04 384.21,411.02 385.28,411.08 386.35,411.20 387.42,411.39 388.48,411.64 389.55,411.94 390.62,412.32 391.69,412.76 392.75,413.25 393.82,413.79 394.89,414.38 395.96,415.01 397.02,415.69 398.09,416.40 399.16,417.13 400.23,417.88 401.29,418.65 402.36,419.43 403.43,420.20 404.50,420.96 405.56,421.70 406.63,422.43 407.70,423.11 408.77,423.74 409.83,424.33 410.90,424.87 411.97,425.34 413.04,425.73 414.10,426.03 415.17,426.26 416.24,426.40 417.31,426.45 418.37,426.37 419.44,426.20 420.51,425.93 421.58,425.56 422.64,425.09 423.71,424.50 424.78,423.80 425.85,423.02 426.91,422.15 427.98,421.19 429.05,420.15 430.12,419.03 431.18,417.87 432.25,416.66 433.32,415.41 434.39,414.14 435.45,412.87 436.52,411.60 437.59,410.36 438.66,409.16 439.72,408.01 440.79,406.94 441.86,405.96 442.93,405.08 443.99,404.30 445.06,403.65 446.13,403.16 447.20,402.82 448.26,402.62 449.33,402.58 450.40,402.71 451.47,403.04 452.53,403.54 453.60,404.21 454.67,405.03 455.74,406.02 456.80,407.20 457.87,408.52 458.94,409.98 460.01,411.56 461.07,413.26 462.14,415.09 463.21,417.01 464.28,419.00 465.34,421.04 466.41,423.14 467.48,425.28 468.55,427.44 469.61,429.61 470.68,431.76 471.75,433.91 472.82,436.02 473.88,438.08 474.95,440.09 476.02,442.05 477.09,443.95 478.15,445.77 479.22,447.51 480.29,449.16 481.36,450.74 482.42,452.24 483.49,453.65 484.56,454.95 485.63,456.18 486.69,457.33 487.76,458.39 488.83,459.38 489.90,460.27 490.97,461.10 492.03,461.86 493.10,462.55 494.17,463.18 495.24,463.74 496.30,464.25 497.37,464.71 498.44,465.12 499.51,465.49 500.57,465.81 501.64,466.10 502.71,466.35 503.78,466.58 504.84,466.78 505.91,466.95 ' style='stroke-width: 1.07;' />
<polygon points='136.55,500.25 137.61,500.11 137.61,501.37 136.55,501.37 ' style='stroke-width: 0.38; stroke: #240691; fill: #240691;' />
<polygon points='137.61,500.11 138.68,499.96 138.68,501.37 137.61,501.37 ' style='stroke-width: 0.38; stroke: #250691; fill: #250691;' />
<polygon points='138.68,499.96 139.75,499.79 139.75,501.37 138.68,501.37 ' style='stroke-width: 0.38; stroke: #260591; fill: #260591;' />
<polygon points='139.75,499.79 140.82,499.61 140.82,501.37 139.75,501.37 ' style='stroke-width: 0.38; stroke: #270591; fill: #270591;' />
<polygon points='140.82,499.61 141.88,499.42 141.88,501.37 140.82,501.37 ' style='stroke-width: 0.38; stroke: #280592; fill: #280592;' />
<polygon points='141.88,499.42 142.95,499.22 142.95,501.37 141.88,501.37 ' style='stroke-width: 0.38; stroke: #290592; fill: #290592;' />
<polygon points='142.95,499.22 144.02,499.01 144.02,501.37 142.95,501.37 ' style='stroke-width: 0.38; stroke: #2A0593; fill: #2A0593;' />
<polygon points='144.02,499.01 145.09,498.78 145.09,501.37 144.02,501.37 ' style='stroke-width: 0.38; stroke: #2B0593; fill: #2B0593;' />
<polygon points='145.09,498.78 146.15,498.55 146.15,501.37 145.09,501.37 ' style='stroke-width: 0.38; stroke: #2C0594; fill: #2C0594;' />
<polygon points='146.15,498.55 147.22,498.30 147.22,501.37 146.15,501.37 ' style='stroke-width: 0.38; stroke: #2D0594; fill: #2D0594;' />
<polygon points='147.22,498.30 148.29,498.05 149.36,497.78 149.36,501.37 148.29,501.37 147.22,501.37 ' style='stroke-width: 0.38; stroke: #2E0595; fill: #2E0595;' />
<polygon points='149.36,497.78 150.42,497.51 150.42,501.37 149.36,501.37 ' style='stroke-width: 0.38; stroke: #2F0596; fill: #2F0596;' />
<polygon points='150.42,497.51 151.49,497.24 151.49,501.37 150.42,501.37 ' style='stroke-width: 0.38; stroke: #300596; fill: #300596;' />
<polygon points='151.49,497.24 152.56,496.96 152.56,501.37 151.49,501.37 ' style='stroke-width: 0.38; stroke: #310597; fill: #310597;' />
<polygon points='152.56,496.96 153.63,496.67 153.63,501.37 152.56,501.37 ' style='stroke-width: 0.38; stroke: #320597; fill: #320597;' />
<polygon points='153.63,496.67 154.69,496.39 154.69,501.37 153.63,501.37 ' style='stroke-width: 0.38; stroke: #330597; fill: #330597;' />
<polygon points='154.69,496.39 155.76,496.10 155.76,501.37 154.69,501.37 ' style='stroke-width: 0.38; stroke: #340597; fill: #340597;' />
<polygon points='155.76,496.10 156.83,495.82 156.83,501.37 155.76,501.37 ' style='stroke-width: 0.38; stroke: #350498; fill: #350498;' />
<polygon points='156.83,495.82 157.90,495.54 157.90,501.37 156.83,501.37 ' style='stroke-width: 0.38; stroke: #360498; fill: #360498;' />
<polygon points='157.90,495.54 158.96,495.27 160.03,495.00 160.03,501.37 158.96,501.37 157.90,501.37 ' style='stroke-width: 0.38; stroke: #370499; fill: #370499;' />
<polygon points='160.03,495.00 161.10,494.74 161.10,501.37 160.03,501.37 ' style='stroke-width: 0.38; stroke: #38049A; fill: #38049A;' />
<polygon points='161.10,494.74 162.17,494.49 162.17,501.37 161.10,501.37 ' style='stroke-width: 0.38; stroke: #39049A; fill: #39049A;' />
<polygon points='162.17,494.49 163.23,494.25 163.23,501.37 162.17,501.37 ' style='stroke-width: 0.38; stroke: #3A049A; fill: #3A049A;' />
<polygon points='163.23,494.25 164.30,494.02 164.30,501.37 163.23,501.37 ' style='stroke-width: 0.38; stroke: #3B049A; fill: #3B049A;' />
<polygon points='164.30,494.02 165.37,493.80 165.37,501.37 164.30,501.37 ' style='stroke-width: 0.38; stroke: #3C049B; fill: #3C049B;' />
<polygon points='165.37,493.80 166.44,493.60 166.44,501.37 165.37,501.37 ' style='stroke-width: 0.38; stroke: #3D049B; fill: #3D049B;' />
<polygon points='166.44,493.60 167.50,493.41 168.57,493.24 168.57,501.37 167.50,501.37 166.44,501.37 ' style='stroke-width: 0.38; stroke: #3E049C; fill: #3E049C;' />
<polygon points='168.57,493.24 169.64,493.08 169.64,501.37 168.57,501.37 ' style='stroke-width: 0.38; stroke: #3F049C; fill: #3F049C;' />
<polygon points='169.64,493.08 170.71,492.94 170.71,501.37 169.64,501.37 ' style='stroke-width: 0.38; stroke: #40049C; fill: #40049C;' />
<polygon points='170.71,492.94 171.77,492.82 171.77,501.37 170.71,501.37 ' style='stroke-width: 0.38; stroke: #41049D; fill: #41049D;' />
<polygon points='171.77,492.82 172.84,492.71 172.84,501.37 171.77,501.37 ' style='stroke-width: 0.38; stroke: #42049D; fill: #42049D;' />
<polygon points='172.84,492.71 173.91,492.62 174.98,492.54 174.98,501.37 173.91,501.37 172.84,501.37 ' style='stroke-width: 0.38; stroke: #43039E; fill: #43039E;' />
<polygon points='174.98,492.54 176.04,492.48 176.04,501.37 174.98,501.37 ' style='stroke-width: 0.38; stroke: #44039E; fill: #44039E;' />
<polygon points='176.04,492.48 177.11,492.44 177.11,501.37 176.04,501.37 ' style='stroke-width: 0.38; stroke: #45039E; fill: #45039E;' />
<polygon points='177.11,492.44 178.18,492.41 178.18,501.37 177.11,501.37 ' style='stroke-width: 0.38; stroke: #46039F; fill: #46039F;' />
<polygon points='178.18,492.41 179.25,492.40 179.25,501.37 178.18,501.37 ' style='stroke-width: 0.38; stroke: #47039F; fill: #47039F;' />
<polygon points='179.25,492.40 180.31,492.41 181.38,492.43 181.38,501.37 180.31,501.37 179.25,501.37 ' style='stroke-width: 0.38; stroke: #48039F; fill: #48039F;' />
<polygon points='181.38,492.43 182.45,492.47 182.45,501.37 181.38,501.37 ' style='stroke-width: 0.38; stroke: #4903A0; fill: #4903A0;' />
<polygon points='182.45,492.47 183.52,492.53 183.52,501.37 182.45,501.37 ' style='stroke-width: 0.38; stroke: #4A03A0; fill: #4A03A0;' />
<polygon points='183.52,492.53 184.59,492.60 185.65,492.68 185.65,501.37 184.59,501.37 183.52,501.37 ' style='stroke-width: 0.38; stroke: #4B03A1; fill: #4B03A1;' />
<polygon points='185.65,492.68 186.72,492.78 186.72,501.37 185.65,501.37 ' style='stroke-width: 0.38; stroke: #4C02A1; fill: #4C02A1;' />
<polygon points='186.72,492.78 187.79,492.90 187.79,501.37 186.72,501.37 ' style='stroke-width: 0.38; stroke: #4D02A1; fill: #4D02A1;' />
<polygon points='187.79,492.90 188.86,493.03 188.86,501.37 187.79,501.37 ' style='stroke-width: 0.38; stroke: #4E02A2; fill: #4E02A2;' />
<polygon points='188.86,493.03 189.92,493.17 189.92,501.37 188.86,501.37 ' style='stroke-width: 0.38; stroke: #4F02A2; fill: #4F02A2;' />
<polygon points='189.92,493.17 190.99,493.33 192.06,493.49 192.06,501.37 190.99,501.37 189.92,501.37 ' style='stroke-width: 0.38; stroke: #5002A2; fill: #5002A2;' />
<polygon points='192.06,493.49 193.13,493.67 193.13,501.37 192.06,501.37 ' style='stroke-width: 0.38; stroke: #5102A3; fill: #5102A3;' />
<polygon points='193.13,493.67 194.19,493.86 194.19,501.37 193.13,501.37 ' style='stroke-width: 0.38; stroke: #5202A3; fill: #5202A3;' />
<polygon points='194.19,493.86 195.26,494.05 195.26,501.37 194.19,501.37 ' style='stroke-width: 0.38; stroke: #5302A3; fill: #5302A3;' />
<polygon points='195.26,494.05 196.33,494.25 196.33,501.37 195.26,501.37 ' style='stroke-width: 0.38; stroke: #5402A3; fill: #5402A3;' />
<polygon points='196.33,494.25 197.40,494.45 198.46,494.65 198.46,501.37 197.40,501.37 196.33,501.37 ' style='stroke-width: 0.38; stroke: #5502A4; fill: #5502A4;' />
<polygon points='198.46,494.65 199.53,494.85 199.53,501.37 198.46,501.37 ' style='stroke-width: 0.38; stroke: #5601A4; fill: #5601A4;' />
<polygon points='199.53,494.85 200.60,495.05 200.60,501.37 199.53,501.37 ' style='stroke-width: 0.38; stroke: #5701A4; fill: #5701A4;' />
<polygon points='200.60,495.05 201.67,495.23 202.73,495.41 202.73,501.37 201.67,501.37 200.60,501.37 ' style='stroke-width: 0.38; stroke: #5801A4; fill: #5801A4;' />
<polygon points='202.73,495.41 203.80,495.58 203.80,501.37 202.73,501.37 ' style='stroke-width: 0.38; stroke: #5901A5; fill: #5901A5;' />
<polygon points='203.80,495.58 204.87,495.73 204.87,501.37 203.80,501.37 ' style='stroke-width: 0.38; stroke: #5A01A5; fill: #5A01A5;' />
<polygon points='204.87,495.73 205.94,495.86 207.00,495.96 207.00,501.37 205.94,501.37 204.87,501.37 ' style='stroke-width: 0.38; stroke: #5B01A5; fill: #5B01A5;' />
<polygon points='207.00,495.96 208.07,496.04 208.07,501.37 207.00,501.37 ' style='stroke-width: 0.38; stroke: #5C01A6; fill: #5C01A6;' />
<polygon points='208.07,496.04 209.14,496.10 209.14,501.37 208.07,501.37 ' style='stroke-width: 0.38; stroke: #5D01A6; fill: #5D01A6;' />
<polygon points='209.14,496.10 210.21,496.12 210.21,501.37 209.14,501.37 ' style='stroke-width: 0.38; stroke: #5E01A6; fill: #5E01A6;' />
<polygon points='210.21,496.12 211.27,496.10 211.27,501.37 210.21,501.37 ' style='stroke-width: 0.38; stroke: #5F01A6; fill: #5F01A6;' />
<polygon points='211.27,496.10 212.34,496.04 213.41,495.95 213.41,501.37 212.34,501.37 211.27,501.37 ' style='stroke-width: 0.38; stroke: #6001A6; fill: #6001A6;' />
<polygon points='213.41,495.95 214.48,495.82 214.48,501.37 213.41,501.37 ' style='stroke-width: 0.38; stroke: #6100A7; fill: #6100A7;' />
<polygon points='214.48,495.82 215.54,495.64 215.54,501.37 214.48,501.37 ' style='stroke-width: 0.38; stroke: #6200A7; fill: #6200A7;' />
<polygon points='215.54,495.64 216.61,495.41 217.68,495.13 217.68,501.37 216.61,501.37 215.54,501.37 ' style='stroke-width: 0.38; stroke: #6300A7; fill: #6300A7;' />
<polygon points='217.68,495.13 218.75,494.81 218.75,501.37 217.68,501.37 ' style='stroke-width: 0.38; stroke: #6400A7; fill: #6400A7;' />
<polygon points='218.75,494.81 219.81,494.44 219.81,501.37 218.75,501.37 ' style='stroke-width: 0.38; stroke: #6500A7; fill: #6500A7;' />
<polygon points='219.81,494.44 220.88,494.02 221.95,493.55 221.95,501.37 220.88,501.37 219.81,501.37 ' style='stroke-width: 0.38; stroke: #6600A7; fill: #6600A7;' />
<polygon points='221.95,493.55 223.02,493.03 223.02,501.37 221.95,501.37 ' style='stroke-width: 0.38; stroke: #6700A8; fill: #6700A8;' />
<polygon points='223.02,493.03 224.08,492.47 224.08,501.37 223.02,501.37 ' style='stroke-width: 0.38; stroke: #6800A8; fill: #6800A8;' />
<polygon points='224.08,492.47 225.15,491.86 226.22,491.21 226.22,501.37 225.15,501.37 224.08,501.37 ' style='stroke-width: 0.38; stroke: #6900A8; fill: #6900A8;' />
<polygon points='226.22,491.21 227.29,490.50 227.29,501.37 226.22,501.37 ' style='stroke-width: 0.38; stroke: #6A00A8; fill: #6A00A8;' />
<polygon points='227.29,490.50 228.35,489.76 228.35,501.37 227.29,501.37 ' style='stroke-width: 0.38; stroke: #6B00A8; fill: #6B00A8;' />
<polygon points='228.35,489.76 229.42,488.98 229.42,501.37 228.35,501.37 ' style='stroke-width: 0.38; stroke: #6C00A8; fill: #6C00A8;' />
<polygon points='229.42,488.98 230.49,488.17 230.49,501.37 229.42,501.37 ' style='stroke-width: 0.38; stroke: #6D00A8; fill: #6D00A8;' />
<polygon points='230.49,488.17 231.56,487.33 232.62,486.46 232.62,501.37 231.56,501.37 230.49,501.37 ' style='stroke-width: 0.38; stroke: #6E00A8; fill: #6E00A8;' />
<polygon points='232.62,486.46 233.69,485.55 233.69,501.37 232.62,501.37 ' style='stroke-width: 0.38; stroke: #6F00A8; fill: #6F00A8;' />
<polygon points='233.69,485.55 234.76,484.63 234.76,501.37 233.69,501.37 ' style='stroke-width: 0.38; stroke: #7000A8; fill: #7000A8;' />
<polygon points='234.76,484.63 235.83,483.69 236.89,482.74 236.89,501.37 235.83,501.37 234.76,501.37 ' style='stroke-width: 0.38; stroke: #7100A8; fill: #7100A8;' />
<polygon points='236.89,482.74 237.96,481.76 237.96,501.37 236.89,501.37 ' style='stroke-width: 0.38; stroke: #7201A8; fill: #7201A8;' />
<polygon points='237.96,481.76 239.03,480.78 239.03,501.37 237.96,501.37 ' style='stroke-width: 0.38; stroke: #7301A8; fill: #7301A8;' />
<polygon points='239.03,480.78 240.10,479.80 241.16,478.81 241.16,501.37 240.10,501.37 239.03,501.37 ' style='stroke-width: 0.38; stroke: #7401A8; fill: #7401A8;' />
<polygon points='241.16,478.81 242.23,477.82 242.23,501.37 241.16,501.37 ' style='stroke-width: 0.38; stroke: #7501A8; fill: #7501A8;' />
<polygon points='242.23,477.82 243.30,476.84 243.30,501.37 242.23,501.37 ' style='stroke-width: 0.38; stroke: #7601A8; fill: #7601A8;' />
<polygon points='243.30,476.84 244.37,475.86 245.43,474.89 245.43,501.37 244.37,501.37 243.30,501.37 ' style='stroke-width: 0.38; stroke: #7701A8; fill: #7701A8;' />
<polygon points='245.43,474.89 246.50,473.93 246.50,501.37 245.43,501.37 ' style='stroke-width: 0.38; stroke: #7801A8; fill: #7801A8;' />
<polygon points='246.50,473.93 247.57,472.98 247.57,501.37 246.50,501.37 ' style='stroke-width: 0.38; stroke: #7901A8; fill: #7901A8;' />
<polygon points='247.57,472.98 248.64,472.06 249.70,471.15 249.70,501.37 248.64,501.37 247.57,501.37 ' style='stroke-width: 0.38; stroke: #7A02A8; fill: #7A02A8;' />
<polygon points='249.70,471.15 250.77,470.27 250.77,501.37 249.70,501.37 ' style='stroke-width: 0.38; stroke: #7B02A8; fill: #7B02A8;' />
<polygon points='250.77,470.27 251.84,469.40 251.84,501.37 250.77,501.37 ' style='stroke-width: 0.38; stroke: #7C02A8; fill: #7C02A8;' />
<polygon points='251.84,469.40 252.91,468.57 253.97,467.77 253.97,501.37 252.91,501.37 251.84,501.37 ' style='stroke-width: 0.38; stroke: #7D03A8; fill: #7D03A8;' />
<polygon points='253.97,467.77 255.04,467.00 255.04,501.37 253.97,501.37 ' style='stroke-width: 0.38; stroke: #7E03A8; fill: #7E03A8;' />
<polygon points='255.04,467.00 256.11,466.27 256.11,501.37 255.04,501.37 ' style='stroke-width: 0.38; stroke: #7F03A8; fill: #7F03A8;' />
<polygon points='256.11,466.27 257.18,465.58 258.24,464.92 258.24,501.37 257.18,501.37 256.11,501.37 ' style='stroke-width: 0.38; stroke: #8004A8; fill: #8004A8;' />
<polygon points='258.24,464.92 259.31,464.32 259.31,501.37 258.24,501.37 ' style='stroke-width: 0.38; stroke: #8104A7; fill: #8104A7;' />
<polygon points='259.31,464.32 260.38,463.77 260.38,501.37 259.31,501.37 ' style='stroke-width: 0.38; stroke: #8204A7; fill: #8204A7;' />
<polygon points='260.38,463.77 261.45,463.27 262.51,462.82 262.51,501.37 261.45,501.37 260.38,501.37 ' style='stroke-width: 0.38; stroke: #8305A7; fill: #8305A7;' />
<polygon points='262.51,462.82 263.58,462.42 263.58,501.37 262.51,501.37 ' style='stroke-width: 0.38; stroke: #8405A7; fill: #8405A7;' />
<polygon points='263.58,462.42 264.65,462.09 264.65,501.37 263.58,501.37 ' style='stroke-width: 0.38; stroke: #8505A7; fill: #8505A7;' />
<polygon points='264.65,462.09 265.72,461.84 266.78,461.64 266.78,501.37 265.72,501.37 264.65,501.37 ' style='stroke-width: 0.38; stroke: #8606A6; fill: #8606A6;' />
<polygon points='266.78,461.64 267.85,461.51 268.92,461.44 268.92,501.37 267.85,501.37 266.78,501.37 ' style='stroke-width: 0.38; stroke: #8707A6; fill: #8707A6;' />
<polygon points='268.92,461.44 269.99,461.45 269.99,501.37 268.92,501.37 ' style='stroke-width: 0.38; stroke: #8808A6; fill: #8808A6;' />
<polygon points='269.99,461.45 271.05,461.53 271.05,501.37 269.99,501.37 ' style='stroke-width: 0.38; stroke: #8908A6; fill: #8908A6;' />
<polygon points='271.05,461.53 272.12,461.68 273.19,461.89 273.19,501.37 272.12,501.37 271.05,501.37 ' style='stroke-width: 0.38; stroke: #8A09A5; fill: #8A09A5;' />
<polygon points='273.19,461.89 274.26,462.16 274.26,501.37 273.19,501.37 ' style='stroke-width: 0.38; stroke: #8B0AA5; fill: #8B0AA5;' />
<polygon points='274.26,462.16 275.32,462.49 275.32,501.37 274.26,501.37 ' style='stroke-width: 0.38; stroke: #8C0AA5; fill: #8C0AA5;' />
<polygon points='275.32,462.49 276.39,462.89 277.46,463.34 277.46,501.37 276.39,501.37 275.32,501.37 ' style='stroke-width: 0.38; stroke: #8D0BA5; fill: #8D0BA5;' />
<polygon points='277.46,463.34 278.53,463.83 279.59,464.37 279.59,501.37 278.53,501.37 277.46,501.37 ' style='stroke-width: 0.38; stroke: #8E0CA4; fill: #8E0CA4;' />
<polygon points='279.59,464.37 280.66,464.93 280.66,501.37 279.59,501.37 ' style='stroke-width: 0.38; stroke: #8F0DA4; fill: #8F0DA4;' />
<polygon points='280.66,464.93 281.73,465.53 281.73,501.37 280.66,501.37 ' style='stroke-width: 0.38; stroke: #900DA4; fill: #900DA4;' />
<polygon points='281.73,465.53 282.80,466.15 283.87,466.77 283.87,501.37 282.80,501.37 281.73,501.37 ' style='stroke-width: 0.38; stroke: #910EA3; fill: #910EA3;' />
<polygon points='283.87,466.77 284.93,467.40 284.93,501.37 283.87,501.37 ' style='stroke-width: 0.38; stroke: #920FA3; fill: #920FA3;' />
<polygon points='284.93,467.40 286.00,468.03 286.00,501.37 284.93,501.37 ' style='stroke-width: 0.38; stroke: #930FA3; fill: #930FA3;' />
<polygon points='286.00,468.03 287.07,468.64 288.14,469.23 288.14,501.37 287.07,501.37 286.00,501.37 ' style='stroke-width: 0.38; stroke: #9410A2; fill: #9410A2;' />
<polygon points='288.14,469.23 289.20,469.79 289.20,501.37 288.14,501.37 ' style='stroke-width: 0.38; stroke: #9511A1; fill: #9511A1;' />
<polygon points='289.20,469.79 290.27,470.32 290.27,501.37 289.20,501.37 ' style='stroke-width: 0.38; stroke: #9512A1; fill: #9512A1;' />
<polygon points='290.27,470.32 291.34,470.80 291.34,501.37 290.27,501.37 ' style='stroke-width: 0.38; stroke: #9613A1; fill: #9613A1;' />
<polygon points='291.34,470.80 292.41,471.23 292.41,501.37 291.34,501.37 ' style='stroke-width: 0.38; stroke: #9713A1; fill: #9713A1;' />
<polygon points='292.41,471.23 293.47,471.59 294.54,471.90 294.54,501.37 293.47,501.37 292.41,501.37 ' style='stroke-width: 0.38; stroke: #9814A0; fill: #9814A0;' />
<polygon points='294.54,471.90 295.61,472.14 296.68,472.32 296.68,501.37 295.61,501.37 294.54,501.37 ' style='stroke-width: 0.38; stroke: #99159F; fill: #99159F;' />
<polygon points='296.68,472.32 297.74,472.41 297.74,501.37 296.68,501.37 ' style='stroke-width: 0.38; stroke: #9A169F; fill: #9A169F;' />
<polygon points='297.74,472.41 298.81,472.42 298.81,501.37 297.74,501.37 ' style='stroke-width: 0.38; stroke: #9B169F; fill: #9B169F;' />
<polygon points='298.81,472.42 299.88,472.35 300.95,472.20 300.95,501.37 299.88,501.37 298.81,501.37 ' style='stroke-width: 0.38; stroke: #9C179E; fill: #9C179E;' />
<polygon points='300.95,472.20 302.01,471.97 303.08,471.65 303.08,501.37 302.01,501.37 300.95,501.37 ' style='stroke-width: 0.38; stroke: #9D189D; fill: #9D189D;' />
<polygon points='303.08,471.65 304.15,471.24 304.15,501.37 303.08,501.37 ' style='stroke-width: 0.38; stroke: #9E199D; fill: #9E199D;' />
<polygon points='304.15,471.24 305.22,470.74 305.22,501.37 304.15,501.37 ' style='stroke-width: 0.38; stroke: #9F199D; fill: #9F199D;' />
<polygon points='305.22,470.74 306.28,470.17 307.35,469.52 307.35,501.37 306.28,501.37 305.22,501.37 ' style='stroke-width: 0.38; stroke: #A01A9C; fill: #A01A9C;' />
<polygon points='307.35,469.52 308.42,468.78 308.42,501.37 307.35,501.37 ' style='stroke-width: 0.38; stroke: #A11B9B; fill: #A11B9B;' />
<polygon points='308.42,468.78 309.49,467.95 309.49,501.37 308.42,501.37 ' style='stroke-width: 0.38; stroke: #A11C9B; fill: #A11C9B;' />
<polygon points='309.49,467.95 310.55,467.04 311.62,466.07 311.62,501.37 310.55,501.37 309.49,501.37 ' style='stroke-width: 0.38; stroke: #A21D9A; fill: #A21D9A;' />
<polygon points='311.62,466.07 312.69,465.02 312.69,501.37 311.62,501.37 ' style='stroke-width: 0.38; stroke: #A31E9A; fill: #A31E9A;' />
<polygon points='312.69,465.02 313.76,463.91 313.76,501.37 312.69,501.37 ' style='stroke-width: 0.38; stroke: #A41E9A; fill: #A41E9A;' />
<polygon points='313.76,463.91 314.82,462.73 315.89,461.49 315.89,501.37 314.82,501.37 313.76,501.37 ' style='stroke-width: 0.38; stroke: #A51F99; fill: #A51F99;' />
<polygon points='315.89,461.49 316.96,460.20 318.03,458.86 318.03,501.37 316.96,501.37 315.89,501.37 ' style='stroke-width: 0.38; stroke: #A62098; fill: #A62098;' />
<polygon points='318.03,458.86 319.09,457.49 320.16,456.07 320.16,501.37 319.09,501.37 318.03,501.37 ' style='stroke-width: 0.38; stroke: #A72197; fill: #A72197;' />
<polygon points='320.16,456.07 321.23,454.64 321.23,501.37 320.16,501.37 ' style='stroke-width: 0.38; stroke: #A82296; fill: #A82296;' />
<polygon points='321.23,454.64 322.30,453.19 322.30,501.37 321.23,501.37 ' style='stroke-width: 0.38; stroke: #A92296; fill: #A92296;' />
<polygon points='322.30,453.19 323.36,451.74 324.43,450.28 324.43,501.37 323.36,501.37 322.30,501.37 ' style='stroke-width: 0.38; stroke: #AA2395; fill: #AA2395;' />
<polygon points='324.43,450.28 325.50,448.85 325.50,501.37 324.43,501.37 ' style='stroke-width: 0.38; stroke: #AB2494; fill: #AB2494;' />
<polygon points='325.50,448.85 326.57,447.44 326.57,501.37 325.50,501.37 ' style='stroke-width: 0.38; stroke: #AB2594; fill: #AB2594;' />
<polygon points='326.57,447.44 327.63,446.06 328.70,444.73 328.70,501.37 327.63,501.37 326.57,501.37 ' style='stroke-width: 0.38; stroke: #AC2694; fill: #AC2694;' />
<polygon points='328.70,444.73 329.77,443.45 330.84,442.25 330.84,501.37 329.77,501.37 328.70,501.37 ' style='stroke-width: 0.38; stroke: #AD2793; fill: #AD2793;' />
<polygon points='330.84,442.25 331.90,441.12 331.90,501.37 330.84,501.37 ' style='stroke-width: 0.38; stroke: #AE2892; fill: #AE2892;' />
<polygon points='331.90,441.12 332.97,440.08 332.97,501.37 331.90,501.37 ' style='stroke-width: 0.38; stroke: #AF2892; fill: #AF2892;' />
<polygon points='332.97,440.08 334.04,439.12 335.11,438.25 335.11,501.37 334.04,501.37 332.97,501.37 ' style='stroke-width: 0.38; stroke: #B02991; fill: #B02991;' />
<polygon points='335.11,438.25 336.17,437.50 337.24,436.87 337.24,501.37 336.17,501.37 335.11,501.37 ' style='stroke-width: 0.38; stroke: #B12A90; fill: #B12A90;' />
<polygon points='337.24,436.87 338.31,436.34 339.38,435.92 339.38,501.37 338.31,501.37 337.24,501.37 ' style='stroke-width: 0.38; stroke: #B22B8F; fill: #B22B8F;' />
<polygon points='339.38,435.92 340.44,435.60 340.44,501.37 339.38,501.37 ' style='stroke-width: 0.38; stroke: #B32C8E; fill: #B32C8E;' />
<polygon points='340.44,435.60 341.51,435.41 341.51,501.37 340.44,501.37 ' style='stroke-width: 0.38; stroke: #B32D8E; fill: #B32D8E;' />
<polygon points='341.51,435.41 342.58,435.34 343.65,435.36 343.65,501.37 342.58,501.37 341.51,501.37 ' style='stroke-width: 0.38; stroke: #B42E8D; fill: #B42E8D;' />
<polygon points='343.65,435.36 344.71,435.47 345.78,435.68 345.78,501.37 344.71,501.37 343.65,501.37 ' style='stroke-width: 0.38; stroke: #B52F8C; fill: #B52F8C;' />
<polygon points='345.78,435.68 346.85,435.97 347.92,436.35 347.92,501.37 346.85,501.37 345.78,501.37 ' style='stroke-width: 0.38; stroke: #B6308B; fill: #B6308B;' />
<polygon points='347.92,436.35 348.98,436.80 350.05,437.30 350.05,501.37 348.98,501.37 347.92,501.37 ' style='stroke-width: 0.38; stroke: #B7318A; fill: #B7318A;' />
<polygon points='350.05,437.30 351.12,437.85 351.12,501.37 350.05,501.37 ' style='stroke-width: 0.38; stroke: #B83289; fill: #B83289;' />
<polygon points='351.12,437.85 352.19,438.45 352.19,501.37 351.12,501.37 ' style='stroke-width: 0.38; stroke: #B93289; fill: #B93289;' />
<polygon points='352.19,438.45 353.25,439.09 354.32,439.76 354.32,501.37 353.25,501.37 352.19,501.37 ' style='stroke-width: 0.38; stroke: #BA3388; fill: #BA3388;' />
<polygon points='354.32,439.76 355.39,440.45 356.46,441.15 356.46,501.37 355.39,501.37 354.32,501.37 ' style='stroke-width: 0.38; stroke: #BB3488; fill: #BB3488;' />
<polygon points='356.46,441.15 357.52,441.87 357.52,501.37 356.46,501.37 ' style='stroke-width: 0.38; stroke: #BC3587; fill: #BC3587;' />
<polygon points='357.52,441.87 358.59,442.60 358.59,501.37 357.52,501.37 ' style='stroke-width: 0.38; stroke: #BC3687; fill: #BC3687;' />
<polygon points='358.59,442.60 359.66,443.33 360.73,444.07 360.73,501.37 359.66,501.37 358.59,501.37 ' style='stroke-width: 0.38; stroke: #BD3786; fill: #BD3786;' />
<polygon points='360.73,444.07 361.79,444.81 362.86,445.55 362.86,501.37 361.79,501.37 360.73,501.37 ' style='stroke-width: 0.38; stroke: #BE3885; fill: #BE3885;' />
<polygon points='362.86,445.55 363.93,446.31 365.00,447.08 365.00,501.37 363.93,501.37 362.86,501.37 ' style='stroke-width: 0.38; stroke: #BF3984; fill: #BF3984;' />
<polygon points='365.00,447.08 366.06,447.86 367.13,448.65 367.13,501.37 366.06,501.37 365.00,501.37 ' style='stroke-width: 0.38; stroke: #C03A83; fill: #C03A83;' />
<polygon points='367.13,448.65 368.20,449.46 369.27,450.31 369.27,501.37 368.20,501.37 367.13,501.37 ' style='stroke-width: 0.38; stroke: #C13B82; fill: #C13B82;' />
<polygon points='369.27,450.31 370.33,451.18 371.40,452.09 371.40,501.37 370.33,501.37 369.27,501.37 ' style='stroke-width: 0.38; stroke: #C23C81; fill: #C23C81;' />
<polygon points='371.40,452.09 372.47,453.03 373.54,454.02 373.54,501.37 372.47,501.37 371.40,501.37 ' style='stroke-width: 0.38; stroke: #C33D80; fill: #C33D80;' />
<polygon points='373.54,454.02 374.60,455.05 374.60,501.37 373.54,501.37 ' style='stroke-width: 0.38; stroke: #C43E7F; fill: #C43E7F;' />
<polygon points='374.60,455.05 375.67,456.14 375.67,501.37 374.60,501.37 ' style='stroke-width: 0.38; stroke: #C43F7F; fill: #C43F7F;' />
<polygon points='375.67,456.14 376.74,457.27 377.81,458.44 377.81,501.37 376.74,501.37 375.67,501.37 ' style='stroke-width: 0.38; stroke: #C5407E; fill: #C5407E;' />
<polygon points='377.81,458.44 378.87,459.66 379.94,460.94 379.94,501.37 378.87,501.37 377.81,501.37 ' style='stroke-width: 0.38; stroke: #C6417D; fill: #C6417D;' />
<polygon points='379.94,460.94 381.01,462.27 382.08,463.63 382.08,501.37 381.01,501.37 379.94,501.37 ' style='stroke-width: 0.38; stroke: #C7427C; fill: #C7427C;' />
<polygon points='382.08,463.63 383.14,465.04 384.21,466.47 384.21,501.37 383.14,501.37 382.08,501.37 ' style='stroke-width: 0.38; stroke: #C8437B; fill: #C8437B;' />
<polygon points='384.21,466.47 385.28,467.94 386.35,469.44 386.35,501.37 385.28,501.37 384.21,501.37 ' style='stroke-width: 0.38; stroke: #C9447A; fill: #C9447A;' />
<polygon points='386.35,469.44 387.42,470.94 388.48,472.46 388.48,501.37 387.42,501.37 386.35,501.37 ' style='stroke-width: 0.38; stroke: #CA457A; fill: #CA457A;' />
<polygon points='388.48,472.46 389.55,473.99 390.62,475.51 390.62,501.37 389.55,501.37 388.48,501.37 ' style='stroke-width: 0.38; stroke: #CB4679; fill: #CB4679;' />
<polygon points='390.62,475.51 391.69,477.02 391.69,501.37 390.62,501.37 ' style='stroke-width: 0.38; stroke: #CC4778; fill: #CC4778;' />
<polygon points='391.69,477.02 392.75,478.51 392.75,501.37 391.69,501.37 ' style='stroke-width: 0.38; stroke: #CC4878; fill: #CC4878;' />
<polygon points='392.75,478.51 393.82,479.98 393.82,501.37 392.75,501.37 ' style='stroke-width: 0.38; stroke: #CC4877; fill: #CC4877;' />
<polygon points='393.82,479.98 394.89,481.42 394.89,501.37 393.82,501.37 ' style='stroke-width: 0.38; stroke: #CC4977; fill: #CC4977;' />
<polygon points='394.89,481.42 395.96,482.82 397.02,484.18 397.02,501.37 395.96,501.37 394.89,501.37 ' style='stroke-width: 0.38; stroke: #CD4A76; fill: #CD4A76;' />
<polygon points='397.02,484.18 398.09,485.49 399.16,486.75 399.16,501.37 398.09,501.37 397.02,501.37 ' style='stroke-width: 0.38; stroke: #CE4B75; fill: #CE4B75;' />
<polygon points='399.16,486.75 400.23,487.97 401.29,489.12 401.29,501.37 400.23,501.37 399.16,501.37 ' style='stroke-width: 0.38; stroke: #CF4C74; fill: #CF4C74;' />
<polygon points='401.29,489.12 402.36,490.20 403.43,491.23 403.43,501.37 402.36,501.37 401.29,501.37 ' style='stroke-width: 0.38; stroke: #D04D73; fill: #D04D73;' />
<polygon points='403.43,491.23 404.50,492.20 405.56,493.11 405.56,501.37 404.50,501.37 403.43,501.37 ' style='stroke-width: 0.38; stroke: #D14E72; fill: #D14E72;' />
<polygon points='405.56,493.11 406.63,493.95 407.70,494.73 407.70,501.37 406.63,501.37 405.56,501.37 ' style='stroke-width: 0.38; stroke: #D24F71; fill: #D24F71;' />
<polygon points='407.70,494.73 408.77,495.44 408.77,501.37 407.70,501.37 ' style='stroke-width: 0.38; stroke: #D35071; fill: #D35071;' />
<polygon points='408.77,495.44 409.83,496.10 409.83,501.37 408.77,501.37 ' style='stroke-width: 0.38; stroke: #D35171; fill: #D35171;' />
<polygon points='409.83,496.10 410.90,496.71 411.97,497.27 411.97,501.37 410.90,501.37 409.83,501.37 ' style='stroke-width: 0.38; stroke: #D45270; fill: #D45270;' />
<polygon points='411.97,497.27 413.04,497.76 414.10,498.21 414.10,501.37 413.04,501.37 411.97,501.37 ' style='stroke-width: 0.38; stroke: #D5536F; fill: #D5536F;' />
<polygon points='414.10,498.21 415.17,498.61 416.24,498.97 416.24,501.37 415.17,501.37 414.10,501.37 ' style='stroke-width: 0.38; stroke: #D5546E; fill: #D5546E;' />
<polygon points='416.24,498.97 417.31,499.30 418.37,499.58 418.37,501.37 417.31,501.37 416.24,501.37 ' style='stroke-width: 0.38; stroke: #D6556D; fill: #D6556D;' />
<polygon points='418.37,499.58 419.44,499.83 420.51,500.05 420.51,501.37 419.44,501.37 418.37,501.37 ' style='stroke-width: 0.38; stroke: #D7566C; fill: #D7566C;' />
<polygon points='420.51,500.05 421.58,500.25 421.58,501.37 420.51,501.37 ' style='stroke-width: 0.38; stroke: #D8576B; fill: #D8576B;' />
<polyline points='136.55,500.25 137.61,500.11 138.68,499.96 139.75,499.79 140.82,499.61 141.88,499.42 142.95,499.22 144.02,499.01 145.09,498.78 146.15,498.55 147.22,498.30 148.29,498.05 149.36,497.78 150.42,497.51 151.49,497.24 152.56,496.96 153.63,496.67 154.69,496.39 155.76,496.10 156.83,495.82 157.90,495.54 158.96,495.27 160.03,495.00 161.10,494.74 162.17,494.49 163.23,494.25 164.30,494.02 165.37,493.80 166.44,493.60 167.50,493.41 168.57,493.24 169.64,493.08 170.71,492.94 171.77,492.82 172.84,492.71 173.91,492.62 174.98,492.54 176.04,492.48 177.11,492.44 178.18,492.41 179.25,492.40 180.31,492.41 181.38,492.43 182.45,492.47 183.52,492.53 184.59,492.60 185.65,492.68 186.72,492.78 187.79,492.90 188.86,493.03 189.92,493.17 190.99,493.33 192.06,493.49 193.13,493.67 194.19,493.86 195.26,494.05 196.33,494.25 197.40,494.45 198.46,494.65 199.53,494.85 200.60,495.05 201.67,495.23 202.73,495.41 203.80,495.58 204.87,495.73 205.94,495.86 207.00,495.96 208.07,496.04 209.14,496.10 210.21,496.12 211.27,496.10 212.34,496.04 213.41,495.95 214.48,495.82 215.54,495.64 216.61,495.41 217.68,495.13 218.75,494.81 219.81,494.44 220.88,494.02 221.95,493.55 223.02,493.03 224.08,492.47 225.15,491.86 226.22,491.21 227.29,490.50 228.35,489.76 229.42,488.98 230.49,488.17 231.56,487.33 232.62,486.46 233.69,485.55 234.76,484.63 235.83,483.69 236.89,482.74 237.96,481.76 239.03,480.78 240.10,479.80 241.16,478.81 242.23,477.82 243.30,476.84 244.37,475.86 245.43,474.89 246.50,473.93 247.57,472.98 248.64,472.06 249.70,471.15 250.77,470.27 251.84,469.40 252.91,468.57 253.97,467.77 255.04,467.00 256.11,466.27 257.18,465.58 258.24,464.92 259.31,464.32 260.38,463.77 261.45,463.27 262.51,462.82 263.58,462.42 264.65,462.09 265.72,461.84 266.78,461.64 267.85,461.51 268.92,461.44 269.99,461.45 271.05,461.53 272.12,461.68 273.19,461.89 274.26,462.16 275.32,462.49 276.39,462.89 277.46,463.34 278.53,463.83 279.59,464.37 280.66,464.93 281.73,465.53 282.80,466.15 283.87,466.77 284.93,467.40 286.00,468.03 287.07,468.64 288.14,469.23 289.20,469.79 290.27,470.32 291.34,470.80 292.41,471.23 293.47,471.59 294.54,471.90 295.61,472.14 296.68,472.32 297.74,472.41 298.81,472.42 299.88,472.35 300.95,472.20 302.01,471.97 303.08,471.65 304.15,471.24 305.22,470.74 306.28,470.17 307.35,469.52 308.42,468.78 309.49,467.95 310.55,467.04 311.62,466.07 312.69,465.02 313.76,463.91 314.82,462.73 315.89,461.49 316.96,460.20 318.03,458.86 319.09,457.49 320.16,456.07 321.23,454.64 322.30,453.19 323.36,451.74 324.43,450.28 325.50,448.85 326.57,447.44 327.63,446.06 328.70,444.73 329.77,443.45 330.84,442.25 331.90,441.12 332.97,440.08 334.04,439.12 335.11,438.25 336.17,437.50 337.24,436.87 338.31,436.34 339.38,435.92 340.44,435.60 341.51,435.41 342.58,435.34 343.65,435.36 344.71,435.47 345.78,435.68 346.85,435.97 347.92,436.35 348.98,436.80 350.05,437.30 351.12,437.85 352.19,438.45 353.25,439.09 354.32,439.76 355.39,440.45 356.46,441.15 357.52,441.87 358.59,442.60 359.66,443.33 360.73,444.07 361.79,444.81 362.86,445.55 363.93,446.31 365.00,447.08 366.06,447.86 367.13,448.65 368.20,449.46 369.27,450.31 370.33,451.18 371.40,452.09 372.47,453.03 373.54,454.02 374.60,455.05 375.67,456.14 376.74,457.27 377.81,458.44 378.87,459.66 379.94,460.94 381.01,462.27 382.08,463.63 383.14,465.04 384.21,466.47 385.28,467.94 386.35,469.44 387.42,470.94 388.48,472.46 389.55,473.99 390.62,475.51 391.69,477.02 392.75,478.51 393.82,479.98 394.89,481.42 395.96,482.82 397.02,484.18 398.09,485.49 399.16,486.75 400.23,487.97 401.29,489.12 402.36,490.20 403.43,491.23 404.50,492.20 405.56,493.11 406.63,493.95 407.70,494.73 408.77,495.44 409.83,496.10 410.90,496.71 411.97,497.27 413.04,497.76 414.10,498.21 415.17,498.61 416.24,498.97 417.31,499.30 418.37,499.58 419.44,499.83 420.51,500.05 421.58,500.25 ' style='stroke-width: 1.07;' />
</g>
<g clip-path='url(#cpMC4wMHw3MjAuMDB8MC4wMHw1NzYuMDA=)'>
<text x='87.19' y='505.48' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='43.48px' lengthAdjust='spacingAndGlyphs'>December</text>
<text x='87.19' y='472.08' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='43.48px' lengthAdjust='spacingAndGlyphs'>November</text>
<text x='87.19' y='438.68' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='33.54px' lengthAdjust='spacingAndGlyphs'>October</text>
<text x='87.19' y='405.28' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='46.11px' lengthAdjust='spacingAndGlyphs'>September</text>
<text x='87.19' y='371.87' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='29.35px' lengthAdjust='spacingAndGlyphs'>August</text>
<text x='87.19' y='338.47' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='16.77px' lengthAdjust='spacingAndGlyphs'>July</text>
<text x='87.19' y='305.07' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='20.44px' lengthAdjust='spacingAndGlyphs'>June</text>
<text x='87.19' y='271.66' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='17.81px' lengthAdjust='spacingAndGlyphs'>May</text>
<text x='87.19' y='238.26' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='18.86px' lengthAdjust='spacingAndGlyphs'>April</text>
<text x='87.19' y='204.86' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='26.19px' lengthAdjust='spacingAndGlyphs'>March</text>
<text x='87.19' y='171.45' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='37.72px' lengthAdjust='spacingAndGlyphs'>February</text>
<text x='87.19' y='138.05' text-anchor='end' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='33.54px' lengthAdjust='spacingAndGlyphs'>January</text>
<text x='196.37' y='532.51' text-anchor='middle' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='5.24px' lengthAdjust='spacingAndGlyphs'>0</text>
<text x='318.97' y='532.51' text-anchor='middle' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='10.48px' lengthAdjust='spacingAndGlyphs'>25</text>
<text x='441.58' y='532.51' text-anchor='middle' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='10.48px' lengthAdjust='spacingAndGlyphs'>50</text>
<text x='564.18' y='532.51' text-anchor='middle' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='10.48px' lengthAdjust='spacingAndGlyphs'>75</text>
<text x='686.78' y='532.51' text-anchor='middle' style='font-size: 11.50px; fill: #4D4D4D; font-family: Arial Narrow;' textLength='15.72px' lengthAdjust='spacingAndGlyphs'>100</text>
<text x='690.11' y='544.23' text-anchor='end' style='font-size: 9.00px; font-family: Arial Narrow;' textLength='72.47px' lengthAdjust='spacingAndGlyphs'>Mean Temperature [F]</text>
<text transform='translate(36.33,56.53) rotate(-90)' text-anchor='end' style='font-size: 9.00px; font-family: Arial Narrow;' textLength='20.51px' lengthAdjust='spacingAndGlyphs'>Month</text>
<text x='90.06' y='42.78' style='font-size: 18.00px; font-weight: bold; font-family: Arial Narrow;' textLength='318.17px' lengthAdjust='spacingAndGlyphs'>Option Implied Price Distribution (Illustrative)</text>
</g>
</svg>
