<script lang="ts">
    import favicon from "$lib/assets/favicon.svg";
    import "../app.scss";
    let { children } = $props();
</script>

<svelte:head>
    <link rel="icon" href={favicon} />
    <link
        rel="stylesheet"
        href="https://raw.githubusercontent.com/sindresorhus/modern-normalize/refs/heads/main/modern-normalize.css"
    />
</svelte:head>

<nav>
    <div>
        <a href="https://haj-links.vercel.app">
            <img
                src="/src/lib/assets/splashtag.png"
                alt="tag"
                style:width="250px"
            /></a
        >
    </div>
</nav>

{@render children()}
