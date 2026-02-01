---
layout: single
author_profile: false
---

<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>

<style>
  /* 1. NETTOYAGE HABITUEL */
  .skip-links, .masthead, #site-nav, .page__footer, .page__title, .breadcrumb {
    display: none !important;
  }
  body, .page__inner-wrapper { background-color: #e3f2fd !important; }

  .titre-ville {
    color: #2e4a62 !important;
    font-family: "Apple Chancery", "Savoye LET", cursive !important;
    font-size: 3.5em !important;
    text-align: center;
    margin: 40px 0 !important;
  }

  /* 2. STYLE DU CARROUSEL */
  .carousel-container {
    max-width: 800px;
    margin: 0 auto;
    background: white;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  }

  .slick-slide img {
    width: 100%;
    height: auto;
    border-radius: 8px;
  }

  /* Style des flèches */
  .slick-prev:before, .slick-next:before {
    color: #2e4a62 !important;
    font-size: 30px;
  }
  
  .legende-carrousel {
    text-align: center;
    font-family: serif;
    font-style: italic;
    color: #5a7d9a;
    margin-top: 15px;
    font-size: 1.2em;
  }

  .bouton-retour {
    display: inline-block;
    margin-bottom: 20px;
    padding: 10px 20px;
    background-color: #2e4a62;
    color: white !important;
    text-decoration: none;
    border-radius: 5px;
  }
</style>

<div style="text-align: center; margin-top: 20px;">
  <a href="/archives-famille/" class="bouton-retour">← Retour à l'accueil</a>
</div>

<h1 class="titre-ville">Collection : Lille</h1>

<div class="carousel-container">
  <div class="mon-carrousel">
    <div>
      <img src="../../assets/images/lille.jpg">
      <p class="legende-carrousel">Légende de la photo 1</p>
    </div>
    <div>
      <img src="../../assets/images/lille2.jpg">
      <p class="legende-carrousel">Légende de la photo 2</p>
    </div>
    <div>
      <img src="../../assets/images/lille3.jpg">
      <p class="legende-carrousel">Légende de la photo 3</p>
    </div>
    <div><img src="../../assets/images/lille4.jpg"><p class="legende-carrousel">Photo 4</p></div>
    <div><img src="../../assets/images/lille5.jpg"><p class="legende-carrousel">Photo 5</p></div>
    <div><img src="../../assets/images/lille6.jpg"><p class="legende-carrousel">Photo 6</p></div>
    <div><img src="../../assets/images/lille7.jpg"><p class="legende-carrousel">Photo 7</p></div>
    <div><img src="../../assets/images/lille8.jpg"><p class="legende-carrousel">Photo 8</p></div>
    <div><img src="../../assets/images/lille9.jpg"><p class="legende-carrousel">Photo 9</p></div>
    <div><img src="../../assets/images/lille10.jpg"><p class="legende-carrousel">Photo 10</p></div>
    <div><img src="../../assets/images/lille11.jpg"><p class="legende-carrousel">Photo 11</p></div>
  </div>
</div>

<script type="text/javascript" src="https://code.jquery.com/jquery-1.11.0.min.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>

<script type="text/javascript">
  $(document).ready(function(){
    $('.mon-carrousel').slick({
      dots: true,         // Petits points en dessous
      infinite: true,     // Tourne en boucle
      speed: 500,         // Vitesse de transition
      fade: true,         // Effet de fondu (plus élégant pour des archives)
      cssEase: 'linear',
      adaptiveHeight: true
    });
  });
</script>
