<script>
	import { onMount } from "svelte";
	import VanillaTilt from 'vanilla-tilt';

	onMount(() => {
		VanillaTilt.init(document.querySelectorAll('.woman'), {
			max: 25,
			speed: 400
		});
	})
</script>

<div class="w-screen overflow-x-hidden overflow-y-hidden">
	<div class="max-w-[1224px] mx-auto pt-5 flex flex-col gap-[10em]">
		<h1 class="text-2xl font-bold text-[#130F49]">nufruit</h1>

		<div class="ml-32 flex">
			<div class="flex flex-col items-start gap-8">
				<h1 class="text-[75px] font-bold w-[600px] text-[#130F49]">
					Life
					<br/>
					Changing
					<br/>
					weight loss.
				</h1>

				<p class="text-2xl text-[#130F49]">
					Tracking made 
					<span class="border-b-2 font-medium border-[#FFD32C]">
						easy
					</span>  🍌
				</p>
				<button class="bg-[#130F49] py-5 px-8 rounded-2xl text-white text-[18px]">
					Start Now
				</button>
			</div>

			<div class="relative">
				<svg
					width="890"
					height="992"
					viewBox="0 0 890 992"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
					class="svg"
				>
					<path
						fill-rule="evenodd"
						clip-rule="evenodd"
						d="M576.071 -121.746C715.069 -144.885 845.108 -292.938 972.977 -233.688C1099.89 -174.881 1080.92 13.3567 1140.67 139.87C1198.72 262.778 1321.69 360.256 1317.66 496.125C1313.43 638.287 1227.34 769.607 1119.21 861.938C1015.28 950.692 876.511 981.142 740.1 989.324C613.135 996.939 475.032 987.753 377.18 906.445C285.638 830.38 310.669 684.523 250.016 582.098C181.11 465.735 16.7822 407.902 2.32895 273.434C-12.7579 133.071 60.3612 -21.0598 176.582 -101.11C289.158 -178.65 441.241 -99.3004 576.071 -121.746Z"
						fill="#D9F4FF"
					/>
				</svg>
				<img src="/assets/woman.png" alt="a woman" class="woman absolute" />
			</div>
		</div>
	</div>
</div>
<style>
	.svg{
		transform: translate(calc(100vw - 185%), calc(100vh - 115%));
		scale: .8;
	}
	.woman{
	transform: translate(calc(100vw - 190%), calc(100vh - 200%)); 
	scale: .9;
	}
</style>