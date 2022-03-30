<script lang="ts">
	const menus = ['Home', 'About', 'Features']
</script>

<nav class="fixed top-0 z-50 w-full py-6 backdrop-blur-md">
	<div class="flex justify-between mx-auto max-w-7xl">
		<img src="/images/logo.svg" width={171} height={32} alt="Pixi Logo" />
		<div class="flex items-center space-x-12">
			{#each menus as menu}
				<a href="/" class="nav-link">{menu}</a>
			{/each}
		</div>
		<div class="flex space-x-3">
			<button>Sign In</button>
			<button class="primary">Create Account</button>
		</div>
	</div>
</nav>

<style lang="postcss">
	.nav-link {
		@apply relative font-bold transition hover:text-info;
	}
	.nav-link:hover::after {
		content: '';
		position: absolute;
		bottom: -8px;
		left: 50%;
		border-radius: 10000px;
		width: 6px;
		height: 6px;
		background: linear-gradient(38.75deg, #6bd4ff 14.73%, #8c70ff 85.28%);
	}
</style>
