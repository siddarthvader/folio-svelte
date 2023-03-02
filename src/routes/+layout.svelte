<script>
	import { SvelteUIProvider } from '@svelteuidev/core';
</script>

<SvelteUIProvider class="animate-bounce app-shell h-full flex flex-col">
	<slot />

	<div class="text-red-600">Siddharth</div>
</SvelteUIProvider>

<style global>
	.app-shell {
		width: 100%;
		height: 100%;
	}
</style>
