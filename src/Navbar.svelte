<script>
	import Logo from './Logo.svelte' // estilos y elemetos header parte izquierda 
	import Hamburger from './Hamburger.svelte'// boton de expandir el menu
	import Menu from './Menu.svelte' // parte derecha del natbar
	
	export let sidebar = false
</script>

<header class="flex justify-between bg-blue-200 p-2 items-center text-gray-600 border-b-2">
	<nav class="flex">
		<Hamburger bind:open={sidebar}/>
		<Logo/>	
	</nav>
	
	<Menu/>
</header>
