<script>
	import PokemonTile from "./PokemonTile.svelte";


</script>

<div>
    <PokemonTile />
    <PokemonTile />
    <PokemonTile />
    <PokemonTile />
</div>

<style>
    div {
        background-color: pink;
        width: 80%;
        max-width: 1300px;
        margin: 0 auto;
        padding: 1em;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
</style>