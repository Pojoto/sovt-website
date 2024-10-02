

<script>
    export let text = "";
    export let url = "/";
    export let bgcolor = "orange";
    export let txtcolor = "black";
    export let active = true;
</script>

{#if active}
    <a href={url} class="button" style="background-color:{bgcolor}; color:{txtcolor}">
        {text}
    </a>
{:else}
    <div class="button" style="background-color:lightgray">
        {text}
    </div>
{/if}




<style>

    .button{
        display: block;
        border-radius: .5rem;
        background-color: orange;
        font-size: 1rem;
        font-family: 'Montserrat', sans-serif;
        width: 10rem;
        height: 2.5rem;
        line-height: 2.5rem;
        text-align: center;
        margin: auto;
        box-shadow: 0 0px 15px rgba(255, 255, 255, 0);

        transition: all 0.3s ease-in-out;
    }

    .button:hover {
        color: rgba(255, 255, 255, 1);
        box-shadow: 0 0px 15px rgba(0, 0, 0, 0.5);
    }

    .button:hover::after {
        transition: opacity 0.3s ease-in-out;
    }

    a {
        text-decoration: none;
    }


</style>