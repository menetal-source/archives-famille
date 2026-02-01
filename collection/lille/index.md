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

  .titre-ville {
    color: #2e4a62 !important;
    font-family: "Apple Chancery", "Savoye LET", cursive !important;
    font-size: 3.5em !important;
    text-align: center;
    margin: 40px 0 !important;
  }

  /* 2. IMAGE D'ACCUEIL (Taille moyenne) */
  .image-principale-container {
    text-align: center;
    margin-bottom: 30px;
  }

  .image-moyenne {
    width: 100%;
    max-width: 500px;
    height: auto;
    border-radius: 10px;
    border: 10px solid white;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
  }

  /* 3. LE BOUTON */
  .bouton-album {
    display: inline-block;
    background-color: #2e4a62;
    color: white !important;
    padding: 12px 25px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    font-family: sans-serif;
    cursor: pointer;
    border: none;
    transition: background 0.3s;
  }
  .bouton-album:hover { background-color: #3e5f7a; }

  /* 4. LA FENÊTRE CACHÉE (MODAL) */
  #album-modal {
    display: none;
    position: fixed;
    z-index: 9999;
    left: 0; top: 0;
    width: 100%; height: 100%;
    background-color: rgba(0,0,0,0.9);
  }

  .modal-content {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    max-width: 900px;
    margin: auto;
    padding: 20px;
  }

  .close-modal {
    position: absolute;
    top: -40px;
    right: 10px;
    color: white;
    font-size: 40px;
    cursor: pointer;
  }

  /* On cache tout texte qui pourrait apparaître sous les photos */
  .slick-slide p, .slick-slide span { display: none !important; }
</style>

<div style="text-align: center; margin-top: 20px;">
  <a href="/archives-famille/" style="text-decoration: none; color: #2e4a62; font-weight: bold;">← Accueil</a>
</div>

<h1 class="titre-ville">Collection : Lille</h1>

<div class="image-principale-container">
  <img src="../../assets/images/lille-place-1.jpg" class="image-moyenne">
  <br><br>
  <button class="bouton-album" onclick="ouvrirAlbum()">Voir les 11 photos</button>
</div>

<div id="album-modal">
  <div class="modal-content">
    <span class="close-modal" onclick="fermerAlbum()">&times;</span>
    <div class="mon-carrousel">
      <div><img src="../../assets/images/lille.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille2.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille3.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille4.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille5.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille6.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille7.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille8.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille9.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille10.jpg" style="width:100%"></div>
      <div><img src="../../assets/images/lille11.jpg" style="width:100%"></div>
    </div>
  </div>
</div>

<script type="text/javascript" src="https://code.jquery.com/jquery-1.11.0.min.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>

<script type="text/javascript">
  function ouvrirAlbum() {
    document.getElementById('album-modal').style.display = "block";
    // On initialise le carrousel seulement à l'ouverture pour éviter les bugs
    $('.mon-carrousel').slick({
      dots: true,
      infinite: true,
      speed: 400,
      fade: true,
      cssEase: 'linear'
    });
  }

  function fermerAlbum() {
    document.getElementById('album-modal').style.display = "none";
    $('.mon-carrousel').slick('unslick'); // On réinitialise pour la prochaine fois
  }
</script>
