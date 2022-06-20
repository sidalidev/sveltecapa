<script>
	import '../app.css';
</script>

<svelte:head>
	<meta
		name="viewport"
		content="viewport-fit=cover, width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no"
	/>
</svelte:head>

<main>
	<slot />
</main>

<style lang="postcss">
	main {
		@apply pt-10 px-4;
	}
</style>
