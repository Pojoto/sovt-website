

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
        font-family: 'Montserrat', sans-serif;
        width: 10rem;
        height: 10rem;
        text-align: center;
        margin-left: 2rem;
        margin-right: 2rem;
        box-shadow: 0px 3px 10px rgba(0, 0, 0, .5);
    }

    .card-title {
        margin-top: 1rem;
        font-size: 1.5rem;
        font-weight: 500;
    }

    .card-content {

        font-size: 3rem;
        position:absolute;

        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);

    }


</style>