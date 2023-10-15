<svelte:head>
    <title>About Us</title>
</svelte:head>

<script>
    import Button from '$lib/Button.svelte';
</script>

<div class="bg-image"></div>

<div class="content">
    <div class="title">
        About Us
    </div>
    <br>
    We are a group of 18 officers and over 100 student volunteers, who have operated since 2018. 
    <br><br>

    <img src="images/team03.jpg" alt="SO@VT Team">

    <p>Our <b>mission</b> is to foster competitive Science Olympiad in the heart of Southwest Virginia, 
        leading to life-changing STEM experiences. We do so through two priorities:</p>
    <br>
    <div class="emphasis"><span>Hosting high-quality tournaments,</span> facilitated by dedicated Virginia Tech students in STEM</div>
    <br>
    
    <div class="emphasis"><span>Pursuing outreach initiatives</span> to schools and new teams, locally and online</div>

    <br>

    <br>

    We welcome you to connect with us! Please see our <a href="/contact" class="button">Contact</a> page.

</div>



<style>

    * {
        font-family: 'Montserrat', sans-serif;
    }

    .bg-image {
        /* The image used */
        background-image: url("/images/fall_burruss.jpg");
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

    .title {
        text-align: center;
        font-size: 3rem;

    }
    .content {

        width: 70vw;

        padding: 3rem;

        background-color: rgba(255, 255, 255, 0.9);
        border-radius: 5rem;

        text-align: center;
        font-size: 1rem;
        margin-top: 10rem;
        margin-left: auto;
        margin-right: auto;
    }

    .emphasis {
        font-size: 1.5rem;
    }

    span {
        color: rgb(255, 102, 0);
    }

    img {
        width:50rem;
        max-width: 75vw;
        margin-left: auto;
        margin-right: auto;
        display: block;
    }



</style>





