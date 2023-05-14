<script>
import Title from './Title.svelte';
import Story from './Story.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Laptop Service Experience" />
</svelte:head>

<section>

<Title />
<Story />

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: left;
		align-items: left;
	}

</style>
