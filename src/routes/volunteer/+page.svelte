

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
    We have a few hundred volunteers come out each year to help with running events, scoring events, handing out awards, 
    and just helping students get around campus. If you need volunteer hours, this is the perfect place to come. 
    Our tournament lasts all day, so you can knock out a bunch of your volunteer hours at once. If you’d like to volunteer please fill out the following form:

    <br><br>
    <Button text="Volunteer Form" url="https://docs.google.com/forms/d/e/1FAIpQLScVRZ-NJZpJIPt5aZ97u_-yKpkOGzL_E8GgBop9ArfNn-2DOQ/viewform"/>
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

        width: 75vw;

        padding: 3rem;

        background-color: rgba(255, 255, 255, 0.9);
        border-radius: 5rem;

        text-align: center;
        font-size: 1rem;
        margin-top: 10rem;
        margin-left: auto;
        margin-right: auto;
    }
</style>





