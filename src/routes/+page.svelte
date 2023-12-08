<script>
	import Image from '../lib/assets/apple.png';
</script>

<body>
	<header>
		<section class="left">
			<ul>
				<img class="logo" src={Image} alt="" />
				<li class="finder">Finder</li>
				<li>Archief</li>
				<li>Wijzig</li>
				<li>Weergave</li>
				<li>Ga</li>
				<li>Venster</li>
				<li>Hulp</li>
			</ul>
		</section>

		<section class="right">
			<ul>
				<li>a</li>
				<li>b</li>
				<li>c</li>
				<li>d</li>
				<li>e</li>
				<li>f</li>
				<li>g</li>
			</ul>
		</section>
	</header>

	<main>
		<section class="Map">
			<img class="Map-blue" src="src/lib/assets/desktop.webp" alt="" />
		</section>
	</main>

	<footer>
		<section class="dock">
			<div class="box">
				<img class="item" src="src/lib/assets/Chrome-logo.png" alt="chrome" />
			</div>

			<div class="box">
				<img class="item" src="src/lib/assets/github-logo.png" alt="github" />
			</div>

			<div class="box">
				<div class="item"></div>
			</div>

			<div class="box">
				<div class="item"></div>
			</div>

			<div class="box">
				<div class="item"></div>
			</div>

			<div class="box">
				<div class="item"></div>
			</div>
		</section>
	</footer>
</body>

<style>
	* {
		box-sizing: border-box;
		margin: 0%;
	}
	

	body {
		background-color: rgb(224, 224, 114);
		position: relative;
		height: 100vh;
	}

	/* HEADER  */

	header {
		background-color: purple;
		display: flex;
		margin: 0%;
	}

	.logo {
		padding-right: 25px;
	}

	ul {
		list-style: none;
		display: flex;
	}

	li {
		color: white;
		padding-right: 25px;
	}

	.finder {
		font-weight: bold;
	}

	section.right {
		display: flex;
		float: right;
	}

	/* DOCK */

	footer {
		display: flex;
		justify-content: center;
		margin-bottom: 0px;
		margin-top: auto;
		position: absolute;
		bottom: 0;
		width: 100%;
		margin-bottom: 2rem;
	}

	.dock {
		padding: 15px;
		width: max-content;
		border: 0.5 px lightgray;
		display: flex;
		gap: 20px;
		background-color: rgb(152, 151, 151);
		border-radius: 40px;
	}

	.box {
		size: 100px;
		width: 100px;
		height: 100px;
		transition: transform 200ms;
		padding: 10px;
	}

	.item {
		width: 100%;
		height: 100%;
	}

	.box:nth-child(1) .item {
		border-radius: 10px;
	}

	.box:nth-child(2) .item {
		border-radius: 10px;
	}

	.box:nth-child(3) .item {
		background-color: black;
		border-radius: 10px;
	}

	.box:nth-child(4) .item {
		background-color: black;
		border-radius: 10px;
	}

	.box:nth-child(5) .item {
		background-color: black;
		border-radius: 10px;
	}

	.box:nth-child(6) .item {
		background-color: black;
		border-radius: 10px;
	}

	.box:hover {
		transform: scale(1.6) translateY(-35px);
	}

	.box:hover + .box,
	.box:has(+ .box:hover) {
		transform: scale(1.2) translateY (-15px);
	}

	/* ----MAP----- */

	img.Map-blue {
		width: 100px;
		display: flex;
		float: right;
		margin-right: 30px;
		margin-top: 30px;
	}
</style>
