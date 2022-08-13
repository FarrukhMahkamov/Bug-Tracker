<script>
    import Card from "../component/Card.svelte";
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<div class="card">
    <Card/>
    <Card/>
    <Card/>
</div>
<style>
    .card {
        display: flex;
    }
</style>