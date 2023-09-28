
<script>
    import Card from '$lib/Card.svelte'; 
    import Button from '$lib/Button.svelte';
</script>

<div class='bg-image'></div>
<div class="content">
    <div class="title">
        <b>2024 Virginia Tech Invitational</b>
    </div>
    
    <div class="cards">
        <Card title="Date" content="1/27/24"/>
        <Card title="Division" content="C"/>
        <Card title="Team # Cap" content="32"/>
        <Card title="Cost" content="$100*"/>
    </div>
    
    <div class="info">
        <b>We're extremely excited to announce the 3rd Virginia Tech Invitational! It will be held in-person on Virginia Tech's campus in Blacksburg, Virginia.</b>
    
    
        <div class="section">
            <h2>
                Registration
            </h2>
        
            <p>
                Registration cost will be <b>$100</b> for the first team and <b>$80</b> for additional teams, up to max 3 teams. <br>Registration is first come, first serve, and will open on 
                <b>October 2</b> for Virginia teams, and <b>October 6</b> for all other states.
                <br><br>
    
    
                *If your school qualifies for the VASO Outreach Initiative, we will waive half of your registration fees. 
                If your school otherwise has special circumstances that prevent you from paying the regsitration fees, please reach out to us at scienceolympiadvt@gmail.com
        
                <br><br>
                <Button text="Register Here" url="/" active={false}/>
        
                <b style="font-size:.75rem">Registration closes November 10 @ 11:59 PM</b>
        
            </p>
        </div>

        <div class="section">
            <h2>
                Tests
            </h2>
        
            <p>
                Test quality is extremely important to us. Tests will be written by experienced Science Olympiad alumni from Virginia Tech and around the country. 
                Each test goes through a series of checks and deadlines to ensure the highest quality.
        
            </p>
        </div>

        <div class="section">
            <h2>
                Map
            </h2>
        
            <p>
                Events will be held at buildings across the academic side of campus. 
                <br>
                <br>
                <a href="https://www.vt.edu/content/dam/vt_edu/maps-locations/blacksburg-map-july21.pdf" target="_blank">PDF Map</a>
                <br>
                <a href="https://campusmap.aws.gis.cloud.vt.edu/">Online Interactive Map</a>
        
            </p>
        </div>

        <div class="section">
            <h2>
                Food
            </h2>
        
                There are several dining halls across campus, located mainly on the residential side. Some options:<br>
                <ul style="display:inline-block">
                    <li>a</li>
                    <li>b</li>
                    <li>c</li>
                    <li>d</li>
                </ul>
                <br>

                If you really want to, food can be found off campus. (Virginia Tech is ranked #2 in campus food!)

        </div>


    </div>
</div>



<style>

    .title {
        text-align: center;
        font-family: 'Montserrat', sans-serif;
        font-size: 3rem;

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
        background-image: url("/images/drillfield_sunset.png");
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
        background-color: orange;
        position: absolute;
        bottom: -.5em; 
        left: 50%;
        transform: translate(-50%);

        transition: 0.3s;
    }



</style>
