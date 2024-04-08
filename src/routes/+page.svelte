<script>
	import Featuredlink from '$lib/components/section/Featuredlink.svelte';
	import Footer from '$lib/components/section/Footer.svelte';
	import Information from '$lib/components/section/Information.svelte';
	import Otherlinks from '$lib/components/section/Otherlinks.svelte';
</script>

<svelte:head>
	<title>My Links</title>
</svelte:head>

<main class="max-w-screen-md min-h-screen mx-auto flex flex-col px-6 py-24 gap-8">
	<!-- Information -->
	<Information />
	<!-- Featured Links -->
	<Featuredlink />
	<!-- Other Links -->
	<Otherlinks />
	<!-- Credit -->
	<Footer />
</main>
