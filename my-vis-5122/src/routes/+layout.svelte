<script>
    let { children } = $props();
    import "../app.css";
</script>


<svelte:head>
    <title>Interactive Multi Views</title>
    <meta name="description" content="Svelte + D3 Tutorial" />
</svelte:head>


{@render children()}