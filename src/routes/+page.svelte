<body>
	<section>
		<link href="https://fonts.googleapis.com/css?family=Russo+One" rel="stylesheet" />

		<svg viewBox="0 0 1320 300">
			<text x="50%" y="50%" dy=".35em" text-anchor="middle"> WEloveWEB </text>
		</svg>
	</section>

	<!-- -------------------BACKGROUND-ANIMATION-------------------------- -->
	<div class="area">
		<ul class="squares">
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
		</ul>
	</div>

	<!-- ----------BLOGPOST------------- -->

	
</body>

<style>
	* {
		margin: 0;
		padding: 0;
	}
	body {
		background: rgb(204, 169, 199);
	}

	svg {
		font-family: 'Russo One', sans-serif;
		width: 100%;
		height: 100%;
		display: flex;
		align-items: center;
	}
	svg text {
		text-transform: uppercase;
		animation: stroke 5s infinite alternate;
		stroke-width: 2;
		stroke: #a03666;
		font-size: 140px;
	}
	@keyframes stroke {
		0% {
			fill: rgba(138, 20, 77, 0);
			stroke: rgb(160, 54, 132);
			stroke-dashoffset: 25%;
			stroke-dasharray: 0 50%;
			stroke-width: 2;
		}
		70% {
			fill: rgba(95, 20, 138, 0);
			stroke: rgb(160, 54, 54);
		}
		80% {
			fill: rgba(20, 73, 138, 0);
			stroke: rgb(153, 54, 160);
			stroke-width: 3;
		}
		100% {
			fill: rgb(204, 72, 118);
			stroke: rgba(54, 137, 160, 0);
			stroke-dashoffset: -25%;
			stroke-dasharray: 50% 0;
			stroke-width: 0;
		}
	}
	/* ---------------------------------------------- */

	section {
		display: flex;
		justify-content: center;
		margin: 250px auto;
		width: 600px;
		flex-direction: column;
		text-align: center;
		color: #fff;
	}

	.squares {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		overflow: hidden;
	}

	.squares li {
		position: absolute;
		display: block;
		list-style: none;
		width: 20px;
		height: 20px;
		background: rgba(255, 255, 255, 0.2);
		animation: animate 8s linear infinite;
		bottom: -150px;
	}

	.squares li:nth-child(1) {
		left: 25%;
		width: 80px;
		height: 80px;
		animation-delay: 0s;
	}

	.squares li:nth-child(2) {
		left: 10%;
		width: 70px;
		height: 70px;
		animation-delay: 0s;
		animation-duration: 12s;
	}

	.squares li:nth-child(3) {
		left: 70%;
		width: 30px;
		height: 30px;
		animation-delay: 2s;
	}

	.squares li:nth-child(4) {
		left: 40%;
		width: 60px;
		height: 60px;
		animation-delay: 0s;
		animation-duration: 18s;
	}

	.squares li:nth-child(5) {
		left: 65%;
		width: 50px;
		height: 50px;
		animation-delay: 0s;
	}

	.squares li:nth-child(6) {
		left: 75%;
		width: 110px;
		height: 110px;
		animation-delay: 0s;
	}

	.squares li:nth-child(7) {
		left: 35%;
		width: 150px;
		height: 150px;
		animation-delay: 4s;
	}

	.squares li:nth-child(8) {
		left: 50%;
		width: 40px;
		height: 40px;
		animation-delay: 2s;
		animation-duration: 30s;
	}

	.squares li:nth-child(9) {
		left: 20%;
		width: 30px;
		height: 30px;
		animation-delay: 2s;
		animation-duration: 25s;
	}

	.squares li:nth-child(10) {
		left: 85%;
		width: 150px;
		height: 150px;
		animation-delay: 0s;
		animation-duration: 11s;
	}

	.squares li:nth-child(11) {
		left: 35%;
		width: 150px;
		height: 150px;
		animation-delay: 0s;
	}

	.squares li:nth-child(12) {
		left: 50%;
		width: 70px;
		height: 70px;
		animation-delay: 2s;
		animation-duration: 7s;
	}

	.squares li:nth-child(13) {
		left: 20%;
		width: 70px;
		height: 70px;
		animation-delay: 0s;
		animation-duration: 15s;
	}

	.squares li:nth-child(14) {
		left: 85%;
		width: 150px;
		height: 150px;
		animation-delay: 0s;
		animation-duration: 11s;
	}

	@keyframes animate {
		0% {
			transform: translateY(0px) rotate(0deg);
			opacity: 1;
			border-radius: 0;
		}

		100% {
			transform: translateY(-1000px) rotate(720deg);
			opacity: 0;
			border-radius: 50%;
		}
	}
</style>
