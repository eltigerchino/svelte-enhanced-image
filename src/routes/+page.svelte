
<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			<enhanced:img src="$lib/images/svelte-welcome.png" alt="Welcome" />
		</span>

		to your new<br />SvelteKit app
	</h1>
</section>

<style>
	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
