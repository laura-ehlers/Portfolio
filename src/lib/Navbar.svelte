<script>
    const links = ['Home', 'About Me', 'Portfolio', 'Contact'];
</script>

<main class="p-3">
    <nav class="navbar bg-primary text-primary-content rounded-3xl ">
        <div class="flex-1">
            <p class="btn btn-ghost normal-case text-xl">Laura Ehlers</p>
        </div>
        <div class="flex-none">
            {#each links as link}
                <li class="menu menu-horizontal px-1">{link}</li>
            {/each}
        </div>
    </nav>
</main>
