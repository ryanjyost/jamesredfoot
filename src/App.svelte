<script>
	export let name;

	const peeps = [
		{name: 'Corey Sharp', image: 'corey.png', title: 'Producer/Writer'},
		{name: 'Ryan Yost', image: 'yost.jpeg', title: 'Producer/Writer'},
		{name: 'Ellie Free', image: 'ellie.jpeg', title: 'Creative Director'},
		{name: 'Daniel Allweiss', image: 'allweiss.jpeg', title: 'Line Producer/Manager'}
	]
</script>

<main>
	<h1 class="red">James Redfoot</h1>
<!--	<h1 class="red">Redfoot</h1>-->
	<h1>Productions</h1>

	<br/>
	<hr/>

	<br/>
	<p>Watch <i>Everybody's Got Their Demons</i> at <a href="https://vimeo.com/736879709/6a1df58d2d">thedemonshow.com</a></p>
	<p>
		Email us at <a style="color: #fff;" href="mailto:jamesredfootproductions@gmail.com">JamesRedfootProductions@gmail.com</a>
	</p>

	<p>Read our scripts at <a href="https://yostandsharp.com">yostandsharp.com</a></p>




	<br/>
	<br/>
	<br/>

<!--	<hr/>-->
	<br/>
<!--	<h2>What we're working on.</h2>-->

<!--	<h4><strong><i>Everybody's got their Demons</i></strong></h4>-->
<!--	<p>-->
<!--		<i>-->
<!--			An animated comedy series about a degenerate who grapples with her religious faith and opts to pursue nunhood to escape the torment of diabolically creative demons who will stop at nothing to make her and everyone else succumb to the dark side of life.-->
<!--		</i>-->
<!--		<i><u><a href="https://yostandsharp.com/scripts/demons">Click to read the script.</a></u></i>-->
<!--	</p>-->

<!--	<br/>-->
<!--	<p>Read our other scripts at <a href="https://yostandsharp.com">yostandsharp.com</a></p>-->
<!--	<br/>-->
<!--	<hr/>-->

<!--	<br/>-->
<!--	<br/>-->
<!--	<br/>-->
<!--	<br/>-->

<!--	<h2>Our team, so far...</h2>-->
<!--	<div id="peepsContainer">-->
<!--		{#each peeps as peep}-->
<!--		<div class="peep">-->
<!--			<img src="{`/images/${peep.image}`}" width="100%" height="auto"/>-->
<!--			<h4><strong>{peep.name}</strong>, {peep.title}</h4>-->
<!--			<br/>-->
<!--			<br/>-->
<!--		</div>-->
<!--		{/each}-->
<!--	</div>-->
</main>

<style>

	#peepsContainer {
		/*display:flex;*/
		/*!*flex-direction: column;*!*/
		/*align-items: center;*/
	}

	.peep {
		/*margin: 20px;*/
	}

	hr {
		background-color: rgba(255, 255, 255, 0);
		border-color: rgba(255, 255, 255, 0.3);
		box-shadow: none;
		outline: none;
		border-style: solid;
		width: 100%;
	}

	img {
		max-width: 200px;
		border-radius: 5px;
	}

	main {
		/*padding: 1em;*/
		/*padding-top: 100px;*/
		width: 100%;
		max-width: 600px !important;
		margin: 0 auto;
		height: 100vh;
		display: flex;
		justify-content: center;
		align-content: center;
		flex-direction: column;
		text-align: center;
	}

	h1 {
		color: rgba(255, 255, 255, 0.5);
		text-transform: uppercase;
		font-size: 2.5em;
		margin-bottom: 10px;
		margin-top: 10px;
		letter-spacing: 0.03em;
		font-weight: 700;
		line-height: 1em;
	}

	h2 {
		color: rgba(255, 255, 255, 1);
		margin-bottom: 40px;
	}

	h3, h4 {
		color: #fff;
		font-weight: normal;
	}

	a {
		color: #fff;
		text-decoration: underline;
	}

	p {
		color: #fff;
	}

	.red {
		color: #ff3e00;
		opacity: 0.9;
		font-weight: 700;
		color: rgba(255, 255, 255, 1);
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
