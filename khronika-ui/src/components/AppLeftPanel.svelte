<!-- AppLeftPanel.svelte -->
<script lang="ts">
	// Define your left panel items here (e.g., tasks, notes, etc.)
	export let leftPanelItems: any[] = [
		{ name: 'Tasks', icon: 'bx-task', link: '/task-view' },
		{ name: 'Notes', icon: 'bx-note', link: '/' }
		// Add more items as needed...
	];
</script>

<div class="bg-surface-800 text-white h-full w-24 sticky top-0 left-0 overflow-y-auto">
	<div class="flex items-center justify-center h-16">
		<span class="text-2xl font-bold">
			<a href="/">
				<img src="assets/khronika-logo-no-bg.png" alt="Khronika" class="pt-3 w-24" />
			</a>
		</span>
	</div>

	<ul class="mt-4">
		{#each leftPanelItems as item}
			<li class="p-4 cursor-pointer flex items-center space-x-4 hover:bg-gray-700">
				<i class="{item.icon} text-xl" />
				<a href={item.link}>
					<span class="text-lg">{item.name}</span>
				</a>
			</li>
		{/each}
	</ul>
</div>

<style>
	/* Customize the styles here or create a separate CSS file and import it */
</style>
