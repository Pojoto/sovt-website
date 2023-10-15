<svelte:head>
    <title>Contact</title>
</svelte:head>

<div class="bg-image"></div>

<div class="content">
    Email us at
    <br>
    <h1 style="color:orange">scienceolympiadvt@gmail.com</h1>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    Find us on Instagram
    <br>
    <br>
    <a href="https://www.instagram.com/scienceolympiadatvt/?hl=en"><img src="images/instagram.png" alt="instagram logo"></a>

    <br>

    <br>
    <a href = "https://gobblerconnect.vt.edu/organization/sovt" target = "_blank">Our Gobbler Connect</a>

    
</div>


<style>

    .bg-image {
        /* The image used */
        background-image: url("/images/pylons.jpg");
        z-index: -1;
        /* Full height */
        /* height: 100vh; 
        width: 100vw; */
        min-height: 100vh;
        min-width: 100vw;
        position:fixed;
        top:0;
        left:0;
        
        /* Center and scale the image nicely */
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        /* background-repeat: no-repeat;
        background-attachment: fixed;  
        background-size: cover; */
    }

    .content {

        background-color: rgba(255,255,255,0.9);

        border-radius: 5rem;

        padding: 5rem;

        width: 50vw;

        margin-top: 5rem;
        
        word-wrap: break-word;

        position:absolute;

        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);

        text-align: center;
        font-family: 'Montserrat', sans-serif;

    }

    img {
        width: 10rem;
    }




</style>