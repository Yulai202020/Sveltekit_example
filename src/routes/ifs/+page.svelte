<script>
    let message = $state("");
</script>

<main>
    <input type="text" bind:value={message}>
    {#if message === "hello"}
        <p>Hello!</p>
    {:else}
        <p>Input hello</p>
    {/if}
</main>