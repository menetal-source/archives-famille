---
layout: single
author_profile: false
---

<style>
  /* 1. NETTOYAGE DU THEME */
  .skip-links, .masthead, #site-nav, .page__footer, .page__title, .breadcrumb { display: none !important; }
  body, .page__inner-wrapper { background-color: #e3f2fd !important; }

  /* 2. STYLE DU CADRE PHOTO */
  .carrousel-cadre {
    max-width: 600px; /* Taille moyenne */
    margin: 40px auto;
    background: white;
    padding: 15px;
    border-radius: 15px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    text-align: center;
  }

  .diapos-container {
    display: none; 
  }

  .diapos-container img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    display: block;
    margin: 0 auto;
  }

  /* 3. NAVIGATION */
  .navigation-boutons {
    margin-top: 15px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
  }

  .btn-nav {
    background: #2e4a62;
    color: white !important;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold;
    font-size: 0.9em;
  }

  .btn-nav:hover { background: #3e5f7a; }

  .titre-ville {
    color: #2e4a62 !important;
    font-family: "Apple Chancery", cursive !important;
    font-size: 3.5em !important;
    text-align: center;
    margin: 20px 0 !important;
  }
</style>

<div style="text-align: center; margin-top: 20px;">
  <a href="/archives-famille/" style="text-decoration: none; color: #2e4a62; font-weight: bold;">← Accueil</a>
</div>

<h1 class="titre-ville">Collection : Lille</h1>

<div class="carrousel-cadre">
  <div class="diapos-container" style="display:block;"><img src="../../assets/images/lille-place-1.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-2.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-3.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-4.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-5.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-6.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-7.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-8.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-9.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-10.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/lille-place-11.jpg"></div>

  <div class="navigation-boutons">
    <button class="btn-nav" onclick="changer(-1)">❮ Précédent</button>
    <span style="color:#2e4a62; font-family:sans-serif; font-weight:bold;">
      <span id="compteur">1</span> / 11
    </span>
    <button class="btn-nav" onclick="changer(1)">Suivant ❯</button>
  </div>
</div>

<script type="text/javascript">
/*<![CDATA[*/
  var index = 1;
  
  function changer(n) {
    var slides = document.getElementsByClassName("diapos-container");
    if (!slides || slides.length === 0) return;

    // Cache la diapo actuelle
    slides[index-1].style.display = "none";
    
    // Calcule le nouvel index
    index += n;
    if (index > slides.length) {index = 1}
    if (index < 1) {index = slides.length}
    
    // Affiche la nouvelle diapo
    slides[index-1].style.display = "block";
    
    // Met à jour le compteur
    document.getElementById("compteur").innerHTML = index;
  }
/*]]>*/
</script>
