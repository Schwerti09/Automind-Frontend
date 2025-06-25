<!-- src/routes/+page.svelte -->
<script>
	import { pingServer } from '$lib/api.ts';
	
	pingServer();
</script>

<main>
	<h1>🤖 Willkommen bei AUTOMIND</h1>
	<p>Frontend erfolgreich verbunden.</p>
</main>
