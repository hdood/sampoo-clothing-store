<template>

	<Head>
		<title>Sampoo</title>
	</Head>
	<header
		class="flex flex-col items-center  sm:justify-start sm:flex-nowrap z-50 w-full bg-emerald-200 text-sm py-4 dark:bg-gray-800 min-h-screen">
		<nav class="w-full mx-auto flex px-8 justify-between lg:px-20 max-h-fit items-center h-10" aria-label="Global">
			<a class="flex-none text-3xl dark:text-white font-elefante font-medium" href="#">Sampoo</a>

			<div class="lg:flex md:flex flex-row gap-5 mt-5 sm:mt-0 sm:pl-5 hidden">
				<a class="font-medium text-emerald-800" href="#" aria-current="page">Home</a>
				<a
					class="font-medium text-gray-600 hover:text-gray-400 dark:text-gray-400 dark:hover:text-gray-500"
					href="#"
					>SHOP</a
				>
					<a
					class="font-medium text-gray-600 hover:text-gray-400 dark:text-gray-400 dark:hover:text-gray-500"
					href="#"
					>FEATURES</a
				>
				<a
				class="font-medium text-gray-600 hover:text-gray-400 dark:text-gray-400 dark:hover:text-gray-500"
				href="#"
				>CONTACT</a
			>
			</div>
			<div>
				<button
					type="button"
					class="py-1 px-4 inline-flex justify-center items-center gap-2 rounded-md border-2 border-emerald-800 font-semibold text-emerald-800 hover:text-white focus:outline-none transition-all text-sm dark:border-gray-700">
					Login
				</button>
			</div>
		</nav>
		<!-- Hero -->
		<div class="max-w-[85rem] mx-auto px-4 sm:px-6 lg:px-8 flex justify-center mt-20">
			<!-- Grid -->
			<div class="grid md:grid-cols-2 gap-4 md:gap-8 xl:gap-20 md:items-center px-9 lg:px-20 lg:ml-32">
				<div>
					<h1
						class="block text-xl font-bold text-gray-800  lg:text-5xl lg:leading-tight dark:text-white">
						Discover and Find Your Own Fashion!
					</h1>
					<p class="mt-3 lg:text-lg text-gray-800 dark:text-gray-400">
						Explore our curated collection of stylish clothing and accessories tailored to your unique
						taste.
					</p>

					<!-- Buttons -->
					<div class="mt-7 grid gap-3 w-full sm:inline-flex">
						<a
							class="inline-flex justify-center items-center gap-x-3 text-center bg-emerald-600 hover:bg-emerald-700 border border-transparent text-sm lg:text-base text-white font-medium rounded-md focus:outline-none focus:ring-2 focus:ring-emerald-600 focus:ring-offset-2 focus:ring-offset-white transition py-3 lg:px-4 px-3 dark:focus:ring-offset-gray-800"
							href="#">
							Explore Now
							<svg class="w-2.5 h-2.5" width="16" height="16" viewBox="0 0 16 16" fill="none">
								<path
									d="M5.27921 2L10.9257 7.64645C11.1209 7.84171 11.1209 8.15829 10.9257 8.35355L5.27921 14"
									stroke="currentColor"
									stroke-width="2"
									stroke-linecap="round" />
							</svg>
						</a>
					</div>
					<!-- End Buttons -->
				</div>
				<!-- End Col -->

				<div class="relative ml-1 lg:ml-4">
					<div
						class="lg:h-[25rem] lg:w-[20rem] h-[20rem] w-[15rem] bg-emerald-500 lg:rounded-tl-[4rem] lg:rounded-br-[4rem] lg:rounded-tr-3xl lg:rounded-bl-3xl lg:relative">
						<img src="@/assets/images/hero-image.png" alt="" class="absolute bottom-0" srcset="" />
					</div>
				</div>
				<!-- End Col -->
			</div>
			<!-- End Grid -->
		</div>
		<!-- End Hero -->
	</header>

	<!-- Team -->
	<div class="max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-14 mx-auto">
		<!-- Title -->
		<div class="max-w-2xl mx-auto text-center mb-10 lg:mb-14 text-emerald-800">
			<h2 class="text-2xl font-bold md:text-4xl md:leading-tight dark:text-white">Best selling</h2>
			<p class="mt-1">Get in on the trend with our curated selection of best-selling styles.</p>
		</div>
		<!-- End Title -->

		<!-- Grid -->
		<div class="flex justify-center gap-8 flex-wrap">
			<div>
				<div class="lg:h-[20rem] lg:w-[15rem] bg-[#93B9A2] relative">
					<img src="@/assets/images/best-selling-1.png" class="" alt="" srcset="" />
				</div>
				<div class="flex flex-col items-center mt-6 gap-3">
					<div class="font-medium">Regular Fit Long Sleeve Top</div>
					<div class="flex gap-5 opacity-80 justify-center items-center">
						<div>$38.99</div>
						<div>|</div>
						<div class="flex items-center gap-1">
							<span>4.5</span>
							<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 256 256">
								<path
									fill="#f5d426"
									d="m234.5 114.38l-45.1 39.36l13.51 58.6a16 16 0 0 1-23.84 17.34l-51.11-31l-51 31a16 16 0 0 1-23.84-17.34l13.49-58.54l-45.11-39.42a16 16 0 0 1 9.11-28.06l59.46-5.15l23.21-55.36a15.95 15.95 0 0 1 29.44 0L166 81.17l59.44 5.15a16 16 0 0 1 9.11 28.06Z" />
							</svg>
						</div>
					</div>
				</div>
			</div>
			<div>
				<div class="lg:h-[20rem] lg:w-[15rem] bg-[#A9D4BA] relative">
					<img src="@/assets/images/best-selling-2.png" class="" alt="" srcset="" />
				</div>
				<div class="flex flex-col items-center mt-6 gap-3">
					<div class="font-medium">Regular Fit Long Sleeve Top</div>
					<div class="flex gap-5 opacity-80 justify-center items-center">
						<div>$62.99</div>
						<div>|</div>
						<div class="flex items-center gap-1">
							<span>4.5</span>
							<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 256 256">
								<path
									fill="#f5d426"
									d="m234.5 114.38l-45.1 39.36l13.51 58.6a16 16 0 0 1-23.84 17.34l-51.11-31l-51 31a16 16 0 0 1-23.84-17.34l13.49-58.54l-45.11-39.42a16 16 0 0 1 9.11-28.06l59.46-5.15l23.21-55.36a15.95 15.95 0 0 1 29.44 0L166 81.17l59.44 5.15a16 16 0 0 1 9.11 28.06Z" />
							</svg>
						</div>
					</div>
				</div>
			</div>
			<div>
				<div class="lg:h-[20rem] lg:w-[15rem] bg-[#A9D4BA] relative">
					<img src="@/assets/images/best-selling-3.png" class="" alt="" srcset="" />
				</div>
				<div class="flex flex-col items-center mt-6 gap-3">
					<div class="font-medium">Regular Fit Long Sleeve Top</div>
					<div class="flex gap-5 opacity-80 justify-center items-center">
						<div>$48.99</div>
						<div>|</div>
						<div class="flex items-center gap-1">
							<span>4.5</span>
							<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 256 256">
								<path
									fill="#f5d426"
									d="m234.5 114.38l-45.1 39.36l13.51 58.6a16 16 0 0 1-23.84 17.34l-51.11-31l-51 31a16 16 0 0 1-23.84-17.34l13.49-58.54l-45.11-39.42a16 16 0 0 1 9.11-28.06l59.46-5.15l23.21-55.36a15.95 15.95 0 0 1 29.44 0L166 81.17l59.44 5.15a16 16 0 0 1 9.11 28.06Z" />
							</svg>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- End Grid -->
	</div>

	<div class="max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-14 mx-auto">
		<!-- Title -->
		<div class="max-w-2xl mx-auto text-center mb-10 lg:mb-14 text-emerald-800">
			<h2 class="text-2xl font-bold md:text-4xl md:leading-tight dark:text-white">Our Products</h2>
			<TabGroup>
				<TabList as="div" class="flex flex-col lg-flex-row items-center lg:gap-20 justify-center mt-10 gap-3">
					<Tab v-slot="{ selected }" as="div" class="focus:outline-none focus:border-none cursor-pointer">
						<span :class="[selected && 'border-b-2 pb-2 border-emerald-600']">SALE</span>
					</Tab>
					<Tab v-slot="{ selected }" as="div" class="focus:outline-none focus:border-none cursor-pointer">
						<span :class="[selected && 'border-b-2 pb-2 border-emerald-600']">HOT</span>
					</Tab>
					<Tab v-slot="{ selected }" as="div" class="focus:outline-none focus:border-none cursor-pointer">
						<span :class="[selected && 'border-b-2 pb-2 border-emerald-600']">NEW ARRIVALS</span>
					</Tab>
					<Tab v-slot="{ selected }" as="div" class="focus:outline-none focus:border-none cursor-pointer">
						<span :class="[selected && 'border-b-2 pb-2 border-emerald-600']">ACCESSORIES</span>
					</Tab>
				</TabList>
				<TabPanels as="div" class="mt-10 ">
					<TabPanel><Sale /></TabPanel>
					<TabPanel><Hot /></TabPanel>
					<TabPanel><Sale /></TabPanel>
					<TabPanel><Hot /></TabPanel>
				</TabPanels>
			</TabGroup>
		</div>
		<!-- End Title -->
	</div>

	<div class="lg:w-8/12 mx-auto bg-emerald-200 overflow-hidden pt-4 lg:pt-0">
		<!-- Hero -->
		<div class="max-w-[85rem] mx-auto px-4 sm:px-6 lg:px-8">
			<!-- Grid -->
			<div class="grid md:grid-cols-2 gap-4 md:gap-8 xl:gap-20 md:items-center">
				<div class="relative ml-4 hidden lg:block">
					<img class="w-full rounded-md" src="~/assets/images/offer.png" alt="Image Description" />
					<div
						class="absolute inset-0 -z-[1] bg-gradient-to-tr from-gray-200 via-white/0 to-white/0 w-full h-full rounded-md mt-4 -mb-4 mr-4 -ml-4 lg:mt-6 lg:-mb-6 lg:mr-6 lg:-ml-6 dark:from-slate-800 dark:via-slate-900/0 dark:to-slate-900/0"></div>
				</div>
				<div class="text-center lg:text-left">
					<h1 class="block text-2xl font-medium text-gray-800t dark:text-white">Exclusive offer</h1>
					<p class="mt-3 text-lg text-gray-800 dark:text-gray-400">
						Unlock the ultimate style upgrade with our exclusive offer Enjoy savings of up to 40% off on our
						latest New Arrivals
					</p>

					<div class="flex gap-3 my-8 justify-center lg:justify-start">
						<div class="bg-white p-3 w-20 flex flex-col items-center">
							<div class="text-xl font-medium">
								{{ days }}
							</div>
							<div class="text-sm">Days</div>
						</div>
						<div class="bg-white p-3 w-20 flex flex-col items-center">
							<div class="text-xl font-medium">
								{{ hours }}
							</div>
							<div class="text-sm">Hours</div>
						</div>
						<div class="bg-white p-3 w-20 flex flex-col items-center">
							<div class="text-xl font-medium">
								{{ minutes }}
							</div>
							<div class="text-sm">Min</div>
						</div>
					</div>

					<!-- Buttons -->
					<div class="grid gap-3 w-full sm:inline-flex">
						<a
							class="inline-flex justify-center items-center gap-x-3 text-center bg-emerald-600 hover:bg-emerald-700 border border-transparent text-sm lg:text-base text-white font-medium focus:outline-none focus:ring-2 focus:ring-emerald-600 focus:ring-offset-2 focus:ring-offset-white transition py-3 px-10 dark:focus:ring-offset-gray-800"
							href="#">
							Buy Now
						</a>
					</div>
					<!-- End Buttons -->
				</div>

				<div class="relative ml-4  lg:hidden">
					<img class="w-full rounded-md" src="~/assets/images/offer.png" alt="Image Description" />
					<div
						class="absolute inset-0 -z-[1] bg-gradient-to-tr from-gray-200 via-white/0 to-white/0 w-full h-full rounded-md mt-4 -mb-4 mr-4 -ml-4 lg:mt-6 lg:-mb-6 lg:mr-6 lg:-ml-6 dark:from-slate-800 dark:via-slate-900/0 dark:to-slate-900/0"></div>
				</div>
				<!-- End Col -->

				<!-- End Col -->
			</div>
			<!-- End Grid -->
		</div>
		<!-- End Hero -->
	</div>
	<!-- Team -->
	<div class="max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-14 mx-auto">
		<!-- Title -->
		<div class="max-w-2xl mx-auto text-center mb-10 lg:mb-14 text-emerald-800">
			<h2 class="text-2xl font-bold md:text-4xl md:leading-tight dark:text-white">Designer Clothes For You</h2>
			<p class="mt-1">
				Immerse yourself in the world of luxury fashion with our meticulously crafted designer clothes!
			</p>
		</div>
		<!-- End Title -->

		<!-- Grid -->
		<div class="flex justify-center gap-8 flex-wrap">
			<div>
				<div class="lg:h-[20rem] lg:w-[15rem] bg-emerald-200 relative">
					<img src="@/assets/images/designer-1.png" class="" alt="" srcset="" />
				</div>
				<div class="flex flex-col items-center mt-6 gap-3">
					<div class="font-medium text-xl">Accessories</div>
					<p class="w-40 text-center text-xs">
						Complete your ensemble with designer accessories such as handbags, scarves, belts, and hats.
					</p>
				</div>
			</div>
			<div>
				<div class="lg:h-[20rem] lg:w-[15rem] bg-[#A9D4BA] relative">
					<img src="@/assets/images/designer-2.png" class="" alt="" srcset="" />
				</div>
				<div class="flex flex-col items-center mt-6 gap-3">
					<div class="font-medium text-xl">Dresses</div>
					<p class="w-40 text-center text-xs">
						Explore a stunning range of designer dresses, including evening gowns and chic day dresses.
					</p>
				</div>
			</div>
			<div>
				<div class="lg:h-[20rem] lg:w-[15rem] bg-[#A9D4BA] relative">
					<img src="@/assets/images/designer-3.png" class="" alt="" srcset="" />
				</div>
				<div class="flex flex-col items-center mt-6 gap-3">
					<div class="font-medium text-xl">Outerwear</div>
					<p class="w-40 text-center text-xs">
						Browse luxurious designer coats, jackets, and blazers to stay stylishly warm during colder
						seasons.
					</p>
				</div>
			</div>
		</div>
		<!-- End Grid -->
	</div>

	<div class="max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-14 mx-auto">
		<!-- Title -->
		<div class="max-w-2xl mx-auto text-center mb-10 lg:mb-14 text-emerald-800">
			<h2 class="text-2xl font-bold md:text-4xl md:leading-tight dark:text-white">Feedback corner</h2>
		</div>
		<!-- End Title -->

		<section class="bg-white dark:bg-gray-900">
			<div class="max-w-screen-xl px-4 py-8 mx-auto text-center lg:py-16 lg:px-6">
				<figure class="max-w-screen-md mx-auto">
					<svg
						class="h-12 mx-auto mb-3 text-gray-400 dark:text-gray-600"
						viewBox="0 0 24 27"
						fill="none"
						xmlns="http://www.w3.org/2000/svg">
						<path
							d="M14.017 18L14.017 10.609C14.017 4.905 17.748 1.039 23 0L23.995 2.151C21.563 3.068 20 5.789 20 8H24V18H14.017ZM0 18V10.609C0 4.905 3.748 1.038 9 0L9.996 2.151C7.563 3.068 6 5.789 6 8H9.983L9.983 18L0 18Z"
							fill="currentColor" />
					</svg>
					<blockquote>
						<p class="text-2xl font-medium text-gray-900 dark:text-white">
							"Sampoo is just awesome. It contains tons of predesigned components and pages starting from
							login screen to complex dashboard. Perfect choice for your next SaaS application."
						</p>
					</blockquote>
					<figcaption class="flex items-center justify-center mt-6 space-x-3">
						<img
							class="w-6 h-6 rounded-full"
							src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/michael-gouch.png"
							alt="profile picture" />
						<div class="flex items-center divide-x-2 divide-gray-500 dark:divide-gray-700">
							<div class="pr-3 font-medium text-gray-900 dark:text-white">Micheal Gough</div>
							<div class="pl-3 text-sm font-light text-gray-500 dark:text-gray-400">CEO at Google</div>
						</div>
					</figcaption>
				</figure>
			</div>
		</section>
	</div>

	<footer class="mt-auto w-full max-w-[85rem] py-10 px-4 sm:px-6 lg:px-8 mx-auto bg-emerald-200 ">
		<!-- Grid -->
		<div class="text-center">
			<div>
				<a class="flex-none text-xl font-semibold text-black dark:text-white" href="#" aria-label="Brand"
					>Sampoo</a
				>
			</div>
			<!-- End Col -->

			<div class="mt-3">
		
				<p class="text-gray-500">© Mahdi Bouguerzi. 2023 Sampoo. All rights reserved.</p>
			</div>

			<!-- Social Brands -->
			<div class="mt-3 space-x-2">
				<a
					class="inline-flex justify-center items-center w-10 h-10 text-center text-gray-500 hover:bg-gray-100 rounded-full focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-offset-2 focus:ring-offset-white transition dark:text-gray-500 dark:hover:text-gray-200 dark:hover:bg-gray-800"
					href="#">
					<svg
						class="w-3.5 h-3.5"
						xmlns="http://www.w3.org/2000/svg"
						width="16"
						height="16"
						fill="currentColor"
						viewBox="0 0 16 16">
						<path
							d="M15.545 6.558a9.42 9.42 0 0 1 .139 1.626c0 2.434-.87 4.492-2.384 5.885h.002C11.978 15.292 10.158 16 8 16A8 8 0 1 1 8 0a7.689 7.689 0 0 1 5.352 2.082l-2.284 2.284A4.347 4.347 0 0 0 8 3.166c-2.087 0-3.86 1.408-4.492 3.304a4.792 4.792 0 0 0 0 3.063h.003c.635 1.893 2.405 3.301 4.492 3.301 1.078 0 2.004-.276 2.722-.764h-.003a3.702 3.702 0 0 0 1.599-2.431H8v-3.08h7.545z" />
					</svg>
				</a>
				<a
					class="inline-flex justify-center items-center w-10 h-10 text-center text-gray-500 hover:bg-gray-100 rounded-full focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-offset-2 focus:ring-offset-white transition dark:text-gray-500 dark:hover:text-gray-200 dark:hover:bg-gray-800"
					href="#">
					<svg
						class="w-3.5 h-3.5"
						xmlns="http://www.w3.org/2000/svg"
						width="16"
						height="16"
						fill="currentColor"
						viewBox="0 0 16 16">
						<path
							d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z" />
					</svg>
				</a>
				<a
					class="inline-flex justify-center items-center w-10 h-10 text-center text-gray-500 hover:bg-gray-100 rounded-full focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-offset-2 focus:ring-offset-white transition dark:text-gray-500 dark:hover:text-gray-200 dark:hover:bg-gray-800"
					href="#">
					<svg
						class="w-3.5 h-3.5"
						xmlns="http://www.w3.org/2000/svg"
						width="16"
						height="16"
						fill="currentColor"
						viewBox="0 0 16 16">
						<path
							d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z" />
					</svg>
				</a>
				<a
					class="inline-flex justify-center items-center w-10 h-10 text-center text-gray-500 hover:bg-gray-100 rounded-full focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-offset-2 focus:ring-offset-white transition dark:text-gray-500 dark:hover:text-gray-200 dark:hover:bg-gray-800"
					href="#">
					<svg
						class="w-3.5 h-3.5"
						xmlns="http://www.w3.org/2000/svg"
						width="16"
						height="16"
						fill="currentColor"
						viewBox="0 0 16 16">
						<path
							d="M3.362 10.11c0 .926-.756 1.681-1.681 1.681S0 11.036 0 10.111C0 9.186.756 8.43 1.68 8.43h1.682v1.68zm.846 0c0-.924.756-1.68 1.681-1.68s1.681.756 1.681 1.68v4.21c0 .924-.756 1.68-1.68 1.68a1.685 1.685 0 0 1-1.682-1.68v-4.21zM5.89 3.362c-.926 0-1.682-.756-1.682-1.681S4.964 0 5.89 0s1.68.756 1.68 1.68v1.682H5.89zm0 .846c.924 0 1.68.756 1.68 1.681S6.814 7.57 5.89 7.57H1.68C.757 7.57 0 6.814 0 5.89c0-.926.756-1.682 1.68-1.682h4.21zm6.749 1.682c0-.926.755-1.682 1.68-1.682.925 0 1.681.756 1.681 1.681s-.756 1.681-1.68 1.681h-1.681V5.89zm-.848 0c0 .924-.755 1.68-1.68 1.68A1.685 1.685 0 0 1 8.43 5.89V1.68C8.43.757 9.186 0 10.11 0c.926 0 1.681.756 1.681 1.68v4.21zm-1.681 6.748c.926 0 1.682.756 1.682 1.681S11.036 16 10.11 16s-1.681-.756-1.681-1.68v-1.682h1.68zm0-.847c-.924 0-1.68-.755-1.68-1.68 0-.925.756-1.681 1.68-1.681h4.21c.924 0 1.68.756 1.68 1.68 0 .926-.756 1.681-1.68 1.681h-4.21z" />
					</svg>
				</a>
			</div>
			<!-- End Social Brands -->
		</div>
		<!-- End Grid -->
	</footer>
</template>

<script setup lang="ts">
	import { TabGroup, TabList, Tab, TabPanels, TabPanel } from '@headlessui/vue';

	const countdown = ref('');

	const minutes = ref('');
	const hours = ref('');
	const days = ref('');
	var countDownDate = new Date('jun 1, 2025 00:00:00').getTime();

	onMounted(() => {
		const x = setInterval(function () {
			const now = new Date().getTime();
			const distance = countDownDate - now;
			const _days = Math.floor(distance / (1000 * 60 * 60 * 24));
			const _hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
			const _minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
			const _seconds = Math.floor((distance % (1000 * 60)) / 1000);
			countdown.value = `${_days >= 10 ? _days : '0' + _days}:${_hours >= 10 ? _hours : '0' + _hours}:${
				_minutes >= 10 ? _minutes : '0' + _minutes
			}:${_seconds >= 10 ? _seconds : '0' + _seconds}`;

			minutes.value = `${_minutes >= 10 ? _minutes : '0' + _minutes}`;

			days.value = `${_days >= 10 ? _days : '0' + _days}`;

			hours.value = `${_hours >= 10 ? _hours : '0' + _hours}`;

			if (distance < 0) {
				clearInterval(x);
				countdown.value = 'EXPIRED';
			}
		}, 1000);
	});
</script>

<style scoped></style>
