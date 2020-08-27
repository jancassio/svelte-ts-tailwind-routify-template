<script lang="ts">
	export let name: string;
</script>

<style>
	@tailwind base;
  @tailwind components;
  @tailwind utilities;

	p {
		@apply text-gray-600 text-sm;
	}

	main {
		@apply text-center p-1 max-w-xs my-0 mx-auto;
	}
</style>

<main>
	<h1 class="text-4xl text-red-600 uppercase">Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>
