<script>
	import { SvelteUIProvider } from '@svelteuidev/core';
</script>

<SvelteUIProvider class="app-shell h-full flex flex-col">
	<slot />
</SvelteUIProvider>

<style global>
	.app-shell {
		width: 100%;
		height: 100%;
	}
</style>
