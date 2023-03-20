<svelte:head>
	<title>home</title>
	<meta name="robots" content="noindex nofollow" />
	<html lang="en" />
</svelte:head>

<main>
	<h1>Spring Season is here!!</h1>
	<div class="gallery">
		<div class="media-group">
			<a href="https://urban-planet.com/">
				<figure class="media-element">
					<h3>White Hoodie</h3>
					<img src="/images/img-1.jpeg" alt="guy with top jeans style" />
					<figcaption>
						<p>Nike Girls' Therma-Fit Hoodie, Kids', Pullover, Kangaroo Pocket</p>
						<button>SHOP NOW</button>
					</figcaption>
				</figure>
			</a>
			<a href="https://urban-planet.com/">
				<figure class="media-element">
					<h3>Long Sleeve</h3>
					<img src="/images/img-2.jpeg" alt="men hoodie style" />
					<figcaption>
						<p>Under Armour Girls' Rival Terry Sweatshirt,light</p>
						<button>SHOP NOW</button>
					</figcaption>
				</figure>
			</a>
			<a href="https://urban-planet.com/">
				<figure class="media-element">
					<h3>Tops</h3>
					<img src="/images/img-3.jpeg" alt="men shorts style" />
					<figcaption>
						<p>Paisley Print Kimono Cardigan, comes in orange</p>
						<button>SHOP NOW</button>
					</figcaption>
				</figure>
			</a>
		</div>

		<div class="media-group">
			<a href="https://urban-planet.com/">
				<figure class="media-element">
					<h3>Top Jacket</h3>
					<img src="/images/img-4.jpeg" alt="guy with top jeans style" />
					<figcaption>
						<p>Columbia Men's Valley Point Winter Ski Jacket, Insulated, Hooded, Waterproof</p>
						<button>SHOP NOW</button>
					</figcaption>
				</figure>
			</a>
			<a href="https://urban-planet.com/">
				<figure class="media-element">
					<h3>Men's Hoodie</h3>
					<img src="/images/img-5.jpeg" alt="men hoodie style" />
					<figcaption>
						<p>Nike Sportswear Men's Club BB Hoodie, Pullover, Drawstring</p>
						<button>SHOP NOW</button>
					</figcaption>
				</figure>
			</a>
			<a href="https://urban-planet.com/">
				<figure class="media-element">
					<h3>Shirts</h3>
					<img src="/images/img-6.jpeg" alt="men shorts style" />
					<figcaption>
						<p>FWD Men's Push Seamless Midlayer Full Zip Training Hoodie</p>
						<button>SHOP NOW</button>
					</figcaption>
				</figure>
			</a>
		</div>

		<div class="media-group">
			<a href="https://urban-planet.com/">
				<figure class="media-element">
					<h3>Light Tops</h3>
					<img src="/images/img-7.jpg" alt="duo style clothing" />
					<figcaption>
						<p>Opens in a new window Gildan Adult Crew Fleece Sweatshirt - Black-white</p>
						<button>SHOP NOW</button>
					</figcaption>
				</figure>
			</a>
			<a href="https://urban-planet.com/">
				<figure class="media-element">
					<h3>Sweat Shirts</h3>
					<img src="/images/img-8.jpg" alt="group clothing style" />
					<figcaption>
						<p>T-shirt Solid Color Shirt Hip-hop Round Neck Top Long-sleeved</p>
						<button>SHOP NOW</button>
					</figcaption>
				</figure>
			</a>
			<a href="https://urban-planet.com/">
				<figure class="media-element">
					<h3>Youth</h3>
					<img src="/images/img-9.jpeg" alt="group selfie style" />
					<figcaption>
						<p>Move Heavy Short Sleeve Tee Shirt Print in Black Size Small</p>
						<button>SHOP NOW</button>
					</figcaption>
				</figure>
			</a>
		</div>
	</div>
</main>

<style>
	main {
		flex: auto;
	}
	.gallery {
		display: grid;
		row-gap: 1rem;
		grid-template-rows: auto;
		margin-bottom: 1rem;
		margin-left: 1rem;
		margin-right: 1rem;
	}

	/* each media group with 3 children */
	.media-group {
		display: grid;
		grid-template-columns: auto auto auto;
		justify-items: center;
	}

	/* media group child */
	.media-element {
		margin: 0;
		padding: 1em;

		border-radius: 15px;
		background-color: #90b8f8;
		width: 25rem;
	}

	/* images within media-element */
	.media-element > img {
		width: 100%;
		aspect-ratio: 16/9;
		object-fit: cover;
	}

	/* hover state for media element */
	.media-element:hover {
		opacity: 0.5;
	}

	/* media element select  */

	/* media element direct select */
	.media-element h3,
	p {
		text-decoration: none;
		color: black;
	}
	/* title for h1 */
	h1 {
		font-size: clamp(2.5rem, 10vw, 3.5rem);
		line-height: 1.2em;
		color: #abecf5;
	}

	/* cta cards */
	h3 {
		color: hsl(170, 30%, 80%);
	}

	button {
		display: flex;
		justify-content: flex-end;

		font-size: clamp(1rem, 1.9vw, 3rem);
		background-color: #90b8f8;
		border: none;
		border-radius: 5px;
	}

	button:hover {
		background-color: #5f85db;
		cursor: pointer;
	}

	/* anchor tag */

	/* responsive on mobile */
	@media only screen and (max-width: 60em) {
		.media-group {
			display: grid;
			grid-template-columns: 1fr;
		}

		.media-element {
			margin-bottom: 1rem;
			width: 17rem;
		}
	}
</style>
