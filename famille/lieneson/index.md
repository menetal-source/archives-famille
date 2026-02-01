---
layout: single
author_profile: false
---

<style>
  .skip-links, .masthead, #site-nav, .page__footer, .page__title, .breadcrumb { display: none !important; }
  body, .page__inner-wrapper { background-color: #e3f2fd !important; }
  .carrousel-cadre { max-width: 600px; margin: 40px auto; background: white; padding: 15px; border-radius: 15px; box-shadow: 0 10px 25px rgba(0,0,0,0.1); text-align: center; }
  .diapos-container { display: none; }
  .diapos-container img { width: 100%; height: auto; border-radius: 8px; display: block; margin: 0 auto; }
  .navigation-boutons { margin-top: 15px; display: flex; justify-content: center; align-items: center; gap: 20px; }
  .btn-nav { background: #2e4a62; color: white !important; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer; font-weight: bold; }
  .titre-ville { color: #2e4a62 !important; font-family: "Apple Chancery", cursive !important; font-size: 3.5em !important; text-align: center; margin: 20px 0 !important; }
</style>

<div style="text-align: center; margin-top: 20px;">
  <a href="/archives-famille/" class="btn-nav" style="text-decoration: none;">← Retour à l'accueil</a>
</div>

<h1 class="titre-ville">Famille Lieneson : Portraits</h1>

<div class="carrousel-cadre">
  <div class="diapos-container" style="display:block;"><img src="../../assets/images/lannoo-constantin-place-1.png"></div>
  <div class="diapos-container"><img src="../../assets/images/lannoo-emma-place-2.png"></div>
  <div class="diapos-container"><img src="../../assets/images/lannoo-jeanne-place-3.png"></div>
  <div class="diapos-container"><img src="../../assets/images/lannoo-zoe-place-4.png"></div>
  <div class="diapos-container"><img src="../../assets/images/debryck-rosalie-place-5.png"></div>

  <div class="navigation-boutons">
    <button class="btn-nav" onclick="changerDiapo(-1)">❮ Précédent</button>
    <span style="color:#2e4a62; font-family:sans-serif; font-weight:bold;">
      <span id="compteur">1</span> / 5
    </span>
    <button class="btn-nav" onclick="changerDiapo(1)">Suivant ❯</button>
  </div>
</div>

<script>
  // Initialisation de l'index
  var currentIndex = 1;
  var slides = document.getElementsByClassName("diapos-container");

  function changerDiapo(n) {
    // Masquer l'image actuelle
    slides[currentIndex - 1].style.display = "none";
    
    // Calculer le nouvel index
    currentIndex += n;
    
    // Boucler si on dépasse
    if (currentIndex > slides.length) { currentIndex = 1; }
    if (currentIndex < 1) { currentIndex = slides.length; }
    
    // Afficher la nouvelle image et mettre à jour le compteur
    slides[currentIndex - 1].style.display = "block";
    document.getElementById("compteur").innerHTML = currentIndex;
  }
</script>
