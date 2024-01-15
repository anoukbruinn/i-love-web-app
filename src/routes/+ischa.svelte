<script>
</script>

<body>
	<header>
		<ul>
			<li class="logo"><a href="+page.svelte">WE 🖤 WEB</a></li>
			<li><a href="https://stustu.studio/">Tim Borst</a></li>
			<li><a href="src/routes/+ischa.svelte">Isha Gast</a></li>
			<li><a href="+page.svelte">workshop</a></li>
			<li><a href="+page.svelte">workshop</a></li>
		</ul>
	</header>

	<section>
		<h1>Ischa Gast</h1>
	</section>

	<section class="story">
		<p>
			Ischa was een enthousiaste spreker, en zijn presentatie begon met een opvallende vergelijking.
			Hij benadrukte het belang van toegankelijkheid op het web door te wijzen op de alledaagse
			afhankelijkheid van stemherkenning. "Denk bijvoorbeeld aan de metro," zei Ischa, "De metro's
			zijn niet toegankelijk als de stemfuncties niet werken." Hij deelde een opname van een
			metroaankondiging die chaotisch verliep vanwege een storing.
		</p>
		<p>
			"Dit is vergelijkbaar met sommige ontoegankelijke websites," zei hij. Als voorbeeld noemde hij
			de website van Hema, waar een screen reader alleen maar "link link, link link, link link"
			voorlas, vanwege slechte navigatie.
		</p>

		<p>
			Ischa herinnerde ons eraan dat Tim Berners-Lee het web had gecreëerd voor iedereen, inclusief
			blinde, dove en slechtziende mensen. "We hebben allemaal beperkingen," zei hij. "Sommige
			mensen hebben tijdelijke beperkingen, zoals slechtziendheid of een gebroken arm."
		</p>

		<p>
			Tijdens zijn presentatie toonde Ischa interessante slides, vaak met cadeautjes, om het belang
			van toegankelijkheid te benadrukken. Hij benadrukte het belang van "hidden tekst" in links om
			screen readers van meer informatie te voorzien.
		</p>

		<p>
			Contrast werd ook besproken. Ischa legde uit hoe je contrast kon controleren en zei dat
			belangrijke knoppen vaak onvoldoende leesbaar waren vanwege slechte contrastverhoudingen. Hij
			gebruikte de bonuspagina van Albert Heijn als voorbeeld van een website met slecht contrast.
		</p>

		<p>
			Ischa deelde een persoonlijk verhaal over een collega met een visuele beperking, zijn scherm
			was 200 keer vergroot en deze stond in omgekeerd contrast. Deze collega had moeite om de
			toegankelijkheidsopties op de website van Schiphol te vinden, wat een uitdaging was.
		</p>

		<p>
			Een ander punt dat Ischa benadrukte was het belang van het plaatsen van belangrijke informatie
			bovenaan een webpagina, vooral op pagina's waar informatie regelmatig verandert. Hij liet zien
			hoe de website van Schiphol was aangepast om deze wijzigingen door te voeren, zodat reizigers
			niet de hele website hoefden door te scrollen om belangrijke informatie te vinden.
		</p>
	</section>
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
</style>
