<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
</svelte:head>


<script>
    import Bio from '$lib/Bio.svelte';

    const group_data = [["Executive Board", 6], ["Tournament Logistics", 5], ["Volunteering", 3], ["Outreach", 4], ["Public Relations", 2]];

</script>


{#each group_data as group}

    <div class="group">
        <div class="title">
            {group[0]}
        </div>

        <div class="bios">
            {#each Array(group[1]) as _}
                <Bio />

            {/each}
        </div>


    </div>

{/each}



<style>

    .group .title{

        font-family: 'Montserrat', sans-serif;
        font-size: 2rem;
        text-align: center;
        margin-top: 10rem;

    }

    .bios {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    body {
        overflow: scroll;
    }

</style>