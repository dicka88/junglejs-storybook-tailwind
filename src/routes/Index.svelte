<script>
	import Nav from "../components/Nav.svelte";
</script>

<svelte:head>
	<title>Index - Example JungleJS App</title>
</svelte:head>

<Nav page="/"/>
<main>
	<h1 class="text-green-500 font-bold text-4xl md:text-6xl">Welcome!</h1>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>