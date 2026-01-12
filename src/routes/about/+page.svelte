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
    We are a group of 20 officers and over 100 student volunteers, who have operated since 2018. 

    <div class="section">
        <h2>Exec</h2>
        <div class="officer-container">
            <div class="officer">
                <img src="images/photoshoot_25/ThiviyaKaruppasamy.jpg" alt="Thiviya Karuppasamy" style="border: 5px solid #076c9b;">
                <p>Thiviya Karuppasamy</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/JakeOBrien.jpg" alt="Jake O' Brien" style="border: 5px solid #076c9b;">
                <p>Jake O' Brien</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/ReaganNguyen.png" alt="Reagan Nguyen" style="border: 5px solid #076c9b;">
                <p>Reagan Nguyen</p>
            </div>
            <div class="officer break"></div>
            <div class="officer">
                <img src="images/photoshoot_25/JoylynWang.jpg" alt="Joylyn Wang" style="border: 5px solid #076c9b;">
                <p>Joylyn Wang</p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Tournament Logistics</h2>
        <div class="officer-container">
            <div class="officer">
                <img src="images/photoshoot_25/TarunNandamudi.jpg" alt="Tarun Nandamudi" style="border: 5px solid #8e3108;">
                <p>Tarun Nandamudi</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/CatherineFelix.png" alt="Catherine Felix" style="border: 5px solid #8e3108;">
                <p>Catherine Felix</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/ChloeWu.jpg" alt="Chloe Wu" style="border: 5px solid #8e3108;">
                <p>Chloe Wu</p>
            </div>
            <div class="officer break"></div>
            <div class="officer">
                <img src="images/photoshoot_25/HenryAyers.jpg" alt="Henry Ayers" style="border: 5px solid #8e3108;">
                <p>Henry Ayers</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/AdiDesai.jpg" alt="Adi Desai" style="border: 5px solid #8e3108;">
                <p>Adi Desai</p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Volunteering</h2>
        <div class="officer-container">
            <div class="officer">
                <img src="images/photoshoot_25/AnjaliPamulapti.jpg" alt="Anjali Pamulapti" style="border: 5px solid #e7a8e0;">
                <p>Anjali Pamulapti</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/MaggieLi.png" alt="Maggie Li" style="border: 5px solid #e7a8e0;">
                <p>Maggie Li</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/EmmaGotlib.png" alt="Emma Gotlib" style="border: 5px solid #e7a8e0;">
                <p>Emma Gotlib</p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Outreach</h2>
        <div class="officer-container">
            <div class="officer">
                <img src="images/photoshoot_25/SimbaSrivastava.jpg" alt="Simba Srivastava" style="border: 5px solid #e40000;">
                <p>Simba Srivastava</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/BlazeCutinho.jpg" alt="Blaze Cutinho" style="border: 5px solid #e40000;">
                <p>Blaze Cutinho</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/AndrewHanna.jpg" alt="Andrew Hanna" style="border: 5px solid #e40000;">
                <p>Andrew Hanna</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/ChristinaLin.jpg" alt="Christina Lin" style="border: 5px solid #e40000;">
                <p>Christina Lin</p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Public Relations</h2>
        <div class="officer-container">
            <div class="officer">
                <img src="images/photoshoot_25/SarayuPulipati.jpg" alt="Sarayu Pulipati" style="border: 5px solid #6cbe68;">
                <p>Sarayu Pulipati</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/GinaSharma.jpg" alt="Gina Sharma" style="border: 5px solid #6cbe68;">
                <p>Gina Sharma</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/JiyoungNam.jpg" alt="Jiyoung Nam" style="border: 5px solid #6cbe68;">
                <p>Jiyoung Nam</p>
            </div>
            <div class="officer">
                <img src="images/photoshoot_25/NavyaAlishala.jpg" alt="Navya Alishala" style="border: 5px solid #6cbe68;">
                <p>Navya Alishala</p>
            </div>
        </div>
    </div>

    <br><br>
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
        width:250px;
        max-width: 75vw;
        margin-right: 1rem;
        margin-bottom: 1rem;
        margin-top: 1rem;
        margin-left: 1rem;
        /* margin-left: auto;
        margin-right: auto; */
        /* display: block; */
    }

    .officer-container {
        display: flex; /* Enables Flexbox layout */
        flex-wrap: wrap; /* Allows items to wrap to the next row */
        justify-content: center; /* Centers the officer blocks horizontally */
        gap: 10px; /* Adds uniform spacing between officer blocks */
        margin: 0px 0; /* Optional: Add spacing around the container */
    }

    .officer {
        display: flex;
        flex-direction: column; /* Stack image and text vertically */
        align-items: center; /* Ensure the image and text are centered */
        text-align: center; /* Center-align text inside the block */
        width: 250px; /* Ensure uniform width for all officer blocks */
    }

    .officer.break {
        flex-basis: 100%; /* Force this item to take a full row */
        max-width: 100%; /* Ensure it spans the full width */
    }


    .officer img {
        /* width:200px;
        max-width: 75vw; */
        margin-right: 1rem;
        margin-bottom: 0rem;
        margin-top: 0rem;
        margin-left: 1rem;
        width: 100%; /* Ensure image fits within the officer block */
        max-width: 200px; /* Set max width to match the officer block width */
        height: auto; /* Maintain aspect ratio */
        border-radius: 10px; /* Optional: Add rounded corners */
    }

    .officer p {
        margin: 10px 0 0; /* Add spacing above the text */
        font-size: 18px; /* Set font size */
        width: 100%; /* Match text width to the officer block */
    }

    .section {
        margin-top: 3rem;
        text-align: center;
        margin-left: auto;
        margin-right: auto;
    }

    .section:hover h2::after{
        width: 30rem;
        background-color: rgba(106, 44, 62);
    }

    h2 {
        position: relative;
    }

    h2::after {
        content: "";
        height: 3px;
        width: 10rem;
        max-width: 50vw;
        background-color: orange;
        position: absolute;
        bottom: -.5em; 
        left: 50%;
        transform: translate(-50%);

        transition: 0.3s;
    }



</style>





