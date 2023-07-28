<script lang="ts">
  export let taskName: string = "";
  export let taskId: string = "";
</script>

<div class="bg-primary-500/50 w-full text-secondary px-4 py-1 h-16">
  <h1 class="text-2xl font-bold">{ taskName }</h1>
  <p class="text-sm">Task ID: { taskId }</p>
</div>

<style>
  /* You can customize the styles here or create a separate CSS file and import it */
</style>
