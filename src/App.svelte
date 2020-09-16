<script>
  export let name;
</script>

<style global>
  /* purgecss start ignore */
  @tailwind base;
  @tailwind components;
  /* purgecss end ignore */
  @tailwind utilities;
</style>

<main class="text-center">
  <h1 class="text-red-800 text-6xl">Hello {name}!</h1>
  <p class="p-2">
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
  <p class="text-sm text-gray-600">TailwindCSS Integration</p>
</main>
