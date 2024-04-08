<script>
	import socials from '$lib/data/social.json';
	import Social from '../Social.svelte';
</script>

<section class="w-full p-5 flex flex-col gap-5 text-center relative">
	<div class="flex flex-col gap-3">
		<img class="block mx-auto w-24" src="/images/avatar.webp" alt="Avatar" />
		<h1 class="font-bold text-xl relative">Muhammad Surya J</h1>
	</div>
	<div class="lg:w-96 mx-auto">
		<p class="font-medium">
			A tea drinker who loves coding and hopes to become a Frontend Developer
		</p>
	</div>
	<div class="flex flex-row gap-5 mx-auto">
		{#each socials as item}
			<Social url={item.url} title={item.title} images={item.images} />
		{/each}
	</div>
</section>
