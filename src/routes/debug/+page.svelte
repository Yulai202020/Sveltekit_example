<script>
    let message = $state("");
</script>

<main>
    <!-- @debug its alternative of console.log() -->
    <input type="text" bind:value={message}>

    {@debug message}
</main>