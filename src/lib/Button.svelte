

<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
</svelte:head>


<script>
    export let text = "";
    export let url = "/";
</script>

<a href={url} class="button">
    {text}
</a>



<style>

    .button{
        display: block;
        border: solid orange 5px;
        border-radius: .5rem;
        background-color: orange;
        font-size: 1rem;
        font-family: 'Montserrat', sans-serif;
        width: 10rem;
        height: 2rem;
        line-height: 2rem;
        text-align: center;
        margin: auto;
        box-shadow: 0 0px 15px rgba(255, 255, 255, 0);

        transition: all 0.3s ease-in-out;
    }

    .button:hover {
        color: rgba(0, 0, 0, 1);
        box-shadow: 0 0px 20px rgba(255, 255, 255, .5);
    }

    .button:hover::after {
        transition: opacity 0.3s ease-in-out;
    }

    a {
        text-decoration: none;
    }


</style>