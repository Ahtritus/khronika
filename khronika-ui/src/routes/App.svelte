<script lang="ts">
	import { AppBar } from '@skeletonlabs/skeleton';
	import { LightSwitch } from '@skeletonlabs/skeleton';
	import { Accordion, AccordionItem } from '@skeletonlabs/skeleton';
</script>

<AppBar gridColumns="grid-cols-3" slotDefault="place-self-center" slotTrail="place-content-end">
	<svelte:fragment slot="lead">
		<svg xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 576 512"
			><!--! Font Awesome Free 6.4.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path
				d="M575.8 255.5c0 18-15 32.1-32 32.1h-32l.7 160.2c0 2.7-.2 5.4-.5 8.1V472c0 22.1-17.9 40-40 40H456c-1.1 0-2.2 0-3.3-.1c-1.4 .1-2.8 .1-4.2 .1H416 392c-22.1 0-40-17.9-40-40V448 384c0-17.7-14.3-32-32-32H256c-17.7 0-32 14.3-32 32v64 24c0 22.1-17.9 40-40 40H160 128.1c-1.5 0-3-.1-4.5-.2c-1.2 .1-2.4 .2-3.6 .2H104c-22.1 0-40-17.9-40-40V360c0-.9 0-1.9 .1-2.8V287.6H32c-18 0-32-14-32-32.1c0-9 3-17 10-24L266.4 8c7-7 15-8 22-8s15 2 21 7L564.8 231.5c8 7 12 15 11 24z"
			/></svg
		>
	</svelte:fragment>
	<h1 class="h1">Khronika</h1>
	<svelte:fragment slot="trail"><LightSwitch /></svelte:fragment>
</AppBar>

<div class="w-full p-10">
	<div class="w-full text-token grid grid-cols-1 md:grid-cols-2 gap-4">
		<div class="card bg-initial p-4 flex justify-center items-center"><span>Minimal</span></div>
		<a class="card bg-initial card-hover overflow-hidden" href="/"
			><header>
				<img
					src="https://images.unsplash.com/photo-1620562303747-ba21ca6f1530?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzY2MjR8&amp;ixlib=rb-4.0.3&amp;w=400&amp;h=175&amp;auto=format&amp;fit=crop"
					class="bg-black/50 w-full aspect-[21/9]"
					alt="Post"
				/>
			</header>
			<div class="p-4 space-y-4">
				<h6 class="h6">Announcements</h6>
				<h3 class="h3" data-toc-ignore="">Skeleton is Awesome!</h3>
				<article>
					<p>
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam aspernatur provident
						eveniet eligendi cumque consequatur tempore sint nisi sapiente. Iste beatae laboriosam
						iure molestias cum expedita architecto itaque quae rem.
					</p>
				</article>
			</div>
			<hr class="opacity-50" />
			<footer class="p-4 flex justify-start items-center space-x-4">
				<figure
					class="avatar flex aspect-square text-surface-50 font-semibold justify-center items-center overflow-hidden isolate bg-surface-400-500-token w-8 rounded-full"
					data-testid="avatar"
				>
					<img
						class="avatar-image w-full h-full object-cover"
						src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&amp;ixlib=rb-4.0.3&amp;w=32&amp;h=32&amp;auto=format&amp;fit=crop"
						alt=""
						style=""
					/>
				</figure>
				<div class="flex-auto flex justify-between items-center">
					<h6 class="font-bold">By Alex</h6>
					<small>On 7/27/2023</small>
				</div>
			</footer></a
		>
	</div>

	
<Accordion>
	<AccordionItem open>
		<svelte:fragment slot="lead"><h3 class="h3"><svg xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M287.9 0c9.2 0 17.6 5.2 21.6 13.5l68.6 141.3 153.2 22.6c9 1.3 16.5 7.6 19.3 16.3s.5 18.1-5.9 24.5L433.6 328.4l26.2 155.6c1.5 9-2.2 18.1-9.6 23.5s-17.3 6-25.3 1.7l-137-73.2L151 509.1c-8.1 4.3-17.9 3.7-25.3-1.7s-11.2-14.5-9.7-23.5l26.2-155.6L31.1 218.2c-6.5-6.4-8.7-15.9-5.9-24.5s10.3-14.9 19.3-16.3l153.2-22.6L266.3 13.5C270.4 5.2 278.7 0 287.9 0zm0 79L235.4 187.2c-3.5 7.1-10.2 12.1-18.1 13.3L99 217.9 184.9 303c5.5 5.5 8.1 13.3 6.8 21L171.4 443.7l105.2-56.2c7.1-3.8 15.6-3.8 22.6 0l105.2 56.2L384.2 324.1c-1.3-7.7 1.2-15.5 6.8-21l85.9-85.1L358.6 200.5c-7.8-1.2-14.6-6.1-18.1-13.3L287.9 79z"/></svg></h3></svelte:fragment>
		<svelte:fragment slot="summary"><h3 class="h3">Item 1</h3></svelte:fragment>
		<svelte:fragment slot="content">Content 1</svelte:fragment>
	</AccordionItem>
	<AccordionItem>
		<svelte:fragment slot="lead"><svg xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M287.9 0c9.2 0 17.6 5.2 21.6 13.5l68.6 141.3 153.2 22.6c9 1.3 16.5 7.6 19.3 16.3s.5 18.1-5.9 24.5L433.6 328.4l26.2 155.6c1.5 9-2.2 18.1-9.6 23.5s-17.3 6-25.3 1.7l-137-73.2L151 509.1c-8.1 4.3-17.9 3.7-25.3-1.7s-11.2-14.5-9.7-23.5l26.2-155.6L31.1 218.2c-6.5-6.4-8.7-15.9-5.9-24.5s10.3-14.9 19.3-16.3l153.2-22.6L266.3 13.5C270.4 5.2 278.7 0 287.9 0zm0 79L235.4 187.2c-3.5 7.1-10.2 12.1-18.1 13.3L99 217.9 184.9 303c5.5 5.5 8.1 13.3 6.8 21L171.4 443.7l105.2-56.2c7.1-3.8 15.6-3.8 22.6 0l105.2 56.2L384.2 324.1c-1.3-7.7 1.2-15.5 6.8-21l85.9-85.1L358.6 200.5c-7.8-1.2-14.6-6.1-18.1-13.3L287.9 79z"/></svg></svelte:fragment>
		<svelte:fragment slot="summary">Item 2</svelte:fragment>
		<svelte:fragment slot="content">Content 2</svelte:fragment>
	</AccordionItem>
</Accordion>


</div>
