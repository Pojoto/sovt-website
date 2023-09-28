

<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
</svelte:head>


<script>
    export let title = "";
    export let content = "";
</script>

<div class="card">
    <div class="card-title">{title}</div>
    <div class="card-content">{content}</div>
</div>



<style>

    .card{
        position: relative;
        display: block;
        border-radius: 2rem;
        background-color: orange;
        font-size: 1rem;
        font-family: 'Montserrat', sans-serif;
        width: 15rem;
        height: 15rem;
        text-align: center;
        margin: auto;
        box-shadow: 5px 5px 5px rgba(0, 0, 0, .5);
    }

    .card-title {
        margin-top: 1rem;
        font-size: 2rem;
        font-weight: 500;
    }

    .card-content {

        font-size: 4rem;
        position:absolute;

        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);

    }


</style>