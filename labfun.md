---
layout: page
title: Lab Fun
permalink: /labfun/
---

<div class="cta-row">
  <div class="cta-copy">
    <h2>Want a quick brain break?</h2>
    <p>Play our lab’s custom game (developed/written by Eduardo Menotti) right here:</p>
    <p><a href="https://edumenotti.github.io/cytokine-wordle/" target="_blank" rel="noopener">Cytokine of the Day</a></p>
    <p>Use the hint button to learn about your cytokine</p>
  </div>

  <!-- Smaller clickable image on the right -->
  <div class="cta-image">
    <a href="https://edumenotti.github.io/cytokine-wordle/" target="_blank" rel="noopener" aria-label="Play Cytokine of the Day">
      <img src="/assets/cytokineoftheday.png" alt="Cytokine of the Day game preview">
    </a>
  </div>
</div>

<br><br>

<!-- Collage (now outside of any <style> block) -->
<div class="photo-collage-vertical">
  <img src="/assets/SeptemberinBangkok.png" alt="Lab dinner">
  <img src="/assets/LabFieldDay.png" alt="Lab Field Day">
</div>

<h2>More photos incoming… </h2>
<p>We’re compiling our favorite lab moments.</p>

<style>
/* Right-side thumbnail next to text */
.cta-row {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  gap: 25px;
  flex-wrap: wrap;
}
.cta-copy { flex: 1 1 400px; min-width: 280px; }
.cta-image { flex: 0 0 auto; }
.cta-image img {
  width: 150px;   /* keep this size */
  height: auto;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.15);
  vertical-align: middle;
  transition: transform 0.2s ease;
}
.cta-image img:hover { transform: scale(1.05); }

@media (max-width: 700px) {
  .cta-row { flex-direction: column; align-items: flex-start; }
  .cta-image img { width: 60%; margin-top: 10px; }
}

/* Collage */
.photo-collage {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 12px;
  justify-items: center;
  align-items: center;
  margin-top: 1rem;
}
.photo-collage img {
  width: 100%;
  height: 100%;
  max-height: 350px;
  object-fit: contain;   /* show full image, no cropping */
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
  background-color: #fafafa;
}
</style>
