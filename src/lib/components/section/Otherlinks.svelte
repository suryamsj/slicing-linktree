<script>
	import otherlinks from '$lib/data/otherlinks.json';
	import Box from '../Box.svelte';
</script>

<section class="lg:w-9/12 w-full mx-auto">
	<h1 class="uppercase text-gray-400 font-medium text-xs mb-2 text-center">Other Links</h1>
	<div class="flex flex-col gap-5">
		{#each otherlinks as item}
			<Box title={item.title} url={item.url} images={item.images} />
		{/each}
	</div>
</section>
