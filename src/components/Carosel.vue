<template>
	<div>
		<div class="px-24">
			<h1 class="my-3 subtitle">MOT consectet</h1>
			<h2 class="text-2xl font-bold title">amet,consectet</h2>
		</div>
		<Carousel :autoplay="2000" :items-to-show="3" :wrap-around="true">
			<Slide v-for="(slide, index) in slides" :key="index">
				<div class="px-4 py-10">
					<div class="flex flex-row my-4 px-4">
						<div class="">
							<img :src="slide.img" alt="" class=" " />
						</div>
						<div>
							<div class="text-sm">
								{{ slide.title }}
							</div>
							<div>
								{{ slide.name }}
							</div>
						</div>
					</div>
					<div class="px-4 bg-gradient-to-t from-slate-300 to-white rounded">
						{{ slide.description }}
					</div>
				</div>
			</Slide>

			<!-- <template #addons>
			<Navigation />
			<Pagination />
		</template> -->
		</Carousel>
	</div>
</template>

<script>
import { defineComponent } from 'vue';
import { Carousel, Navigation, Pagination, Slide } from 'vue3-carousel';

import 'vue3-carousel/dist/carousel.css';
import img1 from '../assets/tayo1.svg';
import img2 from '../assets/tayo2.svg';
import img3 from '../assets/tayo3.svg';

export default defineComponent({
	name: 'Autoplay',
	components: {
		Carousel,
		Slide,
		Pagination,
		Navigation,
	},

	data() {
		return {
			slides: [
				{
					title: 'CTO May & Baker',
					name: 'Tayo Oshinuwa',
					img: img1,
					description:
						'“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis vitae“',
				},
				{
					title: 'CTO May & Baker',
					name: 'Tayo Oshinuwa',
					img: img2,
					description:
						'“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis vitae“',
				},
				{
					title: 'CTO May & Baker',
					name: 'Tayo Oshinuwa',
					img: img3,
					description:
						'“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis vitae“',
				},
				{
					title: 'CTO May & Baker',
					name: 'Tayo Oshinuwa',
					img: img2,
					description:
						'“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis vitae“',
				},
			],
		};
	},
});
</script>

<style>
.title {
	color: #647b64;
}
.subtitle {
	color: #f3b562;
}
</style>
