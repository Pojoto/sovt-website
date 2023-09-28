
<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
</svelte:head>

<script>
    import Button from '$lib/Button.svelte';
</script>

<body>
    <div class='bg-image'></div>

    <div class="content">

        <img src="/images/sovtlogo_transparent_white.png" class="logo" alt="Main SO@VT Logo">

        <div class="border b"></div>
        <div class="border"></div>

        <div class="invy-banner">
            Division C. Invitational
            <br>
            <b>January 27, 2024</b>
            <br>
            <br>
            <Button text="More Info" url="/tournament-info"/>
        </div> 

    </div>

</body>


<style>

    .bg-image {
        /* The image used */
    background-image: url("/images/vtphoto.png");
    
    
    /* Full height */
    height: 100%; 
    width: 100%;
    
    /* Center and scale the image nicely */
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    /* background-repeat: no-repeat;
    background-attachment: fixed;  
    background-size: cover; */
    }

    body {
        margin: 0;
        height: 100vh;
        /* display: flex;
        align-items: center;
        justify-content: center;
        background-color: white; */
        overflow: hidden;
    }


    .content {

        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
        position: absolute;
        top: 50%;
        left: 45%;
        transform: translate(-50%, -50%);
        width: 90%;   

    }

    .logo {

        width: 30rem;
        padding: 5rem;
    }

    .border {
        width: 1rem;
    
        height: 30rem;

    }

    .border.b {
        border-right: 5px solid orange;
        animation: growHeight ease 2s 1 forwards;
    }

    .invy-banner {

        text-align: center;
        font-size: 2rem;
        font-family: 'Montserrat', sans-serif;
        color: white;

        padding: 7rem;
        animation: fadeInAnimation ease 2s 1 forwards;

    }

    @keyframes growHeight {
        0% {
            height: 0;
        }
        100% {
            height: 30rem;
        }
    }

    @keyframes fadeInAnimation {
        0% {
            opacity: 0;
        }
        100% {
            opacity: 1;
        }
    }


</style>