<script>
	import pre_display from '$lib/images/Display-by-palies.jpg';
	import pre_display_close_up from '$lib/images/Display-close-up.jpg';
	import palies_ack_slip from '$lib/images/Palies-ack-slip.jpg';
	import post_display_1 from '$lib/images/Post-display-1.jpg';
	import post_display_2 from '$lib/images/Post-display-2.jpg';
	import post_display_3 from '$lib/images/Post-display-3.jpg';
	import branch_1 from '$lib/images/Branch-1.jpg';
	import branch_2 from '$lib/images/Branch-2.jpg';
	import branch_3 from '$lib/images/Branch-3.jpg';
</script>
<h3> Pictures before </h3>
	<div id="grid-container">
		<img class="pre" src={pre_display} />
		<img class="pre" src={pre_display_close_up} />
		<img class="pre" src={palies_ack_slip} />
	</div>
<h3> Pictures after </h3>
	<div id="grid-container">
		<img class="post" src={post_display_1} />
		<img class="post" src={post_display_3} />
		<img class="post" src={post_display_2} />
	</div>
	
<h3> Palies IT Service, Peelamedu, Coimbatore </h3>	
	<div id="grid-container">
		<img class="post" src={branch_1} />
		<img class="post" src={branch_2} />
		<img class="post" src={branch_3} />
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