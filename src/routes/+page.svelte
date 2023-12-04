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
				<li>Help</li>
			</ul>
		</section>

		<section class="right"></section>
	</header>

	<footer>
		<section class="dock">
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
	}

	body {
		background-color: hotpink;
	}

	/* HEADER  */

	header {
		background-color: purple;
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

	/* DOCK */

	.dock {
		padding: 20px;
		width: max-content;
		border: 0.5 px lightgray;
		display: flex;
		gap: 30px;
	}

	.box {
		size: 100px;
		width: 80px;
		height: 80px;
		transition: transform 200ms;
		padding: 10px;
	}

	.item {
		width: 100%;
		height: 100%;
	}

	.box:nth-child(1) .item {
		background-color: black;
	}

	.box:nth-child(2) .item {
		background-color: rgb(0, 0, 0);
	}

	.box:nth-child(3) .item {
		background-color: black;
	}

	.box:nth-child(4) .item {
		background-color: black;
	}

	.box:nth-child(5) .item {
		background-color: black;
	}

	.box:hover {
		transform: scale(1.6) translateY(-35px);
	}

	.box:hover + .box,
	.box:has(+ .box:hover) {
		transform: scale(1.2) translateY (-15px);
	}
</style>
