<script>
	import { page, navigating } from '$app/stores';
	import { Jumper } from 'svelte-loading-spinners';
</script>

<header>
<nav>
	<ul>
		<li>True Event</li>
	</ul>
	{#if $navigating}
		<Jumper size="60" color="#FF3E00" unit="px" duration="1s" />
	{/if}
</nav>
</header>

<style>

ul {
	list-style-type: none;
}

</style>
