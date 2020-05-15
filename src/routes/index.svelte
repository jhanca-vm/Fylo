<script>
	import Header from '../components/Header.svelte';
	import Hero from '../components/Hero.svelte';
	import Description from '../components/Description.svelte';
	import Promo from '../components/Promo.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<svelte:head>
	<title>Fylo</title>
</svelte:head>
<Header />
<Hero />
<Description />
<Promo />
<Footer />

<style>
	@import url('https://fonts.googleapis.com/css2?family=Open+Sans&family=Raleway:wght@400;700&display=swap');

	:global(body) {
		margin: 0;
		font-family: 'Open Sans', sans-serif;
		color: hsl(243, 87%, 12%);
	}
	
	:global(h1, h2, h3) {
		font-family: 'Raleway', sans-serif;
	}

	:global(.container) {
		max-width: 1440px;
		margin: auto;
		padding: 0 75px;
	}
</style>