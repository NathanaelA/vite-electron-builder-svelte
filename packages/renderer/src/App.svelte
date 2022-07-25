<script>
import Counter from './lib/Counter.svelte';
</script>

<main>
<div>
  <a href="https://vitejs.dev/" target="_blank">
    <img src="./assets/vite.svg" class="logo" alt="Vite Logo" />
  </a>
  <a href="https://svelte.dev/" target="_blank">
    <img src="./assets/svelte.svg" class="logo" alt="Svelte Logo" />
  </a>
</div>
<h1>Vite + Svelte</h1>

<div class="card">
  <Counter />
</div>

<p>
  Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank">SvelteKit</a>, the official Svelte app framework powered by Vite!
</p>

<p class="read-the-docs">
  Click on the Vite and Svelte logos to learn more
</p>
</main>

<style>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.read-the-docs {
  color: #888;
}
</style>
