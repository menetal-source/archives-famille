---
layout: single
author_profile: false
---

<style>
  /* SUPPRESSION DU TITRE ET MISE EN PAGE */
  .page__title, .masthead, .page__footer, .breadcrumb { display: none !important; }
  body, .page__inner-wrapper { background-color: #e3f2fd !important; }

  /* MENU */
  .menu-container { display: flex; justify-content: center; margin: 20px 0; font-family: sans-serif; }
  .custom-menu { display: flex; list-style: none; background: #2e4a62; padding: 0; margin: 0; border-radius: 8px; }
  .custom-menu > li { position: relative; }
  .custom-menu > li > a { color: white !important; text-decoration: none; padding: 15px 25px; display: block; font-weight: bold; }

  /* SOUS-MENU */
  .submenu { 
    display: none; 
    position: absolute; 
    top: 100%; 
    left: 0; 
    background: #3e5f7a; 
    min-width: 180px; 
    list-style: none; 
    padding: 0; 
    margin: 0; 
    z-index: 999;
    border-radius: 0 0 8px 8px;
  }

  /* SURVOL */
  .custom-menu li:hover .submenu { display: block !important; }
  .submenu li a { color: white !important; padding: 10px 15px; display: block; text-decoration: none; border-bottom: 1px solid rgba(255,255,255,0.1); }
  .submenu li:hover { background: #2e4a62; }
</style>

<div style="text-align: center; background: white; padding: 30px; border-radius: 15px; max-width: 900px; margin: 20px auto; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
  <h1 style="color: #2e4a62; font-family: 'Apple Chancery', cursive; font-size: 3em; margin: 0;">Archives Lieneson & Menet</h1>
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
    <li><a href="#">FAMILLE MENET</a></li>
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
  <img src="assets/images/coupain-joly.jpg" style="max-width: 600px; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.1);">
  <div style="max-width: 700px; margin: 30px auto; color: #2e4a62; font-family: sans-serif; line-height: 1.6; padding: 0 20px;">
    <strong>Bienvenue sur mon site d'archives familiales.</strong><br>
    Ce projet est un portail documentaire d'archives familiales réalisé dans le cadre de ma formation.
  </div>
</div>
