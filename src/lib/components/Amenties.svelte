<script>
	const amenties = [
		'Swimmable lagoons & lakes',
		'Floating decks',
		'Kindergarten',
		'Sports zones',
		'Event lawn & event island',
		'Treehouse viewing deck',
		'Adventure park',
		'Community clubhouse',
		'Healthcare facilities',
		'Jogging tracks',
		'Cluster gardens'
	];
</script>

<section class="bg-img-amenties">
	<div class="w-full px-6 py-10 sm:py-28 backdrop-blur-sm bg-white/80">
		<h2 class="text-green-900 text-2xl md:text-4xl lg:text-5xl text-center">Amenities</h2>
		<div
			class="flex sm:flex-row flex-col max-w-screen-xl place-items-center px-4 py-8 mx-auto gap-8 xl:gap-0 lg:py-16 md:grid-cols-3 items-start justify-between"
		>
			<ul class="max-w-md space-y-4 text-gray-700 list-inside dark:text-gray-400">
				{#each amenties.slice(0, 4) as amenty}
					<li class="flex items-center text-xl sm:text-3xl">
						<svg
							class="w-5 sm:w-6 h-5 sm:h-6 me-3 text-green-900 dark:text-green-400 flex-shrink-0"
							aria-hidden="true"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							viewBox="0 0 20 20"
						>
							<path
								d="M10 .5a9.5 9.5 0 1 0 9.5 9.5A9.51 9.51 0 0 0 10 .5Zm3.707 8.207-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414L9 10.586l3.293-3.293a1 1 0 0 1 1.414 1.414Z"
							/>
						</svg>
						{amenty}
					</li>
				{/each}
			</ul>
			<ul class="max-w-md space-y-4 text-gray-700 list-inside dark:text-gray-400">
				{#each amenties.slice(4, 8) as amenty}
					<li class="flex items-center text-xl sm:text-3xl">
						<svg
							class="w-5 sm:w-6 h-5 sm:h-6 me-3 text-green-900 dark:text-green-400 flex-shrink-0"
							aria-hidden="true"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							viewBox="0 0 20 20"
						>
							<path
								d="M10 .5a9.5 9.5 0 1 0 9.5 9.5A9.51 9.51 0 0 0 10 .5Zm3.707 8.207-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414L9 10.586l3.293-3.293a1 1 0 0 1 1.414 1.414Z"
							/>
						</svg>
						{amenty}
					</li>
				{/each}
			</ul>
			<ul class="max-w-md space-y-4 text-gray-700 list-inside dark:text-gray-400">
				{#each amenties.slice(8, 12) as amenty}
					<li class="flex items-center text-xl sm:text-3xl">
						<svg
							class="w-5 sm:w-6 h-5 sm:h-6 me-3 text-green-900 dark:text-green-400 flex-shrink-0"
							aria-hidden="true"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							viewBox="0 0 20 20"
						>
							<path
								d="M10 .5a9.5 9.5 0 1 0 9.5 9.5A9.51 9.51 0 0 0 10 .5Zm3.707 8.207-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414L9 10.586l3.293-3.293a1 1 0 0 1 1.414 1.414Z"
							/>
						</svg>
						{amenty}
					</li>
				{/each}
			</ul>
		</div>
	</div>
</section>

<style lang="scss">
	@import '$lib/styles/main.scss';
</style>
