---
layout: single
author_profile: false
---

<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>

<style>
  /* 1. NETTOYAGE */
  .skip-links, .masthead, #site-nav, .page__footer, .page__title, .breadcrumb { display: none !important; }
  body, .page__inner-wrapper { background-color: #e3f2fd !important; }

  /* 2. TITRE */
  .titre-ville {
    color: #2e4a62 !important;
    font-family: "Apple Chancery", "Savoye LET", cursive !important;
    font-size: 3.5em !important;
    text-align: center;
    margin: 40px 0 !important;
  }

  /* 3. LE CARROUSEL (Taille moyenne par défaut) */
  .carousel-container {
    max-width: 600px; /* Taille moyenne comme demandé */
    margin: 0 auto;
    background: white;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  }

  .mon-carrousel img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    display: block;
  }

  /* Cache les textes parasites */
  .mon-carrousel p, .mon-carrousel span { display: none !important; }

  /* Flèches */
  .slick-prev:before, .slick-next:before { color: #2e4a62 !important; font-size: 30px; }
  
  .bouton-retour {
    display: inline-block;
    margin-bottom: 20px;
    padding: 10px 20px;
    background-color: #2e4a62;
    color: white !important;
    text-decoration: none;
    border-radius: 5px;
    font-family: sans-serif;
  }
</style>

<div style="text-align: center; margin-top: 20px;">
  <a href="/archives-famille/" class="bouton-retour">← Retour à l'accueil</a>
</div>

<h1 class="titre-ville">Collection : Lille</h1>

<div class="carousel-container">
  <div class="mon-carrousel">
    <div><img src="../../assets/images/lille.jpg"></div>
    <div><img src="../../assets/images/lille2.jpg"></div>
    <div><img src="../../assets/images/lille3.jpg"></div>
    <div><img src="../../assets/images/lille4.jpg"></div>
    <div><img src="../../assets/images/lille5.jpg"></div>
    <div><img src="../../assets/images/lille6.jpg"></div>
    <div><img src="../../assets/images/lille7.jpg"></div>
    <div><img src="../../assets/images/lille8.jpg"></div>
    <div><img src="../../assets/images/lille9.jpg"></div>
    <div><img src="../../assets/images/lille10.jpg"></div>
    <div><img src="../../assets/images/lille11.jpg"></div>
  </div>
</div>

<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>

<script>
  $(document).ready(function(){
    $('.mon-carrousel').slick({
      dots: true,
      infinite: true,
      speed: 500,
      fade: true,
      cssEase: 'linear',
      adaptiveHeight: true,
      arrows: true
    });
  });
</script>
