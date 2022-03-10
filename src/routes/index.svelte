<div class="w-full bg-gray-900 overflow-clip relative h-screen">
	<div class="z-0 relative top-0">
		<div class="bg-blue-200/50 w-full h-8 blur-lg rotate-45 absolute right-0 md:-right-96 pulse" />
		<div class="bg-blue-400 w-full h-6 blur rotate-45 absolute right-0 md:-right-96 pulse" />
		<div class="bg-blue-300 w-full h-3 rotate-45 absolute right-0 md:-right-96" />

		<div class="bg-green-200/50 w-full h-8 blur-lg -rotate-45 absolute left-0 md:-left-96 pulse" />
		<div class="bg-green-800 w-full h-6 blur-lg -rotate-45 absolute left-0 md:-left-96 pulse2" />
		<div class="bg-green-300 w-full h-3 -rotate-45 absolute left-0 md:-left-96" />
	</div>
	<div class="max-w-7xl p-4 md:p-32 m-auto z-10 relative">
		<div class="relative">
			<h1 class="text-4xl font-extrabold text-slate-50 tracking-tight sm:text-9xl text-center">
				Cofocus Labs
			</h1>
			<p class="mt-6 text-xl sm:text-2xl text-slate-50 text-center sm:px-40">
				We make web apps to solve problems.
			</p>
		</div>
	</div>
</div>

<style>
	.pulse {
		animation: pulse 22s cubic-bezier(0.4, 0, 0.6, 1) infinite;
	}

	@keyframes pulse {
		0%,
		100% {
			opacity: 1;
		}
		50% {
			opacity: 0.5;
		}
	}
	.pulse2 {
		animation: pulse 17s cubic-bezier(0.4, 0, 0.6, 1) infinite;
	}

	@keyframes pulse2 {
		0%,
		100% {
			opacity: 1;
		}
		50% {
			opacity: 0.2;
		}
	}
</style>
