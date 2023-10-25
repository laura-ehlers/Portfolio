<script>
    const links = [{text: 'Home', slug: '/'}, {text: 'About Me', slug: '/about'},{text: 'Portfolio', slug: '/#portfolio'}, {text: 'Contact', slug: '/#contact'}];
</script>

<main class="p-3">
    <nav class="navbar text-primary-content rounded-3xl ">
        <div class="flex-1">
            <p class="btn normal-case text-xl">Laura Ehlers</p>
        </div>
        <div class="flex-none">
            {#each links as link}
                <a href="{link.slug}" class="btn btn-ghost menu menu-horizontal text-xl">{link.text}</a>
            {/each}
        </div>
    </nav>
</main>
