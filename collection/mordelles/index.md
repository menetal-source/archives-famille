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
  <a href="https://menetal-source.github.io/archives-famille/" class="btn-nav" style="text-decoration: none;">← Retour à l'accueil</a>
</div>

<h1 class="titre-ville">Collection : Mordelles</h1>

<div class="carrousel-cadre">
  <div class="diapos-container" style="display:block;"><img src="../../assets/images/mordelles-place-1.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/mordelles-place-2.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/mordelles-place-3.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/mordelles-place-4.jpg"></div>
  <div class="diapos-container"><img src="../../assets/images/mordelles-place-5.jpg"></div>

  
  <div class="navigation-boutons">
    <button class="btn-nav" onclick="var s=document.getElementsByClassName('diapos-container'); s[window.idx-1].style.display='none'; window.idx--; if(window.idx<1)window.idx=s.length; s[window.idx-1].style.display='block'; document.getElementById('compteur').innerHTML=window.idx;">❮ Précédent</button>
    <span style="color:#2e4a62; font-family:sans-serif; font-weight:bold;">
      <span id="compteur">1</span> / 5
    </span>
    <button class="btn-nav" onclick="var s=document.getElementsByClassName('diapos-container'); s[window.idx-1].style.display='none'; window.idx++; if(window.idx>s.length)window.idx=1; s[window.idx-1].style.display='block'; document.getElementById('compteur').innerHTML=window.idx;">Suivant ❯</button>
  </div>
</div>

<script>window.idx = 1;</script>
