<script>
    export let data
</script>
{#if data.success}
<ul>
    {#each data.myData as item}
    <li>{item.name}</li>
    {/each}
</ul>
{:else}
    <p>There was a problem getting the data...</p>
{/else}