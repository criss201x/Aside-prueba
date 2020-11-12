<script>
	export let open = false
</script>

<aside class="absolute h-full bg-gray-200 border-r-2 shadow-lg" class:open>
<!--<aside class="absolute w-full h-full bg-gray-200 border-r-2 shadow-lg" class:open> -->

	<nav class="p-12 text-xl">
		<a class="block" href="#about">menu item 1 </a>
		<a class="block" href="#about">menu item 2 </a>
		<a class="block" href="#about">menu item 3 </a>
		<a class="block" href="#contact">menu item 4 </a>
	</nav>
</aside>

<style>
	aside {
		
		left: -100%;
		transition: left 0.3s ease-in-out
	}
	
	.open {
		left: 0
	}
</style>