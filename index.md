---
layout: single
author_profile: false
---

<style>
  /* 1. SUPPRESSION DU TITRE ET DES PARASITES */
  .page__title, .skip-links, .masthead, #site-nav, .page__footer, .breadcrumb {
    display: none !important;
  }

  /* 2. FOND ET MISE EN PAGE */
  body, .page__inner-wrapper {
    background-color: #e3f2fd !important;
    padding-top: 0 !important;
  }

  /* 3. POLICE ET TITRES */
  .mon-grand-titre {
    color: #2e4a62 !important;
    font-family: "Apple Chancery", "Savoye LET", cursive !important;
    font-size: 3.5em !important;
    margin: 0 !important;
  }

  /* 4. MENU HORIZONTAL ET DÉROULANT */
  .menu-container { display: flex; justify-content: center; margin: 20px 0; }
  
  ul.custom-menu { 
    display: flex !important; 
    background-color: #2e4a62; 
    padding: 0; margin: 0; 
    list-style: none !important; 
    border-radius: 8px; 
  }
  
  ul.custom-menu > li { position: relative; }
  
  ul.custom-menu > li > a { 
    color: white !important; 
    text-decoration: none; 
    padding: 15px 25px; 
    display: block; 
    font-weight: bold;
    font-family: sans-serif;
  }

  /* Configuration du sous-menu */
  ul.submenu { 
    display: none; 
    position: absolute; 
    top: 100%; 
    left: 0; 
    background-color: #3e5f7a; 
    min-width: 180px; 
    list-style: none !important; 
    padding: 0; 
    margin: 0;
    border-radius: 0 0 8px 8px;
    z-index: 999; 
  }

  /* Faire apparaître le sous-menu au survol */
  ul.custom-menu li:hover ul.submenu { 
    display: block !important; 
  }

  ul.submenu li a { 
    color: white !important; 
    padding: 12px 15px; 
    display: block; 
    text-decoration: none;
    font-size: 0.9em;
    border-bottom: 1px solid rgba(255,255,255,0.1);
  }
  
  ul.submenu li:hover { background-color: #2e4a62; }
</style>

<div style="height: 20px;"></div>

<div style="display: flex; align-items: center; justify-content: center; background: white; padding: 40px; border-radius: 15px; border: 1px solid #d0e3f0; box-shadow: 0 4px 15px rgba(0,0,0,0.1); max-width: 950px; margin: 0 auto;">
  <img src="assets/images/blason-gauche.png" style="width: 120px; height: auto; margin-right: 30px;">
  <div style="text-align: center;">
    <h1 class="mon-grand-titre">Archives Lieneson & Menet</h1>
    <p style="font-family: serif; font-style: italic; color: #5a7d9a; font-size: 1.5em; margin: 10px 0 0 0;">Mémoire et Patrimoine Familial</p>
  </div>
  <img src="assets/images/blason-droit.png" style="width: 120px; height: auto; margin-left: 30px;">
</div>

<div class="menu-container">
  <ul class
