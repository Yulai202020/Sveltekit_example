<script>
    import Navigation from "../nav.svelte";

    let message = $state("");
</script>

<main>
    <Navigation />

    <input type="text" bind:value={message}>
    {#if message === "hello"}
        <p>Hello!</p>
    {:else}
        <p>Input hello</p>
    {/if}
</main>