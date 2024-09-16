<script>
	import PokemonList from '$lib/components/PokemonList.svelte';
	import NavBar from '$lib/components/NavBar.svelte';
</script>

<div>
	<NavBar />
	<div id="content">
		<PokemonList />
	</div>
</div>

<style>
	#content {
		height: auto;
		width: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}
</style>
