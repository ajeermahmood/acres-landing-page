<script>
	import Contents from '$lib/components/Contents.svelte';
	import Location from '$lib/components/Location.svelte';
	import Slider from '$lib/components/Slider.svelte';
	import Amenties from '$lib/components/Amenties.svelte';
	import Contact from '$lib/components/Contact.svelte';
</script>

<svelte:head>
	<title>THE ACRES DUBAI BY MERAAS - DUBAI PROPERTIES</title>
	<meta name="description" content="Real Estate Template with Svelte and TailwindCss" />
</svelte:head>

<section id="hero" class="bg-gray-100 bg-img-main">
	<div class="relative isolate pt-14 lg:px-8 backdrop-blur-sm bg-black/45">
		<div class="w-full flex flex-row justify-center">
			<div class="flex-col text-center max-w-sm">
				<h1 class="text-2xl tracking-tight text-white sm:text-4xl mb-5">THE ACRES DUBAI</h1>
				<h1 class="text-2xl tracking-tight text-white sm:text-4xl">BY MERAAS - DUBAI PROPERTIES</h1>
			</div>
		</div>
		<div class="mx-auto max-w-3xl py-20 sm:py-48 lg:py-40">
			<div class="text-center">
				<h1 class="text-4xl tracking-tight text-white sm:text-7xl">
					STANDALONE VILLAS IN DUBAI AT THE ACRES - NOW LAUNCHED
				</h1>
				<hr class="mt-4 border-white dark:border-white mx-6" />
				<p class="mt-2 text-lg leading-8 text-white px-5">
					New off-plan luxury villas for families at The Acres Dubai. LIMITED TIME OFFER -
					Complimentary private pool with all units
				</p>
				<div class="mt-10 flex items-center justify-center gap-x-6 sm:flex-row flex-col">
					<a
						href="#contact"
						class="mb-3 btn-acres-invert px-4 sm:px-5 py-3 sm:py-4 text-lg sm:text-xl font-semibold text-black shadow-sm focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
						>Register Interest</a
					>
					<a
						href="#"
						class="mb-3 btn-acres px-4 sm:px-5 py-3 sm:py-4 text-lg sm:text-xl font-semibold text-black shadow-sm focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
						>Download Brochure</a
					>
				</div>
			</div>
		</div>
		<div
			class="absolute inset-x-0 top-[calc(100%-13rem)] -z-10 transform-gpu overflow-hidden blur-3xl sm:top-[calc(100%-30rem)]"
			aria-hidden="true"
		/>
	</div>
</section>

<Contents />
<Location />
<Slider />
<Amenties />
<Contact />

<style lang="scss">
	@import '$lib/styles/main.scss';
</style>
