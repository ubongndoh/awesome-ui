<script>
import NavBar from '../components/NavBar.vue';
import Footer from '../components/Footer.vue';
import Carosel from '../components/Carosel.vue';
export default {
	components: {
		NavBar,
		Footer,
		Carosel,
	},
};
</script>

<template>
	<main>
		<NavBar />
		<section>
			<div class="grid grid-cols-2 gap-2 justify-center items-center mt-16">
				<div class="px-24 -mr-10">
					<h2 class="text-2xl font-bold"
						>Lorem ipsum dolor <br />
						sit amet, consectetur</h2
					>
					<p class="leading-7 my-7 text-base"
						>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Augue et
						eros, pellentesque et. Tristique ullamcorper ac pharetra in nisi sit
						vivamus lorem.
					</p>
					<button
						class="btn flex flex-row uppercase justify-between pl-3 lg:py-5 py-10 w-3/6 border-b-2 border-transparent mb-2 text-white font-bold rounded text-left"
						>Get STARTED
						<span class="pr-4"
							><svg
								xmlns="http://www.w3.org/2000/svg"
								class="h-6 w-6"
								fill="none"
								viewBox="0 0 24 24"
								stroke="currentColor"
							>
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									stroke-width="2"
									d="M17 8l4 4m0 0l-4 4m4-4H3"
								/></svg></span
					></button>
				</div>
				<div class="w-60 mx-auto"
					><img class="" src="../assets/Group 2574.svg" alt="" />
				</div>
			</div>
			<div class="grid grid-cols-2 gap-2 mt-10">
				<div class="px-24">
					<h1 class="my-3 subtitle">MOT consectet</h1>
					<h2 class="text-2xl font-bold title">amet,consectet</h2>
					<p class="leading-7 my-7 text-base"
						>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis
						vitae nullam aliquet dignissim quis. Vel, faucibus ac justo aliquam
						donec enim, commodo fermentum vitae. Et velit sceleris
					</p>
					<button
						class="btn flex flex-row uppercase justify-between pl-3 lg:py-2 py-8 w-4/6 border-b-2 border-transparent mb-2 text-white font-bold rounded text-left"
						>Get STARTED
						<span class="pr-4"
							><svg
								xmlns="http://www.w3.org/2000/svg"
								class="h-6 w-6"
								fill="none"
								viewBox="0 0 24 24"
								stroke="currentColor"
							>
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									stroke-width="2"
									d="M17 8l4 4m0 0l-4 4m4-4H3"
								/></svg></span
					></button>
				</div>
				<div class="grid grid-cols-2 gap-1 w-full">
					<div
						class="pt-10 px-5 bg-white shadow-md cursor-pointer hover:shadow-2xl w-11/12 my-5 pb-7 rounded"
					>
						<div
							class="car w-12 h-12 flex justify-center items-center rounded mb-4"
						>
							<img src="../assets/smart-car.svg" alt="" class="w-5" />
						</div>
						<h3 class="text-lg font-semibold">Car Rental</h3>
						<p class="text-sm"
							>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis
							vitae
						</p>
					</div>
					<div
						class="pt-10 px-5 bg-white shadow-md cursor-pointer hover:shadow-2xl w-11/12 my-5 pb-7 rounded"
					>
						<div
							class="w-12 h-12 flex justify-center items-center rounded mb-4"
						>
							<img src="../assets/ship.svg" alt="" class="w-5" />
						</div>
						<h3 class="text-lg font-semibold">Boat Cruise</h3>
						<p class="text-sm"
							>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis
							vitae
						</p>
					</div>
					<div
						class="pt-10 px-5 bg-white shadow-md cursor-pointer hover:shadow-2xl w-11/12 my-5 pb-7 rounded"
					>
						<div
							class="w-12 h-12 flex justify-center items-center rounded mb-4"
						>
							<img src="../assets/bus.svg" alt="" class="w-5" />
						</div>
						<h3 class="text-lg font-semibold">Bus Trip</h3>
						<p class="text-sm"
							>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis
							vitae
						</p>
					</div>
					<div
						class="pt-10 px-5 bg-white shadow-md cursor-pointer hover:shadow-2xl w-11/12 my-5 pb-7 rounded"
					>
						<div
							class="w-12 h-12 flex justify-center items-center rounded mb-4"
						>
							<img src="../assets/driving.svg" alt="" class="w-5" />
						</div>
						<h3 class="text-lg font-semibold">Road Trip</h3>
						<p class="text-sm"
							>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis
							vitae
						</p>
					</div>
				</div>
			</div>
			<div class="mt-16 mb-10">
				<h2 class="text-center my-3 subtitle">MOT consectet</h2>
				<h3 class="text-center text-2xl font-bold title"
					>amet,consectet iquet</h3
				>
				<div class="">
					<div class="grid grid-cols-3 gap-5 mx-24">
						<div class="pt-10 px-10 bg-white shadow-2xl my-2 pb-10 rounded">
							<div
								class="w-12 h-12 flex justify-center items-center rounded mb-4"
							>
								<img src="../assets/python.svg" alt="" class="w-9/12" />
							</div>
							<h3 class="text-lg font-semibold uppercase">MOT consectet</h3>
							<p class="text-sm"
								>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit
								quis vitae
							</p>
						</div>
						<div class="pt-10 px-10 text-white my-2 pb-10 rounded dark">
							<div
								class="w-12 h-12 flex justify-center items-center rounded mb-4"
							>
								<img src="../assets/iost-(iost).svg" alt="" class="w-9/12" />
							</div>
							<h3 class="text-lg font-semibold uppercase">MOT consectet</h3>
							<p class="text-sm"
								>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit
								quis vitae
							</p>
						</div>
						<div class="pt-10 px-10 bg-white shadow-2xl my-2 pb-10 rounded">
							<div
								class="w-12 h-12 flex justify-center items-center rounded mb-4"
							>
								<img src="../assets/Vector.svg" alt="" class="w-9/12" />
							</div>
							<h3 class="text-lg font-semibold uppercase">MOT consectet</h3>
							<p class="text-sm"
								>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit
								quis vitae
							</p>
						</div>
					</div>
				</div>
			</div>
			<div class="mt-16 mb-10">
				<div class="grid grid-cols-2 gap-5 mx-24">
					<div class="flex justify-center items-center">
						<img src="../assets/Group 2571.svg" alt="" class="w-4/5" />
					</div>
					<div class="px-24">
						<h1 class="my-3 subtitle">MOT consectet</h1>
						<h2 class="text-2xl font-bold title">amet,consectet</h2>
						<p class="leading-7 my-7 text-base"
							>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sit quis
							vitae nullam aliquet dignissim quis. Vel, faucibus ac justo
							aliquam donec enim, commodo fermentum vitae. Et velit sceleris
						</p>
						<button
							class="btn flex flex-row uppercase justify-between pl-3 lg:py-2 py-8 w-4/6 border-b-2 border-transparent mb-2 text-white font-bold rounded text-left"
							>Get STARTED
							<span class="pr-4"
								><svg
									xmlns="http://www.w3.org/2000/svg"
									class="h-6 w-6"
									fill="none"
									viewBox="0 0 24 24"
									stroke="currentColor"
								>
									<path
										stroke-linecap="round"
										stroke-linejoin="round"
										stroke-width="2"
										d="M17 8l4 4m0 0l-4 4m4-4H3"
									/></svg></span
						></button>
					</div>
				</div>
			</div>
		</section>
		<Carosel />
		<Footer />
	</main>
</template>
<style scoped>
.title {
	color: #647b64;
}
.car {
	background-color: #647b64;
}
.btn {
	background-color: #647b64;
}
.subtitle {
	color: #f3b562;
}
.dark {
	background-color: #647b64;
}
</style>
