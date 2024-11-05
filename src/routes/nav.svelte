<script>
</script>

<main>
    <nav class="menu">
        <ul class="navbar">
            <li><a href="/">Home page</a></li>
            <li><a href="/ifs">If statement example</a></li>
            <li><a href="/for">For statement example</a></li>
            <li><a href="/imports">imports example</a></li>
            <li><a href="/snippet">snippet example</a></li>
        </ul>
    </nav>
</main>

<style>
    :global(body), :global(html) {
        margin: 0px;
    }
    .menu {
        background-color: black;
    }

    .navbar {
        display: flex;
        justify-content: center;
    }

    .navbar a {
        color: white;
        text-decoration: none;
        padding: 20px 30px;
        display: block;
        transition: background-color 0.3s ease, color 0.3s ease;
    }

    .navbar a:hover {
        background-color: #575757;
        color: #ffcc00;
    }

</style>