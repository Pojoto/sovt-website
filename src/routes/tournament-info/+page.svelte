<svelte:head>
    <title>Tournament Info</title>
</svelte:head>
<script>
    import Card from '$lib/Card.svelte'; 
    import Button from '$lib/Button.svelte';
</script>

<div class='bg-image'></div>
<div class="content">
    <div class="title">
        <b>2025 Virginia Tech Invitational</b>
    </div>

    <div class="division">Division C</div>
    <br>
    <div class="division">February 1, 2025</div>
    
    <div class="cards">
        <Card title="Date" content="2/1/25"/>
        <Card title="Division" content="C"/>
        <Card title="Team # Cap" content="TBD"/>
        <Card title="Cost" content="TBD"/>
    </div>
    
    <div class="info">
        <b>The date for the 2025 Virginia Tech Invitational has been decided! More details are to come.</b>
    

        <div class="section">

            <h2>Why SO@VT?</h2>

            <h1 class="subtitle">Explore Virginia Tech</h1>
            <p style='text-align:left'>We will have opportunities for exclusive university lab tours, 
                connecting with VT students and programs, and meeting the Hokie 
                Bird (our wonderful school mascot!). We encourage students to 
                explore VT’s campus and award-winning dining halls during our 
                tournament.</p>

                <br>

            <h1 class="subtitle">Build Events</h1>
            <p style='text-align:left'>We’re working closely with VASO to align 
                build testing with Regionals and State tournament standards. 
                We expect to run all builds this year.</p>

                <br>

            <h1 class="subtitle">Test Events</h1>
            <p style='text-align:left'>Our writers are experienced Science Olympiad 
                alumni from Virginia Tech and other colleges. 
                Tests go through rounds of thorough review and revision to ensure quality.</p>

                <br>

            <h1 class="subtitle">Early-Spring Regionals Prep</h1>
            <p style='text-align:left'>We are targeting our invitational to give teams the
                 best competitive start to the Regionals/States season. 
                 Virginia teams can return for our Virginia Tech Regional 
                 on February 15th, 2025.</p>

            
                 <br>

            <h1 class="subtitle">Webinars and Support</h1>
            <p style='text-align:left'>We host an annual Q&A webinar leading up 
                to our competition, where SO alumni give competition advice. 
                We’d love to answer any questions you have about our tournament 
                or team logistics in general.</p>

            <!-- <h2>
                Tests
            </h2>
        
            <p>
                Tournament quality is extremely important to us. Tests will be written by experienced Science Olympiad alumni from Virginia Tech and around the country. 
                Each test goes through a series of checks and deadlines to ensure the highest quality. <br>
                <br>
            </p> -->
        </div>

        <div class="section">
            <h2>
                Campus Map, Food, Schedule, VT Programs
            </h2>
        
            <p>
                Coming Soon! 🦃
        
            </p>
        </div>


    </div>
</div>



<style>

    .title {
        text-align: center;
        font-family: 'Montserrat', sans-serif;
        font-size: 3rem;

    }

    .division {
        display: none;
        text-align: center;
        font-family: 'Montserrat', sans-serif;
        font-size: 2rem;
    }

    .cards {
        display: flex;
        align-items: center;
        justify-content: center;
        margin-top: 2rem;
    }

    .info {

        margin-left: auto;
        margin-right: auto;
        margin-top: 2rem;
        text-align: center;
        font-family: 'Montserrat', sans-serif;
        font-size: 1rem;
    }

    .section {
        margin-top: 3rem;
        text-align: center;
        margin-left: auto;
        margin-right: auto;
    }

    .content {

        background-color: rgba(255, 255, 255, .9);
        margin-top: 8rem;
        width: 70vw;
        text-align: center;
        margin-left: auto;
        margin-right: auto;

        border-radius: 5rem;

        padding: 3rem;
    }

    .bg-image {
        /* The image used */
        background-image: url("/images/drillfield_sunset.jpg");
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
        max-width: 75vw;
        background-color: orange;
        position: absolute;
        bottom: -.5em; 
        left: 50%;
        transform: translate(-50%);

        transition: 0.3s;
    }


    .subtitle {

        font-size: 1.15rem;
        font-weight: 1000;
        text-decoration: underline;
        text-underline-offset: .4rem;
        text-decoration-color: orange;
        text-align: left;

    }


    @media (max-width: 1000px) {
        .cards {
            display: none;
        }   

        .division {
            display: inline;
        }   
    }



</style>
