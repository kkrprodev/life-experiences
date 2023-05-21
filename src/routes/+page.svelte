<script>
	import Story from './Story.svelte';
	import Loader from './Loader.svelte';
	import { Jumper } from 'svelte-loading-spinners';
</script>

<svelte:head>
	<title>Palies - Worst Laptop Service Experience</title>
	<meta name="description" content="Laptop Service Experience" />
</svelte:head>

<section>

<Loader this={() => import('./Story.svelte')}>
	<div slot="fallback">
		<Jumper size="60" color="#FF3E00" unit="px" duration="1s" />
	</div>
</Loader>

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: left;
		align-items: left;
		width: 100%;
	}

</style>
