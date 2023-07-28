<!-- TaskView.svelte -->
<script>
	import TaskHeader from './TaskHeader.svelte';

	let task = {
		name: 'Sample Task',
		id: '123456'
		// Other task details...
	};
</script>



<main>
	<TaskHeader taskName={task.name} taskId={task.id} />
	<!-- Other components for TaskSubHeader, TaskDescription, TaskComments, and TaskSidePanel -->
</main>

<style>
</style>
