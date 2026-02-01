---
layout: single
author_profile: false
---

<style>
  .skip-links, .page__title, .masthead, .page__footer, .breadcrumb { display: none !important; }
  body, .page__inner-wrapper { background-color: #e3f2fd !important; padding-top: 0 !important; }
  
  .mon-grand-titre { 
    color: #2e4a62 !important; 
    font-family: "Apple Chancery", cursive !important; 
    font-size: 3.8em !important; 
    margin: 0 !important; 
    line-height: 1.1;
  }

  .menu-container { display: flex; justify-content: center; margin: 30px 0; font-family: sans-serif; }
  .custom-menu { display: flex; list-style: none; background: #2e4a62; padding: 0; margin: 0; border-radius: 8px; }
  .custom-menu > li { position: relative; }
  .custom-menu > li > a { color: white !important; text-decoration: none; padding: 15px 25px; display: block; font-weight: bold; }
  
  .submenu { 
    display: none; position: absolute; top: 100%; left: 0; 
    background: #3e5f7a; min-width: 180px; list-style: none; 
    padding: 0; margin: 0; z-index: 999; border-radius: 0 0 8px 8px; 
  }
  .custom-menu li:hover .submenu { display: block !important; }
  .submenu li a { color: white !important; padding: 10px 15px; display: block; text-decoration: none; border-bottom: 1px solid rgba(255,255,255,0.1); }
  .submenu li:hover { background: #2e4a62; }
</style>

<div style="height: 20px;"></div>

<div style="display: flex; align-items: center; justify-content: center; background: white; padding: 50px; border-radius: 20px; border: 1px solid #d0e3f0; box-shadow: 0 8px 25px rgba(0,0,0,0.1); max-width: 1200px; margin: 0 auto;">
  <img src="assets/images/blason-gauche.png" style="width: 250px; height: auto; margin-right: 50px;" alt="[Blason Lieneson]">
  <div style="text-align: center;">
    <h1 class="mon-grand-titre">Archives Lieneson & Menet</h1>
    <p style="font-family: serif; font-style: italic; color: #5a7d9a; font-size: 1.6em; margin: 15px 0 0 0;">Mémoire et Patrimoine Familial</p>
  </div>
  <img src="assets/images/blason-droit.png" style="width: 250px; height: auto; margin-left: 50px;" alt="[Blason Menet]">
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
