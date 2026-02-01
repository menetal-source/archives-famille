---
layout: single
author_profile: false
---

<style>
  /* 1. SUPPRESSION DES BLOCAGES */
  .skip-links, .page__title, .masthead, .page__footer, .breadcrumb { display: none !important; }
  body, .page__inner-wrapper { background-color: #e3f2fd !important; padding: 0 !important; margin: 0 !important; }

  /* 2. TITRE */
  .mon-grand-titre { 
    color: #2e4a62 !important; 
    font-family: "Apple Chancery", cursive !important; 
    font-size: 3.5em !important; 
    margin: 0 !important; 
  }

  /* 3. MENU DÉROULANT (FORCÉ) */
  .menu-container { display: flex; justify-content: center; margin: 30px 0; font-family: sans-serif; position: relative; z-index: 1000; }
  .custom-menu { display: flex; list-style: none !important; background: #2e4a62; padding: 0; margin: 0; border-radius: 8px; }
  .custom-menu > li { position: relative; }
  .custom-menu > li > a { color: white !important; text-decoration: none; padding: 15px 25px; display: block; font-weight: bold; }

  /* Sous-menus */
  .submenu { 
    display: none; 
    position: absolute; 
    top: 100%; 
    left: 0; 
    background: #3e5f7a; 
    min-width: 200px; 
    list-style: none !important; 
    padding: 0; margin: 0; 
    z-index: 9999; 
    border-radius: 0 0 8px 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
  }

  /* L'effet de survol magique */
  .custom-menu li:hover .submenu { display: block !important; }
  
  .submenu li a { 
    color: white !important; 
    padding: 12px 20px; 
    display: block; 
    text-decoration: none; 
    border-bottom: 1px solid rgba(255,255,255,0.1); 
  }
  .submenu li:hover { background: #2e4a62; }
</style>

<div style="height: 20px;"></div>

<div style="display: flex; align-items: center; justify-content: center; background: white; padding: 40px; border-radius: 20px; border: 1px solid #d0e3f0; box-shadow: 0 8px 25px rgba(0,0,0,0.1); max-width: 1100px; margin: 0 auto;">
  <img src="assets/images/blason-gauche.png" style="width: 220px; height: auto; margin-right: 40px;" alt="Blason">
  <div style="text-align: center;">
    <h1 class="mon-grand-titre">Archives Lieneson & Menet</h1>
    <p style="font-family: serif; font-style: italic; color: #5a7d9a; font-size: 1.4em; margin: 10px 0 0 0;">Mémoire et Patrimoine Familial</p>
  </div>
  <img src="assets/images/blason-droit.png" style="width: 220px; height: auto; margin-left: 40px;" alt="Blason">
</div>

<div class="menu-container">
  <ul class="custom-menu">
    <li><a href="/archives-famille/">ACCUEIL</a></li>
    
    <li>
      <a href="#">FAMILLE LIENESON ▾</a>
      <ul class="submenu">
        <li><a href="/archives-famille/famille/lieneson/">Galerie</a></li>
        <li><a href="#">Documents</a></li>
      </ul>
    </li>

    <li>
      <a href="#">FAMILLE MENET ▾</a>
      <ul class="submenu">
        <li><a href="/archives-famille/famille/menet/">Galerie</a></li>
        <li><a href="#">Documents</a></li>
      </ul>
    </li>

    <li>
      <a href="#">COLLECTION ▾</a>
      <ul class="submenu">
        <li><a href="/archives-famille/collection/lille/">Lille</a></li>
        <li><a href="/archives-famille/collection/reims/">Reims</a></li>
        <li><a href="/archives-famille/collection/mordelles/">Mordelles</a></li>
      </ul>
    </li>
  </ul>
</div>

<div style="text-align: center;">
  <img src="assets/images/coupain-joly.jpg" style="max-width: 650px; height: auto; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); margin-bottom: 30px;">
  
  <div style="max-width: 800px; margin: 0 auto; padding: 0 20px; color: #2e4a62; font-family: sans-serif; line-height: 1.8; text-align: justify;">
    <h2 style="font-family: 'Apple Chancery', cursive; text-align: center; font-size: 2em;">Présentation du projet</h2>
    <p>Ce projet est né de la volonté de préserver et de transmettre la mémoire des familles <strong>Lieneson</strong> et <strong>Menet</strong>. À travers ce portail, vous découvrirez une collection de photographies, de documents et d'objets qui retracent plusieurs générations d'histoire.</p>
    <p>Réalisé dans le cadre d'une <strong>Licence professionnelle en documentation</strong>, ce site n'est pas seulement une galerie de souvenirs : c'est un outil de gestion documentaire structuré. Il utilise des technologies modernes comme <strong>Jekyll</strong> et des métadonnées en <strong>YAML</strong> pour garantir que ces archives restent accessibles, organisées et pérennes dans le temps.</p>
  </div>
</div>
