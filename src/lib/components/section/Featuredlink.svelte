<script>
	import featuredlinks from '$lib/data/featuredlinks.json';
	import Box from '../Box.svelte';
</script>

<section class="lg:w-9/12 w-full mx-auto">
	<h1 class="uppercase text-gray-400 font-medium text-xs mb-2 text-center">Featured Links</h1>
	<div class="flex flex-col gap-5">
		{#each featuredlinks as item}
			<Box title={item.title} url={item.url} images={item.images} />
		{/each}
	</div>
</section>
