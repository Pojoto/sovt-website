
<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
</svelte:head>

<script>
    import Card from '$lib/Card.svelte'; 
    import Button from '$lib/Button.svelte';
</script>


<body>
    <div class="title">
        2024 Virginia Tech Invitational
    </div>

    <div class="cards">
        <Card title="Date" content="1/27/24"/>
        <Card title="Division" content="C"/>
        <Card title="Team # Cap" content="32"/>
        <Card title="Cost" content="$100*"/>
    </div>

    <div class="info">
        The Virginia Tech Invitational will be held in-person on Virginia Tech's campus in Blacksburg, Virginia. 
        Registration cost will be $100 for the first team and $80 for additional teams. Registration will open on 
        October 2 for VA teams, and October 6 for all other teams. We will be closing registration on Friday, November 10th at 11:59 PM.
        SO@VT will be providing high-quality tests and experienced event supervisors for every event.

    </div>

    <Button text="Register Here" url="/" active={false}/>


</body>





<style>

    body {
        padding-top: 10rem;
    }

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
        width: 50vw;
        margin-left: auto;
        margin-right: auto;
        margin-top: 2rem;
        text-align: center;
        font-family: 'Montserrat', sans-serif;
        font-size: 1rem;
    }

</style>
