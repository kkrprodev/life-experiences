<script>
	import pre_display from '$lib/images/Display-by-palies.jpg';
	import pre_display_close_up from '$lib/images/Display-close-up.jpg';
	import post_display_1 from '$lib/images/Post-display-1.jpg';
	import post_display_2 from '$lib/images/Post-display-2.jpg';
	import post_display_3 from '$lib/images/Post-display-3.jpg';
</script>

<div id="grid-container">
	<img class="pre" src={pre_display} />
	<img class="post" src={post_display_1} />
</div>

<style>

#grid-container {
	display: grid;
    grid-template-columns: auto auto;
}

img {
	width: 100%;
}


</style>