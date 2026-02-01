---
layout: single
author_profile: false
---

<style>
  /* 1. SUPPRESSION DES ÉLÉMENTS INDÉSIRABLES */
  .skip-links, .masthead, .page__footer, .page__title, .breadcrumb { display: none !important; }
  body, .page__inner-wrapper { background-color: #e3f2fd !important; padding: 0 !important; }

  /* 2. STYLE DU TITRE ET BLASONS */
  .mon-grand-titre { 
    color: #2e4a62 !important; 
    font-family: cursive, serif !important; 
    font-size: 3.2em !important; 
    margin: 0 !important; 
  }

  /* 3. MENU DÉROULANT */
  .menu-container { display: flex; justify-content: center; margin: 25px 0; font-family: sans-serif; position: relative; z-index: 1000; }
  .custom-menu { display: flex; list-style: none !important; background: #2e4a62; padding: 0; margin: 0; border-radius: 8px; }
  .custom-menu > li { position: relative; }
  .custom-menu > li > a { color: white !important; text-decoration: none; padding: 15px 22px; display: block; font-weight: bold; }
  
  .submenu { 
    display: none; position: absolute; top: 100%; left: 0; 
    background: #3e5f7a; min-width: 180px; list-style: none !important; padding: 0; z-index: 999; border-radius: 0 0 8px 8px;
  }
  .custom-menu li:hover .submenu { display: block !important; }
  .submenu li a { color: white !important; padding: 10px 15px; display: block; text-decoration: none; border-bottom: 1px solid rgba(255,255,255,0.1); }
</style>

<div style="display: flex; align-items: center; justify-content: center; background: white; padding: 30px; border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); max-width: 1100px; margin: 20px auto;">
  <img src="assets/images/blason-gauche.png" style="width: 220px; height: auto;" alt="Blason Gauche">
  <div style="text-align: center; padding: 0 30px;">
    <h1 class="mon-grand-titre">Archives Lieneson & Menet</h1>
    <p style="font-style: italic; color: #5a7d9a; font-size: 1.2em;">Mémoire et Patrimoine Familial</p>
  </div>
  <img src="assets/images/blason-droit.png" style="width: 220px; height: auto;" alt="Blason Droit">
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
        <li><a href="/archives-famille/collection/lyon/">Lyon</a></li>
        <li><a href="/archives-famille/collection/mordelles/">Mordelles</a></li>
      </ul>
    </li>
  </ul>
</div>

<div style="text-align: center; margin-bottom: 40px;">
  <img src="assets/images/coupain-joly.jpg" style="max-width: 600px; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.1);" alt="Photo accueil">
</div>

<div style="max-width: 850px; margin: 0 auto 50px auto; color: #2e4a62; font-family: sans-serif; line-height: 1.8; text-align: justify; background: white; padding: 40px; border-radius: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.05);">
  <h2 style="text-align: center; font-family: cursive; font-size: 2em; margin-top: 0;">Présentation du projet</h2>
  
  <p>Ce projet est né de la volonté de préserver et de transmettre la mémoire des familles <strong>Lieneson</strong> et <strong>Menet</strong>. À travers ce portail, vous découvrirez une collection de photographies, de documents et d'objets qui retracent plusieurs générations d'histoire.</p>

  <p>Réalisé dans le cadre d'une <strong>Licence professionnelle en documentation</strong>, ce site n'est pas seulement une galerie de souvenirs : c'est un outil de gestion documentaire structuré. Il utilise des technologies modernes comme <strong>Jekyll</strong> et des métadonnées en <strong>YAML</strong> pour garantir que ces archives restent accessibles, organisées et pérennes dans le temps.</p>

  <p style="text-align: center; font-style: italic; margin-top: 20px; border-top: 1px solid #eee; padding-top: 20px;">
    Explorez nos collections par ville ou par famille via le menu ci-dessus pour plonger dans notre patrimoine commun.
  </p>
</div>
