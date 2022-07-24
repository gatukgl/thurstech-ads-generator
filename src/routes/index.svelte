<script>
	import image from '../example-ads.jpg';
</script>

<div class="container mx-auto">
	<h1 class="text-2xl font-bold leading-7 text-gray-900 sm:text-3xl sm:truncate">
		Thurstech Ads Generator
	</h1>

	<slot name="ads">
		<img src={image} width="1000px" alt="ThursTech Ads Template" />
	</slot>
</div>
