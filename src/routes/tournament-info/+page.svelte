
<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
</svelte:head>

<script>
    import Card from '$lib/Card.svelte'; 
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

    The Virginia Tech Invitational will be held in-person on Virginia Tech's campus in Blacksburg, Virginia.

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
        margin-top: 2rem;
    }

</style>
