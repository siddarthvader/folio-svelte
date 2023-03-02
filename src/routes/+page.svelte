<script lang="ts">
	import HeaderContent from './Components/Header.svelte';
	import HeroContent from './Components/Hero.svelte';
	import SideNavContent from './Components/SideNav.svelte';
	import FooterContent from './Components/Footer.svelte';
</script>

<HeaderContent />
<SideNavContent />
<FooterContent />
<HeroContent />

<style global>
	.app-shell {
		width: 100%;
		height: 100%;
	}
</style>
