

<script>
	
	
	import Header from "../components/HeaderLogin.svelte";
	import Inicio from "../components/Inicio.svelte";
	
	import Tailwindcss from '../Tailwindcss.svelte';
	
	let imagen = 'https://www.tailwindtoolbox.com/templates/hero.png';

</script>


<style>
	:global(body){
		background-color: #f2eee2;
		color: #0084f6;
	}
	:global(body.dark-mode){
		background-color: #1d3040;
		color: #f2eee2;
	}
</style>

<main>
<Tailwindcss />
<Header />
<Inicio />
</main>
