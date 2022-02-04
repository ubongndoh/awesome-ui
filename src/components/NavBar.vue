<script setup></script>

<template>
	<header
		class="lg:px-16 px-6 bg-white flex flex-wrap items-center lg:py-0 py-2 mt-4"
	>
		<div class="flex-1 flex justify-between items-center">
			<a href="#">
				<div class="flex flex-row justify-between items-center">
					<img src="../assets/A U.svg" alt="" />
					<span class="uppercase mx-4 font-bold text-2xl title1"
						>awesome ui</span
					>
				</div>
			</a>
		</div>

		<label for="menu-toggle" class="pointer-cursor lg:hidden block"
			><svg
				class="fill-current text-gray-900"
				xmlns="http://www.w3.org/2000/svg"
				width="20"
				height="20"
				viewBox="0 0 20 20"
			>
				<title>menu</title>
				<path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path></svg
		></label>
		<input class="hidden" type="checkbox" id="menu-toggle" />

		<div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
			<nav>
				<ul
					class="lg:flex items-center justify-between text-base text-gray-700 pt-4 lg:pt-0"
				>
					<li
						><a
							class="lg:p-4 py-3 px-0 block border-b-2 border-transparent lg:hover:border-emerald-600 uppercase"
							href="#"
							>About Us</a
						></li
					>
					<li
						><a
							class="lg:p-4 py-3 px-0 block border-b-2 border-transparent lg:hover:border-emerald-600 uppercase"
							href="#"
							>Contact Us</a
						></li
					>
					<li
						><a
							class="lg:p-4 py-3 px-0 block border-b-2 border-transparent lg:hover:border-emerald-600 uppercase"
							href="#"
							>Store</a
						></li
					>
					<li
						><a
							class="lg:p-4 py-3 px-0 block border-b-2 border-transparent lg:hover:border-emerald-600 lg:mb-0 mb-2 uppercase"
							href="#"
							>Use Cases</a
						></li
					><li
						><a
							class="lg:py-2 py-3 px-7 block border-b-2 border-transparent bg-emerald-600 lg:mb-0 mb-2 text-white font-bold lg:ml-6 uppercase rounded"
							href="#"
							>Register</a
						></li
					>
				</ul>
			</nav>
		</div>
	</header>
</template>

<style scoped>
#menu-toggle:checked + #menu {
	display: block;
}

.title1 {
	color: #647b64;
}
</style>
