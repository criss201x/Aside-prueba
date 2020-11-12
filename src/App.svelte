<script>
//	export let name;
  import Navbar from './Navbar.svelte'
  import Sidebar from './Sidebar.svelte'
  import Main from './Main.svelte'
  let open = false
</script>


<Navbar bind:sidebar={open}/>
<Sidebar bind:open/>
<Main/>




<svelte:head>
	<link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet"/>
</svelte:head>



<style> 
  :global(body) {
    padding: 0;
  }
</style>