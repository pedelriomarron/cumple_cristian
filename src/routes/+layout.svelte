<script>
	import Header from "./Header.svelte";
	import "./styles.css";
	export const prerender = true;
</script>

<div class="app">
	<main>
		<slot />
	</main>
</div>

<style>
	.app {
	}

	main {
	}
</style>
