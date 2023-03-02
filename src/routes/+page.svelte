<script lang="ts">
	import {
		fns,
		AppShell,
		Navbar,
		Header,
		Footer,
		ShellSection,
		Aside,
		Container
	} from '@svelteuidev/core';

	import HeaderContent from './Components/Header.svelte';
	import HeroContent from './Components/Hero.svelte';
	import SideNavContent from './Components/SideNav.svelte';
	import FooterContent from './Components/Footer.svelte';
</script>

<AppShell>
	<Navbar height="100%" slot="navbar" position={{ top: 0, left: 0 }} width={{ xl: '300px' }}>
		<SideNavContent />
	</Navbar>
	<Header slot="header" height="32px" p="1">
		<HeaderContent />
	</Header>

	<ShellSection grow>
		<HeroContent />
	</ShellSection>

	<Footer height="20px" slot="footer">
		<FooterContent />
	</Footer>
</AppShell>
