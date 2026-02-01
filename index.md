---
layout: single
author_profile: false
---

<style>
  /* 1. ON FAIT DISPARAÎTRE LE MENU DU HAUT ET LE TITRE DU THÈME */
  .masthead, .masthead__inner-wrapper, .masthead__menu {
    display: none !important;
    visibility: hidden !important;
    height: 0 !important;
    padding: 0 !important;
    margin: 0 !important;
  }

  /* 2. ON FORCE LE FOND BLEU CIEL PARTOUT */
  body, .page__inner-wrapper, .initial-content, .page {
    background-color: #e3f2fd !important;
    margin-top: 0 !important;
  }

  /* 3. STYLE DU GROS TITRE (Police Serif élégante) */
  .mon-grand-titre {
    color: #2e4a62 !important;
    font-family: "Playfair Display", "Times New Roman", serif !important;
    font-size: 2.8em !important;
    font-weight: bold !important;
    margin: 0 !important;
    letter-spacing: 1px;
  }

  /* 4. MENU MAISON */
  .custom-menu {
    display: flex;
    justify-content: center;
    background-color: #2e4a62;
    padding: 12px;
    border-radius: 8px;
    margin: 20px 0;
    list-style: none;
  }
  .custom-menu a {
    color: white !important;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    font-family: Arial, sans-serif;
  }
</style>

<div style="height: 30px;"></div>

<div style="display: flex; align-items: center; justify-content: center; background: white; padding: 30px; border-radius: 15px; border: 1px solid #d0e3f0; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
  
  <img src="assets/images/blason-gauche.png" style="width: 110px; height: auto; margin-right: 25px;" alt="Blason">

  <div style="text-align: center;">
    <h1 class="mon-grand-titre">Archives Lieneson & Menet</h1>
    <p style="font-style: italic; color: #5a7d9a; margin: 10px 0 0 0; font-size: 1.3em; font-family: serif;">Mémoire et Patrimoine Familial</p>
  </div>

  <img src="assets/images/blason-droit.png" style="width: 110px; height: auto; margin-left: 25px;" alt="Blason">

</div>

<nav class="custom-menu">
  <a href="/archives-famille/">ACCUEIL</a>
  <a href="#">FAMILLE LIENESON</a>
  <a href="#">FAMILLE MENET</a>
  <a href="#">COLLECTION</a>
</nav>

<div style="text-align: center; margin-top: 40px;">
  <h2 style="color: #2e4a62; font-family: serif; font-size: 1.8em;">Portrait de Constantin Lannoo</h2>
  <img src="assets/images/lannoo-constantin.png" style="width: 100%; max-width: 400px; border-radius: 8px; border: 8px solid white; box-shadow: 0 5px 25px rgba(0,0,0,0.2);">
</div>
