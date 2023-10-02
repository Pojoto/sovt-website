
<script>
    import Card from '$lib/Card.svelte'; 
    import Button from '$lib/Button.svelte';
</script>

<div class='bg-image'></div>
<div class="content">
    <div class="title">
        <b>2024 Virginia Tech Invitational</b>
    </div>

    <div class="division">Division C</div>
    <br>
    <div class="division">January 27, 2024</div>
    
    <div class="cards">
        <Card title="Date" content="1/27/24"/>
        <Card title="Division" content="C"/>
        <Card title="Team # Cap" content="32"/>
        <Card title="Cost" content="$100*"/>
    </div>
    
    <div class="info">
        <b>We're excited to announce the 2024 Virginia Tech Invitational! It will be held in-person on Virginia Tech's campus in Blacksburg, Virginia and is open to teams from Virginia and across the country.</b>
    
    
        <div class="section">
            <h2>
                Registration
            </h2>
        
            <p style="text-align:left">
                Registration cost will be <b>$100</b> for the first team and <b>$80</b> for additional teams, up to 3 teams per school. 
                Our team cap this year is 32 teams.<br>Registration is first come, first serve, and will open on 
                <b>October 2</b> for Virginia teams, and <b>October 6</b> for other states.
                <br><br>
            </p>
    
            <p style="text-align:left">
                We welcome both veteran and new teams to gain competition experience at our tournament. If you are a Virginia school and qualify for the VASO Outreach Initiative, we will waive half of your registration fees. 
                If your school otherwise has special circumstances that prevent you from paying the regsitration fees, 
                please reach out to us at scienceolympiadvt@gmail.com</p>
        
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
                Tournament quality is extremely important to us. Tests will be written by experienced Science Olympiad alumni from Virginia Tech and around the country. 
                Each test goes through a series of checks and deadlines to ensure the highest quality. <br>
                <ul style="display:inline-block">
                    <li></li>
                    <li></li>
                </ul>
                <br>
        
            </p>
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
        background-color: orange;
        position: absolute;
        bottom: -.5em; 
        left: 50%;
        transform: translate(-50%);

        transition: 0.3s;
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
