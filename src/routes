<script lang="ts">
  import { onMount } from 'svelte';
  import { pingServer } from '$lib/api';

  let serverStatus = 'Wird geprüft...';

  onMount(async () => {
    serverStatus = await pingServer();
  });
</script>

<main class="h-screen w-screen flex flex-col items-center justify-center bg-black text-white">
  <h1 class="text-4xl font-bold mb-4">AUTOMIND FRONTEND</h1>
  <p class="text-lg">{serverStatus}</p>
</main>

<style>
  main {
    font-family: system-ui, sans-serif;
  }
</style>
