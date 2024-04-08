<script>
	export let title = '';
	export let images = '';
	export let url = '';
</script>

<a class="link" href={url}>
	<div class="w-full border-2 border-black rounded-full p-2 box">
		<div class="flex justify-between items-center">
			<div class="flex items-center gap-3">
				<img class="w-10 h-auto" src={images} alt={title} />
				{title}
			</div>
			<img class="w-6 h-auto mr-2 arrow" src="/images/icon/arrow.png" alt="Arrow" />
		</div>
	</div>
</a>
