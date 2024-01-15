<script>
</script>

<body>
	<header>
		<ul>
			<li class="logo"><a href="+page.svelte">WE 🖤 WEB</a></li>
			<li><a href="https://stustu.studio/">Tim Borst</a></li>
			<li><a href="+ischa.svelte">Ischa Gast</a></li>
			<li><a href="+page.svelte">workshop</a></li>
			<li><a href="+page.svelte">workshop</a></li>
		</ul>
	</header>

	<main>
		<section class="intro">
			<h1>Code Different</h1>
		</section>

		<section class="workshop-1">
			<h1 class="workshop-1-letter">
				<a class=" workshop-1-letter" href="https://stustu.studio/">T.B</a>
			</h1>
		</section>

		<section class="workshop-2">
			<h1 class="workshop-2-letter">
				<a class=" workshop-1-letter" href="https://stustu.studio/">Ischa Gast</a>
			</h1>
		</section>

		<section class="workshop-3"></section>
	</main>

	<footer></footer>
</body>

<style>
	* {
		box-sizing: border-box;
		margin: 0%;
	}

	body {
		background-color: rgb(231, 231, 230);
	}

	/* ------------------header-------------------- */

	header {
		position: sticky;
	}

	ul {
		list-style-type: none;
		margin: 0;
		padding-top: 2em;
		padding-left: 8em;
		padding-right: 8em;
		position: sticky;
	}

	li {
		display: inline;
		float: right;
		padding: 12px;
		font-family: Courier 'Courier New';
	}

	a {
		font-family: 'Courier New', Courier, monospace;
		display: inline;
		color: black;
		font-style: normal;
		font-weight: bold;
		text-decoration: none;
	}

	.logo {
		float: left;
	}

	/* ---------------intro---------------- */

	.intro {
		display: flex;
		justify-content: center;
		width: 100%;
		height: 300px;
		margin-top: 20%;
		margin-bottom: 300px;
	}

	h1 {
		font-size: 12em;
	}

	/* -------------workshops------------------ */

	.workshop-1 {
		background: black;
		width: 1100px;
		height: 400px;
		color: white;
		font-size: 0.5em;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.workshop-1-letter {
		color: white;
		font-size: 5em;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.workshop-2 {
		background: rgb(103, 2, 2);
		width: 565px;
		height: 400px;
		color: white;
		font-size: 0.5em;
		display: flex;
		justify-content: center;
		align-items: center;
		float: right;
	}

	.workshop-2-letter {
		color: white;
		font-size: 2em;
		display: flex;
		justify-content: center;
		align-items: center;
	}
</style>
