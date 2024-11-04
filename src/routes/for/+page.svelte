<script>
    let message = $state("");
    let count = $state(0);
</script>

<main>
    <input type="text" bind:value={message}>
    <p>{count}</p>
    <button onclick={() => count++}>+</button>
    <button onclick={() => count--}>-</button>

    {#each {length: count} as _, i}
        {message}
    {/each}
</main>