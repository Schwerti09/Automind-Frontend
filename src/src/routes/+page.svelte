<script>
  import { onMount } from 'svelte'
  let status = '...'

  onMount(async () => {
    const res = await fetch('/api/reality-check')
    const data = await res.json()
    status = data.status
  })
</script>

<main>
  <h1>AUTOMIND UI</h1>
  <p>Status: {status}</p>
</main>

<style>
  main {
    font-family: system-ui, sans-serif;
    padding: 2rem;
    background: #0a0a12;
    color: #00ff9f;
    height: 100vh;
  }

  h1 {
    font-size: 2rem;
    color: #bd00ff;
  }
</style>
