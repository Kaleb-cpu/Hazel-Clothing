<svelte:head>
	<title>home</title>
	<meta name="robots" content="noindex nofollow" />
	
</svelte:head>

<main>

  <h1>Shop now</h1>

	<video id="background-video" autoplay loop controls muted poster>
  <source src="./videos/How to Break into the Fashion Industry with Alexa Chung S1, E1 Future of Fashion British Vogue.mp4" type="video/mp4">
</video>

</main>
<style>
  main{
    flex: auto;
  }

  #background-video {
  width: 100vw;
  height: 100vh;
  object-fit: cover;
  position: fixed;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  z-index: -1;
}

h1 {
  color: white;
  font-family: Trebuchet MS;
  font-weight: bold;
  text-align: center;
  font-size: clamp(1rem, 10vw, 5rem); ;
  margin-top: 30vh;
  margin-left: 90vh;
}



</style>
