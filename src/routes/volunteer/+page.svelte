<svelte:head>
    <title>Volunteer</title>
</svelte:head>

<script>
    import Button from '$lib/Button.svelte';
</script>

<div class="bg-image"></div>

<div class="content">
    <div class="title">
        Volunteer!
    </div>
    <br>
    SO@VT Regionals & Invitationals would be impossible without the amazing work of our volunteers each tournament. 
    <br><br>

    We have 100-200 volunteers come out each year to serve our student competitors. Roles include:

    <br>

    <ul>
        <li>Test writing</li>
        <li>Build event supervising</li>

        <li>Test/lab event supervising</li>

        <li>Grading</li>

        <li>General helpers (registration, campus guides, clean up, etc.)</li>

    </ul>

    <br>
    <br>

    If you need service hours, being part of tournament day is an immensely fulfilling and fun way to serve. 
    <br>
    We welcome you to volunteer either for the full day or for a few hours. Please fill out the following 
    form to stay in touch with us:
    <br><br>
    <Button text="Volunteer Form" url="https://forms.gle/zm3VTkN4QrfjiH9G6"/>
</div>



<style>

    * {
        font-family: 'Montserrat', sans-serif;
    }

    .bg-image {
        /* The image used */
        background-image: url("/images/campus2.jpg");
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

    ul {
        display: inline-block;
        text-align: left;
        color: rgb(161, 105, 0);
    }


</style>





