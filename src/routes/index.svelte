<script>
	import successkid from 'images/successkid.jpg';
	import {Card, Image} from 'smelte';
</script>

<style>
	h1,  p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<h1>Great success!</h1>

<Card.Card elevation={2}>
	<Image alt="Success Kid" src="{successkid}" width="100%"/>
	<h6>Have fun with Sapper!</h6>
</Card.Card>

<p><strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong></p>
