<script>
	

    import { fns, AppShell, Navbar, Header,Footer, ShellSection, Aside } from '@svelteuidev/core';

	import HeaderContent from "./Components/Header.svelte";
	import HeroContent from './Components/Hero.svelte';
	import SideNavContent from "./Components/SideNav.svelte";
    import FooterContent from './Components/Footer.svelte';
    

</script>


<AppShell 
navbarOffsetBreakpoint="sm"
asideOffsetBreakpoint="sm">
	<Navbar slot="navbar" fixed position={{ top: 0, left: 0 }}  width={{
        sm: 300,
        lg: 400,
        base: 100
    }}>
		<SideNavContent />
    </Navbar>
	<Header slot="header" height=32 fixed>
		<HeaderContent />
	</Header>
    <ShellSection grow>

        <HeroContent></HeroContent>
    </ShellSection>



    <Footer height="20px" slot="footer">

        <FooterContent></FooterContent>
    </Footer>
</AppShell>