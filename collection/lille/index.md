---
layout: single
author_profile: false
---

<style>
  /* 1. NETTOYAGE DU THEME */
  .skip-links, .masthead, #site-nav, .page__footer, .page__title, .breadcrumb { display: none !important; }
  body, .page__inner-wrapper { background-color: #e3f2fd !important; }

  /* 2. STYLE DU CARROUSEL */
  .carrousel-cadre {
    max-width: 600px;
    margin: 40px auto;
    position: relative;
    background: white;
    padding: 15px;
    border-radius: 15px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    text-align: center;
  }

  .diapos-container {
    display: none; /* Cache toutes les photos par défaut */
  }

  .diapos-container img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    display: block;
  }

  /* 3. LES BOUTONS */
  .bouton-prec, .bouton-suiv {
    cursor: pointer;
    position: absolute;
    top: 50%;
    width: auto;
    padding: 16px;
    margin-top: -22px;
    color: #2e4a62;
    font-weight: bold;
    font-size: 25px;
    transition: 0.6s ease;
    user-select: none;
    text-decoration: none;
  }

  .bouton-prec { left: -50px; }
  .bouton-suiv { right: -50px; }

  .bouton-prec:hover, .bouton-suiv:hover { color: #3e5f7a; }

  .titre-ville {
    color: #2e4a62 !important;
    font-family: "Apple Chancery", cursive !important;
    font-size: 3.5em !important;
    text-align: center;
  }
</style>

<div style="text-align: center; margin-top: 20px;">
  <a href="/archives-famille/" style="text-decoration: none; color: #2e4a62; font-weight: bold;">← Accueil</a>
</div>

<h1 class="titre-ville">Collection : Lille</h1>

<div class="carrousel-cadre">
  <div class="diapos-container" style="display:block;">
    <img src="../../assets/images/lille-place-1.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-2.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-3.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-4.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-5.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-6.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-7.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-8.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-9.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-10.jpg">
  </div>
  <div class="diapos-container">
    <img src="../../assets/images/lille-place-11.jpg">
  </div>

  <a class="bouton-prec" onclick="changerDiapo(-1)">&#10094;</a>
  <a class="bouton-suiv" onclick="changerDiapo(1)">&#10095;</a>
  
  <div style="margin-top:1
