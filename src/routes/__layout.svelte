<script lang="ts">
	import '../app.css'
	import '@fontsource/inter/300.css'
	import '@fontsource/inter/400.css'
	import '@fontsource/inter/600.css'
	import '@fontsource/inter/700.css'
	import '@fontsource/inter/800.css'
	import Navbar from '$lib/components/Navbar.svelte'
	import Footer from '$lib/components/Footer.svelte'
</script>

<div class="overflow-x-hidden text-white bg-dark">
	<Navbar />
	<slot />
	<Footer />
</div>

<style lang="postcss" global>
	button {
		@apply px-[18px] py-[10px] rounded-[100px] font-bold;
		@apply text-primary bg-white;
	}
	button.primary {
		@apply text-white bg-primary;
	}
</style>
