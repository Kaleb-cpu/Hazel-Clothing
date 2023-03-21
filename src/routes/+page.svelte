<svelte:head>
	<title>home</title>
	<meta name="robots" content="noindex nofollow" />
	
</svelte:head>

<main>

  <h1>Shop Now</h1>

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
  display: flex;
  justify-content: flex-end;
  color: white;
  font-family: Trebuchet MS;
  font-weight: bold;
  text-align: center;
  font-size: clamp(1rem, 10vw, 5rem);
  margin-top: 55vh;
  float: right;
  margin-right: 1rem;
  width: max-content;
  border: 7px solid #90b8f8;
  padding: 2.2rem 1rem;
  border-radius: 10px;
}

h1:hover{
  color: #353941;
  cursor: pointer;
}



</style>
