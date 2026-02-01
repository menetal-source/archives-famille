---
layout: single
author_profile: false
---

<style>
  /* 1. NETTOYAGE (Identique à l'accueil) */
  .skip-links, .masthead, #site-nav, .page__footer, .page__title, .breadcrumb {
    display: none !important;
  }

  body, .page__inner-wrapper {
    background-color: #e3f2fd !important;
  }

  /* 2. TITRE DE LA VILLE */
  .titre-ville {
    color: #2e4a62 !important;
    font-family: "Apple Chancery", "Savoye LET", cursive !important;
    font-size: 3.5em !important;
    text-align: center;
    margin: 40px 0 10px 0 !important;
  }

  /* 3. SYSTÈME DE GRILLE POUR LES CARTES */
  .galerie-cartes {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    padding: 20px;
    max-width: 1000px;
    margin: 0 auto;
  }

  .carte-item {
    background: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    text-align: center;
    transition: transform 0.2s;
  }

  .carte-item:hover {
    transform: scale(1.02); /* Petit effet de zoom au survol */
  }

  .carte-item img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    border: 1px solid #eee;
  }

  .legende {
    font-family: serif;
    font-style: italic;
    color: #5a7d9a;
    margin-top: 15px;
    font-size: 1.1em;
  }

  .bouton-retour {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background-color: #2e4a62;
    color: white !important;
    text-decoration: none;
    border-radius: 5px;
    font-family: sans-serif;
    font-size: 0.9em;
  }
</style>

<div style="text-align: center; margin-top: 20px;">
  <a href="/archives-famille/" class="bouton-retour">← Retour à l'accueil</a>
</div>

<h1 class="titre-ville">Collection : Lille</h1>

<div style="text-align: center; max-width: 700px; margin: 0 auto; font-family: serif; color: #2e4a62;">
  <p>Découvrez ici les cartes postales anciennes et les souvenirs photographiques de la ville de Lille.</p>
</div>

<div class="galerie-cartes">
  
  <div class="carte-item">
    <img src="../../assets/images/lille-place.jpg" alt="La Grande Place">
    <p class="legende">La Grande Place - Début du XXème siècle</p>
  </div>

  <div class="carte-item">
    <img src="../../assets/images/lille-beffroi.jpg" alt="Le Beffroi">
    <p class="legende">Vue sur le Beffroi</p>
  </div>

  </div>
