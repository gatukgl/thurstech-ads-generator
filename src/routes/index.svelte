<div class="container mx-auto my-5">
	<h1 class="text-2xl font-bold leading-7 text-gray-900 sm:text-3xl sm:truncate mb-5">
		Thurstech Ads Generator
	</h1>

	<slot name="ads-form">
		<div class="mt-10 sm:mt-0">
			<div class="md:grid md:grid-cols-3 md:gap-6">
			  <div class="mt-5 md:mt-0 md:col-span-2">
				<form >
				  <div class="shadow overflow-hidden sm:rounded-md">
					<div class="px-4 py-5 bg-white sm:p-6">
					  <div class="grid grid-cols-6 gap-6">
						<div class="col-span-6">
						  <label for="first-name" class="block text-sm font-medium text-gray-700">Date</label>
						  <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
						</div>

						<div class="col-span-6">
							First Speaker: 
						</div>
						<div class="col-span-6 sm:col-span-3">
						  <label for="first-name" class="block text-sm font-medium text-gray-700">Name</label>
						  <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
						</div>
						<div class="col-span-6 sm:col-span-3">
						  <label for="last-name" class="block text-sm font-medium text-gray-700">Talk</label>
						  <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
						</div>
						<div class="col-span-6 sm:col-span-3">
						  <label for="last-name" class="block text-sm font-medium text-gray-700">Job title</label>
						  <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
						</div>
						<div class="col-span-6 sm:col-span-3">
						  <label for="last-name" class="block text-sm font-medium text-gray-700">Company</label>
						  <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
						</div>
						<div class="col-span-6 sm:col-span-3">
						  <label for="last-name" class="block text-sm font-medium text-gray-700">Image</label>
						  <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
						</div>
					</div>
					<div class="px-4 py-3 bg-gray-50 text-right sm:px-6">
					  <button type="submit" class="inline-flex justify-center py-2 px-4 border border-transparent shadow-sm text-sm font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">Save</button>
					</div>
				  </div>
				</form>
			  </div>
			</div>
		  </div>
	</slot>

	<div id="ads">
		Test
	</div>
</div>

<style>
	#ads {
		background-image: url('../example-ads.jpg');
		background-repeat: no-repeat;
		background-size: auto;
		width: 800px;
		height: 533px;
	}
</style>
