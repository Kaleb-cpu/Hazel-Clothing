<svelte:head>
	<title>blog</title>
	<meta name="robots" content="noindex nofollow" />
	<html lang="en" />
</svelte:head>

<main>
	<section>
		<h1>BLOG</h1>
		<div class="rows">
			<div class="title">
				<h2>5 Reasons to love Belkin</h2>
			</div>
			<div class="content">
				<a
					href="https://www.michaelkors.ca/handbags/view-all-handbags/_/N-282y?ecid=MKS_TEXT_P_GG_NBPR_CA_EN_HANDBAGS_X_PHRASE_11230790571_109672114229&gclid=CjwKCAiAioifBhAXEiwApzCztnrLse88Prs8qlC7oyIdEhqz0TMP3DMl2-hSC756JV8SZFBKdksg1hoCaEoQAvD_BwE&gclsrc=aw.ds"
				>
					<div class="card">
						<img src="./images/blog-img-1.jpeg" alt="brown hand bag" width="507" height="595" />
						<h4>Brown hand bag</h4>
						<p>
							Excellent craftsmanship and long-lasting materials are key to ensure you can wear it
							for years to come Renowned for exemplary techniques and Italian artisanship, VONI is a
							high-in-demand bag brand.
						</p>
					</div>
				</a>
				<a
					href="https://www.michaelkors.ca/handbags/view-all-handbags/_/N-282y?ecid=MKS_TEXT_P_GG_NBPR_CA_EN_HANDBAGS_X_PHRASE_11230790571_109672114229&gclid=CjwKCAiAioifBhAXEiwApzCztnrLse88Prs8qlC7oyIdEhqz0TMP3DMl2-hSC756JV8SZFBKdksg1hoCaEoQAvD_BwE&gclsrc=aw.ds"
				>
					<div class="card">
						<img src="./images/blog-img-2.jpeg" alt="blue hand bag" width="504" height="656" />
						<h4>Blue</h4>
						<p>
							VONI is a high-in-demand bag brand. Made out of intrecciato, the famous leather weave
							that dates back to the 1960s.VONI is a great choice for anyone who adores subtle
							design and extra-fine craftsmanship rather than flashy logos.
						</p>
					</div>
				</a>
				<a
					href="https://www.michaelkors.ca/handbags/view-all-handbags/_/N-282y?ecid=MKS_TEXT_P_GG_NBPR_CA_EN_HANDBAGS_X_PHRASE_11230790571_109672114229&gclid=CjwKCAiAioifBhAXEiwApzCztnrLse88Prs8qlC7oyIdEhqz0TMP3DMl2-hSC756JV8SZFBKdksg1hoCaEoQAvD_BwE&gclsrc=aw.ds"
				>
					<div class="card">
						<img src="./images/blog-img-3.jpg" alt="black hand bag" width="513" height="686" />
						<h4>Black hand bag</h4>
						<p>
							The black one is good on the winter, it's very versatile and has the most unique
							design. You can also wear the black one if you like, on a very rainy spring. These
							bags are awesome. The blue one also has a unique style to it.
						</p>
					</div>
				</a>
				<div class="card">
					<video
						src="./videos/birklin.mp4"
						autoplay
						muted
						controls
						title="expensive birkin bags"
						width="500"
						height="300"
					/>
					<h4>Berkin Bags</h4>
					<p>
						Berkin Bags are One of the most luxirious bags. Birkin bags are handmade from leather
						and are named after the English-French actress and singer Jane Birkin.
					</p>
				</div>
			</div>
		</div>
	</section>
</main>

<style>
	main {
		flex: auto;
	}
	/* page title */
	h1 {
		color: #abecf5;
		font-size: clamp(1rem, 10vw, 4rem);
		text-align: center;
	}

	h2 {
		color: #90b8f8;
	}
	/* parent */
	section {
		width: 100%;
	}

	/* rows */
	section .rows {
		max-width: auto;
		/* margin: auto; */
	}

	/* title in the rows */
	.title {
		margin: auto;
		text-align: center;
	}
	.card img {
		width: 100%;
		height: initial;
		object-fit: cover;
		border-radius: 10px;
	}

	/* card parent */
	.content {
		display: grid;
		grid-auto-flow: column;
		grid-auto-columns: 2fr 2fr 2fr 4fr;
	}

	/* card holder */
	.card {
		margin: 2rem 1rem;
	}

	/* border box only on images */
	.card:nth-child(-n + 3) {
		border: solid 5px #26282b;
		border-radius: 10px;
	}
	/* inside card title 2 */
	.title h2 {
		font-size: clamp(1.5rem, 2.5vw, 4rem);
		font-family: 'Lato', Tahoma, Geneva, Verdana, sans-serif;
	}

	/* inside card title */
	.content h4 {
		padding: 1rem;
		font-size: clamp(1rem, 2.5vw, 1.5rem);
		color: #90b8f8;
	}

	/* inside card paragraph */
	.content p {
		font-size: clamp(1rem, 2vw, 1.2rem);
		color: #d6d0b8;
		line-height: 1.5;
		padding: 1em;
	}

	/* first three children of card element */
	.card:nth-child(-n + 3):hover {
		opacity: 0.5;
		cursor: pointer;
	}

	/* hover on image cards only */
	.card video {
		width: 100%;
		border: none;
	}

	@media only screen and (max-width: 60em) {
		.content {
			display: flex;
			flex-direction: column;
		}
	}
</style>
