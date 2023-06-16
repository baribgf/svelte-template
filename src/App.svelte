<svelte:options tag="bari-app"/>

<script>
    export let name = "World";
</script>

<div id="main-container">
    <h1>Hello, {name}!</h1>
    <h4>Bari BGF's App</h4>
</div>

<style>
    #main-container {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
</style>
