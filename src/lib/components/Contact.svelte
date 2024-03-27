<section id="contact" class="sm:px-6 px-2 py-12 bg-gray-100">
	<div class="grid max-w-screen-xl grid-cols-1 px-4 py-8 mx-auto gap-3 lg:py-16 md:grid-cols-2">
		<img
			src="/images/slider/slider-27.webp"
			class="cover sm:w-5/6 w-full"
			width="600"
			height="200"
			alt="A House"
		/>
		<div>
			<h3 class="text-2xl text-green-900 sm:text-3xl mt-4 sm:mt-0">REGISTER YOUR INTEREST TODAY</h3>
			<p class="font-light text-sm py-2 mb-3 text-gray-500">
				To find out about availability, fill out the form and we'll be in touch.
			</p>
			<!-- <div class="flex justify-end mb-5">
				<a class="mr-6" href="#"><img src="/images/whatsapp.png" alt="whatsapp" width="30" height="30" /></a>
				<a class="mr-6" href="#"><img src="/images/call.png" alt="whatsapp" width="30" height="30" /></a>
				<a class="mr-6" href="#"><img src="/images/mail.png" alt="whatsapp" width="30" height="30" /></a>
			</div> -->
			<hr class="mt-0 border-gray-300 dark:border-gray-300 mb-4" />
			<form>
				<div class="mb-6 flex flex-col md:flex-row gap-5">
					<input
						type="text"
						id="name"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-lg focus:ring-green-700 focus:border-green-700 block w-full p-2.5"
						placeholder="Name*"
						required
					/>
					<input
						type="email"
						id="email"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-lg focus:ring-green-700 focus:border-green-700 block w-full p-2.5"
						placeholder="Email*"
						required
					/>
				</div>
				<div class="mb-4 flex flex-col md:flex-row gap-5">
					<input
						type="text"
						id="number"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-lg focus:ring-green-700 focus:border-green-700 block w-full p-2.5"
						placeholder="Contact Number*"
						required
					/>
					<input
						type="text"
						id="disabled"
						class="opacity-0 hidden w-full p-2.5 sm:block"
						disabled
					/>
				</div>
				<h2 class="mb-4">How many bedrooms are you interested in?*</h2>
				<div class="flex sm:flex-row flex-col w-full mb-6 gap-3">
					<div class="w-full flex items-center ps-4 border border-gray-300 rounded dark:border-gray-700 bg-gray-50">
						<input
							id="bordered-radio-1"
							type="radio"
							value=""
							name="bordered-radio"
							class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
						/>
						<label
							for="bordered-radio-1"
							class="w-full py-4 ms-2 text-gray-600 text-md"
							>3 Bedroom Villas</label
						>
					</div>
					<div class="w-full flex items-center ps-4 border border-gray-300 rounded dark:border-gray-700 bg-gray-50">
						<input
							checked
							id="bordered-radio-2"
							type="radio"
							value=""
							name="bordered-radio"
							class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
						/>
						<label
							for="bordered-radio-2"
							class="w-full py-4 ms-2 text-gray-600 text-md"
							>4 Bedroom Villas</label
						>
					</div>
					<div class="w-full flex items-center ps-4 border border-gray-300 rounded dark:border-gray-700 bg-gray-50">
						<input
							checked
							id="bordered-radio-3"
							type="radio"
							value=""
							name="bordered-radio"
							class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
						/>
						<label
							for="bordered-radio-3"
							class="w-full py-4 ms-2 text-gray-600 text-md"
							>5 Bedroom Villas</label
						>
					</div>
				</div>
				<textarea
					id="comment"
					rows="4"
					class="w-full px-3 py-3 text-gray-900 bg-gray-50 border text-lg focus:ring-green-700 focus:border-green-700 border-gray-300 mb-2"
					placeholder="Description"
					required
				/>
				<span class="font-light text-sm py-2 mb-1 text-gray-500">
					By clicking Submit, you agree to our <a href="#"><u><b>Terms and Conditions</b></u></a>
					and
					<a href="#"><u><b>Privacy Policy</b></u></a>.
				</span>
				<button
					type="button"
					class="mt-5 w-full text-white bg-green-700 hover:bg-green-800 focus:ring-4 focus:outline-none focus:ring-green-100 font-medium text-xl px-4 py-4 text-center mr-3 md:mr-0"
					>Contact Us</button
				>
			</form>
		</div>
	</div>
</section>

<style lang="scss">
	@import '$lib/styles/main.scss';
</style>
