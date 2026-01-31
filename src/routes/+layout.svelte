<script lang="ts">
    import favicon from "$lib/assets/favicon.svg";
    import "../app.scss";
    import tag from "$lib/assets/splattag.png"
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
        <h2>/!\ under construction /!\</h2>
        <a href="https://haj-links.vercel.app">
            <img
                src={tag}
                alt="tag"
                style:width="250px"
            /></a
        >
    </div>
</nav>

{@render children()}
