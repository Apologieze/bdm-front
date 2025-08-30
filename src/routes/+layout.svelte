<script lang="ts">
	import '../app.css';
	import ScrollingBanner from '$lib/components/ScrollingBanner.svelte';
	import favicon from '$lib/assets/favicon.svg';
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<!-- Add the banner here, outside of the main content area -->
<ScrollingBanner />

<!-- It's good practice to wrap your page content in a <main> tag -->
<main>
	{@render children?.()}
</main>