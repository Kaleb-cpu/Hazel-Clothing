<script>
	import "./app.css"
</script>

<header>
	<!-- header navigation logo and title -->

	<a href="/" class="logo">
		<svg
			xmlns="http://www.w3.org/2000/svg"
			width="100"
			height="85"
			version="1.0"
			viewBox="0 0 122 129"
			><path
				fill="#90b8f8"
				d="M18.8 19.7c-.7 5 1 44.3 2.7 60.8 2.9 29.9 3.5 31.5 10 31.5 5.7 0 6.2-1.2 9-19.5 3.3-21.6 3.4-21.8 5.3-21 .9.3 6.1 1.7 11.7 3.1 5.6 1.4 10.7 2.9 11.4 3.3 1 .6.9 4-.5 16-.9 8.3-1.4 15.4-1.1 15.8 1.9 1.8 35.4.9 37.4-1.1.9-.8-14.5-88.8-15.7-90-1.2-1.2-9.8-1.2-11.1.1-.5.5-1.7 7-2.5 14.4-.9 7.4-1.8 13.5-1.9 13.7-.4.5-23.8 3.2-24.3 2.8-.6-.7 5.7-22.8 6.9-24.3.6-.6.8-2.1.5-3.1-.6-1.6-2.4-2-14.9-3.1-7.8-.6-16.1-1.4-18.3-1.7-4-.6-4.2-.5-4.6 2.3z"
			/></svg
		>

		<span class="site-title">Hazel Clothing</span>
	</a>

	<input id="toggle" type="checkbox" />

	<label class="hamburger" for="toggle">
		<div class="bar1" />
		<div class="bar2" />
		<div class="bar3" />
	</label>

	<!-- header navigation -->
	<nav>
		<ul class="main-nav">
			<li><a href="./">Home</a></li>
			<li><a href="./gallery">Gallery</a></li>
			<li><a href="./blog">Blog</a></li>
			<li><a href="./contact">Contact</a></li>
		</ul>
	</nav>
</header>

<slot></slot>

<!-- company footer navigation  -->
<footer>
	
	<div class="nav-social">
		<nav>
			<ul class="footer-nav">
				<li><a href="./">Home</a></li>
				<li><a href="./blog">Blog</a></li>
				<li><a href="./gallery">Gallery</a></li>
				<li><a href="./contact">Contact</a></li>
			</ul>
		</nav>
	

	<!-- company social media -->
	<div class="social-media">
		<a href="https://twitter.com/explore"><i class="fa-brands fa-twitter" /></a>
		<a href="https://www.instagram.com/"><i class="fa-brands fa-square-instagram" /></a>
		<a href="https://www.facebook.com/"><i class="fa-brands fa-facebook" /></a>
		<a href="https://www.youtube.com/"><i class="fa-brands fa-youtube" /></a>
	</div>
</div>
	

	<!-- company information -->
	<div class="copy-right">
		<p>TERMS OF USE</p>
		<p>PRIVACY AND POLICY</p>
		<p>&copy; Kaleb Berhane. All rights reserved</p>
	</div>
</footer>

<style>
	@media only screen and (max-width: 60em) {
		.social-media{
			margin: 0.3em;
		}
	}
</style>



