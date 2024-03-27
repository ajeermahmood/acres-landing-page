<section id="contact" class="px-6 py-12 bg-gray-100">
	<div class="grid max-w-screen-xl grid-cols-1 px-4 py-8 mx-auto gap-3 lg:py-16 md:grid-cols-2">
		<img
			src="/images/house2.avif"
			class="h-full lg:w-10/12"
			width="996"
			height="662"
			alt="A House"
		/>
		<div>
			<h3 class="text-3xl">REGISTER YOUR INTEREST TODAY</h3>
			<p class="font-light text-sm py-2 mb-3 text-gray-500">
				Schedule a consultation with an agent
			</p>
			<form>
				<div class="mb-6 flex flex-col md:flex-row gap-5">
					<input
						type="text"
						id="name"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-purple-500 focus:border-purple-500 block w-full p-2.5"
						placeholder="Name*"
						required
					/>
					<input
						type="email"
						id="email"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-purple-500 focus:border-purple-500 block w-full p-2.5"
						placeholder="Email*"
						required
					/>
				</div>
				<div class="mb-6 flex flex-col md:flex-row gap-5">
					<input
						type="text"
						id="number"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-purple-500 focus:border-purple-500 block w-full p-2.5"
						placeholder="Contact Number*"
						required
					/>
					<input
						type="text"
						id="disabled"
						class="opacity-0 bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-purple-500 focus:border-purple-500 block w-full p-2.5"
						disabled
					/>
				</div>
				<textarea
					id="comment"
					rows="4"
					class="w-full px-3 py-3 text-sm text-gray-900 bg-gray-50 border rounded-lg border-gray-300 focus:ring-0 mb-6"
					placeholder="Description"
					required
				/>
				<button
					type="button"
					class="w-full text-white bg-purple-700 hover:bg-purple-800 focus:ring-4 focus:outline-none focus:ring-purple-300 font-medium rounded-lg text-sm px-4 py-4 text-center mr-3 md:mr-0"
					>Contact Us</button
				>
			</form>
		</div>
	</div>
</section>

<style lang="scss">
	@import '$lib/styles/main.scss';
</style>
