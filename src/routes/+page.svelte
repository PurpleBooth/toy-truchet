<script>
	import Tile from '../Tile.svelte';
</script>

<div style:display="flex" style:flex-wrap="wrap" style:gap="0">


	{#each { length: 1003 } as _, i}
		<Tile />
	{/each}
</div>
