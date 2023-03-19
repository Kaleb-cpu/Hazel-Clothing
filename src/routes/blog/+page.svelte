  <main>
    <h1>BLOG</h1>
    <section>
      <div class="rows">
        <div class="title">
          <h2>5 Reasons to love Belkin</h2>
        </div>
        <div class="content">
          <a href="https://www.michaelkors.ca/handbags/view-all-handbags/_/N-282y?ecid=MKS_TEXT_P_GG_NBPR_CA_EN_HANDBAGS_X_PHRASE_11230790571_109672114229&gclid=CjwKCAiAioifBhAXEiwApzCztnrLse88Prs8qlC7oyIdEhqz0TMP3DMl2-hSC756JV8SZFBKdksg1hoCaEoQAvD_BwE&gclsrc=aw.ds">
            <div class="card">
              <img src="./images/blog-img-1.jpeg" alt="brown hand bag"  width="507" height="595">
              <h4>Brown hand bag</h4> 
              <p>Excellent craftsmanship and long-lasting materials are key to ensure you can wear it for years to come Renowned for exemplary techniques and Italian artisanship, VONI is a high-in-demand bag brand.</p>
            </div>
          </a>
          <a href="https://www.michaelkors.ca/handbags/view-all-handbags/_/N-282y?ecid=MKS_TEXT_P_GG_NBPR_CA_EN_HANDBAGS_X_PHRASE_11230790571_109672114229&gclid=CjwKCAiAioifBhAXEiwApzCztnrLse88Prs8qlC7oyIdEhqz0TMP3DMl2-hSC756JV8SZFBKdksg1hoCaEoQAvD_BwE&gclsrc=aw.ds">
            <div class="card">
              <img src="./images/blog-img-2.jpeg" alt="blue hand bag" width="504" height="656">
              <h4>Blue</h4> 
              <p>VONI is a high-in-demand bag brand. Made out of intrecciato, the famous leather weave that dates back to the 1960s.VONI is a great choice for anyone who adores subtle design and extra-fine craftsmanship rather than flashy logos.</p>
            </div>
          </a>
          <a href="https://www.michaelkors.ca/handbags/view-all-handbags/_/N-282y?ecid=MKS_TEXT_P_GG_NBPR_CA_EN_HANDBAGS_X_PHRASE_11230790571_109672114229&gclid=CjwKCAiAioifBhAXEiwApzCztnrLse88Prs8qlC7oyIdEhqz0TMP3DMl2-hSC756JV8SZFBKdksg1hoCaEoQAvD_BwE&gclsrc=aw.ds">
            <div class="card">
              <img src="./images/blog-img-3.jpg" alt="black hand bag" width="513" height="686">
              <h4>Black hand bag</h4> 
              <p>The black one is good on the winter, it's very versatile and has the most unique design. You can also wear the black one if you like, on a very rainy spring. These bags are awesome. The blue one also has a unique style to it.</p>
            </div>
          </a>
          <div class="card">
            <video src="./videos/birklin.mp4" autoplay muted controls title="expensive birkin bags"  width="500" height="300"></video> 
            <h4>Berkin Bags</h4> 
            <p>Berkin Bags are One of the most luxirious bags. Birkin bags are handmade from leather and are named after the English-French actress and singer Jane Birkin.</p>
          </div>
        </div>

    </section>
    
  </main>

  <style>

/* page title */
h1{
  color: brown;
  font-size: clamp(1rem, 10vw, 4rem); 
  text-align: center;
  
  
}
/* parent */
section{
  width: 100%;
}

/* rows */
section .rows{
  max-width: auto;
  /* margin: auto; */
}

/* title in the rows */
.title{
  margin: auto;
  text-align: center;
}
.card img{
  max-width: 100%;
  height: auto;
  object-fit: cover;
  
}


/* card parent */
.content{
  display: grid;
  grid-auto-flow: column;
  grid-auto-columns: 2fr 2fr 2fr 4fr;
  
 
}

/* card holder */
.card{
  flex: 1;
  margin: 2rem 1.5rem;
}

/* border box only on images */
.card:nth-child(-n+3){
  box-shadow: 0px 0px 7px 0px darkred;

}
/* inside card title 2 */
.title h2{
  font-size: clamp(1.5rem, 2.5vw, 4rem); 
  font-family: 'Lato', Tahoma, Geneva, Verdana, sans-serif;
}


/* inside card title */
.content h4 {
    padding: 1rem;
    font-size: clamp(1rem, 2.5vw, 1.5rem); 
    color: hsla(0, 93%, 30%, 0.788);
}


  /* inside card paragraph */
.content p{
  font-size: clamp(1rem, 2vw, 1.2rem); 
    color: rgb(26, 4, 4);
    line-height: 1.5;
    padding: 1em;
} 

/* first three children of card element */
.card:nth-child(-n+3):hover{
  background-color: aquamarine;
  cursor: pointer;

}

/* hover on image cards only */
.card iframe{
  width: 100%;
  border: none;
}

@media only screen and (max-width: 60em){
  
  .content{
    display: flex;
    flex-direction: column;
  }
}
  </style>