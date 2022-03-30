<script lang="ts">
	const clientsList = [
		['Airbnb'],
		['Google', 'BookMyShow'],
		['Microsoft', 'FedEx', 'Walmart'],
		['OYO', 'OLA'],
		['Amazon']
	]
	function scrollToTop() {
		document.body.scrollTop = 0
		document.documentElement.scrollTop = 0
	}
</script>

<!-- Hero section -->
<section class="py-48 mt-16">
	<div class="flex justify-between mx-auto space-x-40 max-w-7xl">
		<div class="flex flex-col w-1/2">
			<h1 class="text-5xl font-bold leading-[84px]">
				Discover <span class="character-gradient">Characters</span> in Pixi-World
			</h1>
			<p class="mt-8 leading-[36px]">
				We believe the world is more beautiful as each person gets better. We believe the world is
				more beautiful as each person gets better. Person gets better.
			</p>
			<button class="mt-12 w-fit px-9 py-[18px]">Get Started For Free</button>
		</div>
		<div class="relative flex items-center justify-center w-1/2">
			<img src="/images/Gradient Ball.png" width={448} height={448} alt="Pixi Logo" />
			<img
				src="/images/objects/Other 15.png"
				class="absolute left-12 -top-10"
				width={185}
				height={185}
				alt="Other 15"
			/>
			<img
				src="/images/characters/Marni 4.png"
				class="absolute -right-8 -top-20"
				width={383}
				height={434}
				alt="Marni 4"
			/>
			<img
				src="/images/characters/Badrun 4.png"
				class="absolute -left-16 -bottom-32"
				width={427}
				height={427}
				alt="Badrun 4"
			/>
			<img
				src="/images/objects/Other 04.png"
				class="absolute -bottom-12 right-20"
				width={164}
				height={164}
				alt="Other 04"
			/>
		</div>
	</div>
</section>

<!-- Our clients section -->
<section class="py-20">
	<div class="flex flex-col items-center">
		<h1 class="text-4xl font-extrabold">Our Clients</h1>
		<p class="mt-2 font-light">We have been working with some Fortune 500 clients</p>
	</div>
	<div class="flex items-center justify-center mt-20 space-x-6">
		{#each clientsList as clients}
			<div class="flex flex-col space-y-6">
				{#each clients as client}
					<div class="client-card">
						<img src={`/images/clients/${client} Logo.svg`} alt={client} />
					</div>
				{/each}
			</div>
		{/each}
	</div>
</section>

<section class="relative py-20">
	<div class="mx-auto max-w-7xl">
		<div class="relative flex justify-between">
			<div
				class="bg-secondary w-[263px] h-[263px] rounded-full flex items-center justify-center absolute -left-[5%]"
			>
				<img src="/images/objects/Other 07.png" width={182} height={182} alt="Other 07" />
			</div>
			<div
				class="absolute w-[51px] h-[51px] rounded-full flex items-center justify-center bottom-0 left-[15%] bg-secondary"
			>
				<img src="/images/objects/Ball.png" width={33} height={33} alt="Ball" />
			</div>
			<div />
			<div class="flex flex-col items-center w-3/4 space-y-7 z-[2]">
				<div class="relative">
					<div
						class="absolute w-[43px] h-[43px] bg-secondary rounded-full left-[35%] top-[65%] z-[1]"
					/>
					<img
						src="/images/objects/Other 02.png"
						width={124}
						height={124}
						alt="Other 02"
						class="relative z-10"
					/>
				</div>
				<h1 class="text-4xl font-bold leading-[84px] text-right">
					You are one step away from discovering your next <span class="character-gradient"
						>Character</span
					> in Pixi-World
				</h1>
			</div>
		</div>
	</div>
	<div class="rectangle" />
</section>

<section class="py-52">
	<div class="flex justify-between mx-auto space-x-24 max-w-7xl">
		<div class="relative w-1/2">
			<img src="/images/Gradient Ball.png" width={448} height={448} alt="Gradient Ball" />
			<img
				src="/images/objects/Other 19.png"
				width={177}
				height={177}
				alt="Other 19"
				class="absolute -top-20 -left-12"
			/>
			<img
				src="/images/objects/Other 10.png"
				width={120}
				height={120}
				alt="Other 10"
				class="absolute -top-20 right-40"
			/>
			<img
				src="/images/characters/Ikbal 5.png"
				width={413}
				height={413}
				alt="Ikbal 5"
				class="absolute -left-4 top-32"
			/>
			<img
				src="/images/objects/Other 18.png"
				width={232}
				height={232}
				alt="Other 18"
				class="absolute top-32 right-16"
			/>
		</div>
		<div class="flex flex-col space-y-10 w-1/2 z-[2]">
			<h1 class="text-4xl font-bold leading-[84px]">Discover Characters in Pixi-World</h1>
			<p class="leading-9">
				We believe the world is more beautiful as each person gets better. We believe the world is
				more beautiful as each person gets better. Person gets better.
			</p>
			<button class="w-fit py-[18px] px-9">Try It Now</button>
		</div>
	</div>
</section>

<section class="py-40">
	<div class="flex justify-between mx-auto space-x-24 max-w-7xl">
		<div class="flex flex-col space-y-10 w-1/2 z-[2]">
			<h1 class="text-4xl font-bold leading-[84px]">Discover Characters in Pixi-World</h1>
			<p class="leading-9">
				We believe the world is more beautiful as each person gets better. We believe the world is
				more beautiful as each person gets better. Person gets better.
			</p>
			<button class="w-fit py-[18px] px-9">Try It Now</button>
		</div>
		<div class="relative flex justify-end w-1/2">
			<img src="/images/Gradient Ball.png" width={448} height={448} alt="Gradient Ball" />
			<img
				src="/images/objects/Other 20.png"
				width={169}
				height={169}
				alt="Other 20"
				class="absolute left-32 -top-10"
			/>
			<img
				src="/images/objects/Other 19.png"
				width={158}
				height={158}
				alt="Other 19"
				class="absolute bottom-0 left-20"
			/>
			<img
				src="/images/characters/Marni 3.png"
				width={537}
				height={537}
				alt="Marni 3"
				class="absolute -bottom-1/3 left-28"
			/>
			<img
				src="/images/objects/Other 05.png"
				width={179}
				height={179}
				alt="Other 05"
				class="absolute -right-20 top-[30%]"
			/>
		</div>
	</div>
</section>

<div class="flex justify-end w-full px-10 py-12 mx-auto max-w-7xl">
	<div class="flex flex-col items-center justify-center space-y-2">
		<button class="back-to-top-button" on:click={scrollToTop}>
			<img src="/images/arrow.svg" alt="Arrow icon" width={16} height={16} />
		</button>
		<p class="text-center">Back to top</p>
	</div>
</div>

<style lang="postcss">
	.character-gradient {
		background: linear-gradient(
			245.29deg,
			#6dc1dc 13.32%,
			#a690fc 28.55%,
			#fc96bb 55.55%,
			#ffc397 84.12%
		);
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		background-clip: text;
		text-fill-color: transparent;
	}
	.client-card {
		@apply bg-white px-[38px] py-8 flex justify-center items-center;
		@apply transition hover:-translate-y-2 cursor-pointer duration-300;
		background: #ebe6fa;
		box-shadow: 0px 30px 40px rgba(212, 217, 232, 0.2);
		border-radius: 16px;
	}
	.rectangle {
		position: absolute;
		width: 262.68px;
		height: 2762.24px;
		top: -15%;
		right: 40%;
		background: #291c52;
		border-radius: 140px;
		transform: rotate(38.51deg);
		z-index: 1;
	}
	.back-to-top-button {
		@apply flex items-center justify-center;
		width: 56px;
		height: 56px;
		background: #ebe6fa;
		box-shadow: 0px 30px 40px rgba(212, 217, 232, 0.2);
		border-radius: 88px;
	}
</style>
