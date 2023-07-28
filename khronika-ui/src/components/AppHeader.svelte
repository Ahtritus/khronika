<script lang="ts">
	import { AppBar } from '@skeletonlabs/skeleton';
	import { LightSwitch } from '@skeletonlabs/skeleton';
</script>

<div class="h-16">
	<AppBar background="bg-surface-300 dark:bg-primary-800"
	
	gridColumns="grid-cols-2" slotDefault="place-self-start" slotTrail="place-content-end">
		
		<a href="/"><h3 class="h3">Khronika</h3></a>
		<svelte:fragment slot="trail"><LightSwitch /></svelte:fragment>
	</AppBar>
</div>
