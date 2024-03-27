<script>
	import { Carousel, Thumbnails } from 'flowbite-svelte';

	const images = [
		{
			alt: 'Image 01',
			src: '/images/slider/slider-01.webp',
			title: 'Slider Image 01'
		},
		{
			alt: 'Image 02',
			src: '/images/slider/slider-02.webp',
			title: 'Slider Image 02'
		},
		{
			alt: 'Image 03',
			src: '/images/slider/slider-03.webp',
			title: 'Slider Image 03'
		},
		{
			alt: 'Image 04',
			src: '/images/slider/slider-04.webp',
			title: 'Slider Image 04'
		},
		{
			alt: 'Image 05',
			src: '/images/slider/slider-05.webp',
			title: 'Slider Image 05'
		},
		{
			alt: 'Image 06',
			src: '/images/slider/slider-06.webp',
			title: 'Slider Image 06'
		},
		{
			alt: 'Image 07',
			src: '/images/slider/slider-07.webp',
			title: 'Slider Image 07'
		},
		{
			alt: 'Image 08',
			src: '/images/slider/slider-08.webp',
			title: 'Slider Image 08'
		},
		{
			alt: 'Image 09',
			src: '/images/slider/slider-09.webp',
			title: 'Slider Image 09'
		},
		{
			alt: 'Image 10',
			src: '/images/slider/slider-10.webp',
			title: 'Slider Image 10'
		}
	];

	let index = 0;
	let forward = true;
</script>

<section id="slider" class="px-2 sm:py-12 py-3 bg-gray-100 sm:px-6 pb-10 sm:pb-40">
	<div class="max-w-screen-xl px-4 mx-auto">
		<h1 class="text-2xl text-green-900 sm:text-3xl">DISCOVER THE BEAUTY OF THE ACRES</h1>
		<hr class="mt-4 border-gray-300 dark:border-gray-300 mb-8" />
		<Carousel
			class="w-full min-h-[300px] sm:min-h-[600px] "
			{images}
			{forward}
			let:Indicators
			let:Controls
			bind:index
		>
			<Controls />
			<Indicators class="sm:hidden"/>
		</Carousel>
		<Thumbnails class="sm:flex hidden" {images} {forward} bind:index />
	</div>
</section>
