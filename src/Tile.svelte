<script>
	import TopLeft from './TopLeft.svelte';
	import TopRight from './TopRight.svelte';
	import BottomLeft from './BottomLeft.svelte';
	import BottomRight from './BottomRight.svelte';

	const random = Math.floor(Math.random() * 3);
</script>

{#if random === 0}
	<TopLeft />
{/if}
{#if random === 1}
	<TopRight />
{/if}
{#if random === 2}
	<BottomLeft />
{/if}
{#if random === 3}
	<BottomRight />
{/if}