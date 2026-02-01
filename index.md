---
layout: single
author_profile: false
---

<style>
  /* --- AJUSTEMENT DU MENU POUR LES SOUS-MENUS --- */
  .custom-menu {
    display: flex;
    justify-content: center;
    background-color: #2e4a62;
    padding: 0; /* On gère le padding dans les li */
    border-radius: 8px;
    margin: 20px auto;
    max-width: 950px;
    list-style: none;
  }

  .custom-menu > li {
    position: relative; /* Important pour placer le sous-menu */
  }

  .custom-menu a {
    color: white !important;
    text-decoration: none;
    padding: 15px 20px;
    display: block;
    font-weight: bold;
    font-family: sans-serif;
    font-size: 0.9em;
  }

  /* Style du sous-menu (caché par défaut) */
  .submenu {
    display: none;
    position: absolute;
    top: 100%; /* Juste en dessous du parent */
    left: 0;
    background-color: #3e5f7a; /* Un bleu un peu différent */
    min-width: 180px;
    border-radius: 0 0 8px 8px;
    margin: 0;
    padding: 0;
    list-style: none;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    z-index: 999;
  }

  .submenu li {
    border-bottom: 1px solid rgba(255,255,255,0.1);
  }

  .submenu a {
    padding: 10px 15px;
    font-size: 0.85em;
    text-transform: none; /* Pas tout en majuscules pour les villes */
  }

  .submenu a:hover {
    background-color: #2e4a62;
  }

  /* Affiche le sous-menu au survol de "COLLECTION" */
  .custom-menu > li:hover .submenu {
    display: block;
  }
</style>

<nav>
  <ul class="custom-menu">
    <li><a href="/archives-famille/">ACCUEIL</a></li>
    <li><a href="#">FAMILLE LIENESON</a></li>
    <li><a href="#">FAMILLE MENET</a></li>
    
    <li>
      <a href="#">COLLECTION ▾</a>
      <ul class="submenu">
        <li><a href="/archives-famille/collection/lille/">Lille</a></li>
        <li><a href="/archives-famille/collection/reims/">Reims</a></li>
        <li><a href="/archives-famille/collection/lyon/">Lyon</a></li>
        <li><a href="/archives-famille/collection/mordelles/">Mordelles</a></li>
      </ul>
    </li>
  </ul>
</nav>

<div style="height: 40px;"></div>

<div style="display: flex; align-items: center; justify-content: center; background: white; padding: 40px; border-radius: 15px; border: 1px solid #d0e3f0; box-shadow: 0 4px 15px rgba(0,0,0,0.1); max-width: 950px; margin: 0 auto;">
  
  <img src="assets/images/blason-gauche.png" style="width: 120px; height: auto; margin-right: 30px;" alt="Blason Gauche">

  <div style="text-align: center;">
    <h1 class="mon-grand-titre">Archives Lieneson & Menet</h1>
    <p class="mon-sous-titre">Mémoire et Patrimoine Familial</p>
  </div>

  <img src="assets/images/blason-droit.png" style="width: 120px; height: auto; margin-left: 30px;" alt="Blason Droit">

</div>

<nav class="custom-menu">
  <a href="/archives-famille/">ACCUEIL</a>
  <a href="#">FAMILLE LIENESON</a>
  <a href="#">FAMILLE MENET</a>
  <a href="#">COLLECTION</a>
</nav>

<div style="text-align: center; margin-top: 40px; padding-bottom: 50px;">
  <h2 style="color: #2e4a62; font-family: serif; margin-bottom: 20px;">Portrait de Constantin Lannoo</h2>
  <img src="assets/images/lannoo-constantin.png" style="width: 100%; max-width: 420px; border-radius: 8px; border: 10px solid white; box-shadow: 0 5px 25px rgba(0,0,0,0.2);">
</div>
