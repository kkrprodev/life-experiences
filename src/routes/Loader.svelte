<script>

    import {onMount} from 'svelte';

	let loader;
	let Component;
    
    onMount(async () => {
        Component = (await loader()).default;
    })

</script>