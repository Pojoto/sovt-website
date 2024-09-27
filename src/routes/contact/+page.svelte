<svelte:head>
    <title>Contact</title>
</svelte:head>

<script>
    import Button from '$lib/Button.svelte';
</script>

<div class="bg-image"></div>

<div class="content">

    <div class="title">Contact Us</div>

    <!-- <a href="mailto:scienceolympiadvt@gmail.com"> -->
        <div class="contact-line">
            <img src="images/mail.png" alt="email icon">
            <div class="text">scienceolympiadvt@gmail.com</div>
        </div>
    <!-- </a> -->

    <a href="https://www.instagram.com/scienceolympiadatvt/?hl=en">
        <div class="contact-line">
            <img src="images/instagram.png" alt="instagram logo">
            <div class="text">@scienceolympiadatvt</div>
        </div>
    </a>

    <a href="https://scioly.org/forums/viewtopic.php?t=28758">
        <div class="contact-line">
            <img src="images/flask.png" alt="science icon">
            <div class="text">Scioly.org Forum</div>
        </div>
    </a>

    <a href="https://gobblerconnect.vt.edu/organization/sovt">
        <div class="contact-line">
            <img src="images/search.png" alt="search icon">
            <div class="text">Our Gobbler Connect</div>
        </div>
    </a>

    <br><br>

    <Button text="Join Email List!" url="https://forms.gle/PJNkzkCbvuk3Hzah8"/>

    
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

        position:absolute;

        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);

        text-align: center;
        font-family: 'Montserrat', sans-serif;

    }

    .title {
        text-align: center;
        font-size: 3rem;

    }

    .contact-line {
        text-align: left;
        margin-left: 5rem;
        line-height: 5rem;
        display: flex;
        margin-top: 2rem;
    }

    .contact-line:hover img{
        filter: hue-rotate(100deg);
    }

    img {
        width: 5rem;
        height: 5rem;
        display: block;
        margin-right: 1rem;

        transition: 0.3s;
    }

    a {
        text-decoration: none;
        color: black;
    }


    @media (max-width: 1000px) {
        .contact-line {
            flex-direction: column;
            margin-left: 0rem;
            text-align: center;
            align-items: center;
        }

        .content {
            margin-top: 15rem;
        }
    }





</style>
