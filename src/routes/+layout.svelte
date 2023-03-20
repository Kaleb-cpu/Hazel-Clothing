  <script>
  import'./app.css';
  </script>
  
  <header>

    <!-- header navigation logo and title -->
  
    
    
      <a href="./" class="logo">
        <img src="./images/logo.PNG" alt="hazel logo">
        <span class="site-title">Hazel Clothing</span>
      </a>
      
      <input id="toggle" type="checkbox">

      <label class="hamburger" for="toggle">
        <div class="bar1"></div>
        <div class="bar2"></div>
        <div class="bar3"></div>
      </label>
     
    
    <!-- header navigation -->
    <nav>
      <ul class="main-nav">
        <li><a href="./">Home</a></li>
        <li><a href="./blog">Blog</a></li>
        <li><a href="./contact">Contact</a></li>
      </ul>
    </nav>
  
  
  </header>

   <slot></slot>

  <!-- company footer navigation  -->
  <footer>
    <div class="nav-media">
      <nav>
        <ul class="footer-nav">
          <li><a href="./">Home</a></li>
          <li><a href="./blog">Blog</a></li>
          <li><a href="./contact">Contact</a></li>
        </ul>
      </nav>
    </div>

      <!-- company social media -->
    <div class="social-media">
      <a href="https://twitter.com/explore"><i class="fa-brands fa-twitter"></i></a>
      <a href="https://www.instagram.com/"><i class="fa-brands fa-square-instagram"></i></a>
      <a href="https://www.facebook.com/"><i class="fa-brands fa-facebook"></i></a>
      <a href="https://www.youtube.com/"><i class="fa-brands fa-youtube"></i></a>
    </div>
      
    <!-- company information -->
   <div class="copy-right">
      <p>TERMS OF USE</p>
      <p>PRIVACY AND POLICY</p>
      <p>&copy; Kaleb Berhane. All rights reserved</p>
    </div>
  </footer>


  <style>
   
  </style>
  <!-- <slot></slot> -->
  