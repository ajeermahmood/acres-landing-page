<script>
	export let type;

	export let opened = true;

	const dataSubmit = async () => {
		if (type == 'DOWNLOAD BROCHURE') {
			window.open(
				'https://ireproperty.com/ain_al_nisr/acres/files/The%20Acres%20Brochure-English.pdf',
				'_blank'
			);
		} else {
			window.open(
				'https://ireproperty.com/ain_al_nisr/acres/files/The%20Acres%20Updated%20Floorplans.pdf',
				'_blank'
			);
		}
	};
</script>

{#if opened}
	<div class="relative z-10" aria-labelledby="modal-title" role="dialog" aria-modal="true">
		<div class="fixed inset-0 bg-gray-500 bg-opacity-75 transition-opacity" />

		<div class="fixed inset-0 z-10 w-screen overflow-y-auto">
			<div class="flex min-h-full items-end justify-center p-4 text-center sm:items-center sm:p-0">
				<div
					class="relative transform overflow-hidden rounded-lg bg-white text-left shadow-xl transition-all sm:my-8 sm:w-full sm:max-w-lg"
				>
					<div class="bg-white p-4 sm:p-7">
						<div class="sm:flex sm:items-start">
							<div>
								<div class="flex justify-between items-center">
									<h3 class="text-2xl text-green-900 sm:text-3xl">
										{type}
									</h3>
									<button
										on:click={() => {
											opened = false;
										}}
										><svg
											class="cursor-pointer"
											xmlns="http://www.w3.org/2000/svg"
											x="0px"
											y="0px"
											width="20"
											height="20"
											viewBox="0 0 30 30"
										>
											<path
												d="M 7 4 C 6.744125 4 6.4879687 4.0974687 6.2929688 4.2929688 L 4.2929688 6.2929688 C 3.9019687 6.6839688 3.9019687 7.3170313 4.2929688 7.7070312 L 11.585938 15 L 4.2929688 22.292969 C 3.9019687 22.683969 3.9019687 23.317031 4.2929688 23.707031 L 6.2929688 25.707031 C 6.6839688 26.098031 7.3170313 26.098031 7.7070312 25.707031 L 15 18.414062 L 22.292969 25.707031 C 22.682969 26.098031 23.317031 26.098031 23.707031 25.707031 L 25.707031 23.707031 C 26.098031 23.316031 26.098031 22.682969 25.707031 22.292969 L 18.414062 15 L 25.707031 7.7070312 C 26.098031 7.3170312 26.098031 6.6829688 25.707031 6.2929688 L 23.707031 4.2929688 C 23.316031 3.9019687 22.682969 3.9019687 22.292969 4.2929688 L 15 11.585938 L 7.7070312 4.2929688 C 7.5115312 4.0974687 7.255875 4 7 4 z"
											/>
										</svg></button
									>
								</div>
								<form class="mt-6" on:submit|preventDefault={dataSubmit}>
									<div class="mb-6 flex flex-col md:flex-row gap-5">
										<input
											type="text"
											id="name"
											class="bg-gray-50 border border-gray-300 text-gray-900 text-lg focus:ring-green-700 focus:border-green-700 block w-full p-2.5"
											placeholder="Name*"
											required
										/>
									</div>
									<div class="mb-6 flex flex-col md:flex-row gap-5">
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
									</div>

									<span class="font-light text-sm py-2 mb-1 text-gray-500">
										By clicking Download, you agree to our <a href="#"
											><u><b>Terms and Conditions</b></u></a
										>
										and
										<a href="#"><u><b>Privacy Policy</b></u></a>.
									</span>
									<button
										type="submit"
										class="mt-5 w-full text-white bg-green-700 hover:bg-green-800 focus:ring-4 focus:outline-none focus:ring-green-100 font-medium text-xl px-4 py-4 text-center mr-3 md:mr-0"
										>{type}</button
									>
								</form>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
{/if}
