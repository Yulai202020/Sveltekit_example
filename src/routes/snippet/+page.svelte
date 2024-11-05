<script>
    import Navigation from "../nav.svelte";
</script>

<main>
    <Navigation />

    <!-- snippet its like html function -->
    {#snippet hello(name)}
        <p>Hello {name}!</p>
    {/snippet}

    {@render hello("yulai")}
    {@render hello("azamat")}
</main>
