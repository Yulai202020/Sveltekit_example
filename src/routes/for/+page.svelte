<script>
    let message = $state("");
    let count = $state(0);
</script>

<main>
    <div class="container">
        <label for="message">Input text</label>
        <input type="text" id="message" style="width: 300px;" bind:value={message}>
        <div>
            <p>{count}</p>
            <button onclick={() => count++}>+</button>
            <button onclick={() => count--}>-</button>
        <div>

        {#each {length: count} as _, i}
            {message}
        {/each}
    </div>
</main>

<style>
    .container {
        display: flex;
        flex-direction: column;
    }
</style>