<script>
	import '../app.postcss';
	import '@skeletonlabs/skeleton/themes/theme-skeleton.css';
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	import '@skeletonlabs/skeleton/themes/theme-modern.css';
	import '@skeletonlabs/skeleton/themes/theme-rocket.css';
	import '@skeletonlabs/skeleton/themes/theme-seafoam.css';
	import '@skeletonlabs/skeleton/themes/theme-vintage.css';
	import '@skeletonlabs/skeleton/themes/theme-sahara.css';
	import '@skeletonlabs/skeleton/themes/theme-hamlindigo.css';
	import '@skeletonlabs/skeleton/themes/theme-crimson.css';
	import '@skeletonlabs/skeleton/themes/theme-gold-nouveau.css';

    import { AppShell } from '@skeletonlabs/skeleton';
	import AppHeader from "../components/AppHeader.svelte"
	import AppLeftPanel from "../components/AppLeftPanel.svelte"


</script>

<AppShell>
	<svelte:fragment slot="pageHeader"><AppHeader/></svelte:fragment>
	<svelte:fragment slot="sidebarLeft"><AppLeftPanel /></svelte:fragment>
	<!-- (sidebarRight) -->
	<!-- (pageHeader) -->
	<!-- Router Slot -->
	<slot />
	<!-- ---- / ---- -->
	<svelte:fragment slot="pageFooter">Page Footer</svelte:fragment>
	<!-- (footer) -->
</AppShell>


