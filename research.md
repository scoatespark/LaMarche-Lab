---
layout: page
title: Research
permalink: /about/
---

Our primary research focuses on the following areas:

<style>
  :root{
    --maxw: 1100px;
    --gap: 1.25rem;
    --radius: 18px;
    --shadow: 0 6px 24px rgba(0,0,0,.08);
  }
  @media (prefers-color-scheme: dark){
    :root{ --shadow: 0 6px 24px rgba(0,0,0,.35); }
  }
  .research-wrap{ 
    box-sizing:border-box; 
    max-width: var(--maxw); 
    margin: 0 auto; 
    padding: 2rem 1rem 4rem; 
    font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
    line-height: 1.6;
  }
  .research-heading{
    font-size: clamp(2.25rem, 4vw, 3.5rem);
    font-weight: 700;
    letter-spacing: .5px;
    text-align: center;
    margin: 0 0 2rem 0;
  }
  .research-grid{
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    gap: var(--gap);
  }
  .project{
    grid-column: 1 / -1; /* full width on mobile */
    display: grid;
    grid-template-columns: 1fr; /* stacked on mobile */
    gap: var(--gap);
    padding: 1rem; 
    border-radius: var(--radius);
    box-shadow: var(--shadow);
    background: color-mix(in oklab, Canvas 96%, black 0%);
  }
  @media (min-width: 900px){
    .project{ grid-template-columns: 6fr 6fr; }
    /* alternate media on left/right for visual rhythm */
    .project:nth-child(even) .project-media{ order: 2; }
  }
  .project-media figure{ 
    margin:0; 
    border-radius:0;
    overflow:hidden; 
    background: none;
    border: none;
  }
  .project-media img{
    width: 100%; height: auto; display:block; object-fit: cover; 
    transition: transform .35s ease;
  }
  .project-media:hover img{ transform: scale(1.02); }
  .project-media figcaption{
    font-size: .925rem;
    padding: .6rem .9rem; 
    border-top: 1px solid color-mix(in oklab, CanvasText 20%, Canvas 85%);
    background: color-mix(in oklab, Canvas 96%, black 2%);
  }
  .project-body{ display:flex; flex-direction:column; gap:.6rem; }
  .project-title{ 
    font-weight: 800; 
    font-size: clamp(1.15rem, 1.2rem + .5vw, 1.6rem); 
    margin: .25rem 0 .25rem; 
  }
  .project-summary{ margin: 0.25rem 0 0.5rem; }
  .project-contact{ margin-top: auto; font-size: .975rem; }
  .project-contact a{ text-decoration: none; border-bottom: 1px solid currentColor; }
  .project-tags{ font-size: .85rem; opacity:.85; }
</style>

  <div class="research-grid">
    <!-- Chang-->
    <article class="project">
      <div class="project-media">
        <figure>
          <img src="/assets/Changimage.png" alt="Changimage.png" loading="lazy"/>
          <figcaption>fig caption...</figcaption>
        </figure>
      </div>
      <div class="project-body">
        <h2 class="project-title"><strong>Title</strong></h2>
        <p class="project-summary">description...</p>
        <p class="project-contact">Contact: <a href="mailto:chang.zhang@yale.edu">Chang</a></p>
        <p class="project-tags">Keywords: ... </p>
      </div>
    </article>

<!-- Myelopoiesis -->
    <article class="project">
      <div class="project-media">
    <figure>
      <img src="{{ '/assets/jakeimage.jpg' | relative_url }}" alt="myelopoiesis image" loading="lazy"/>
      <figcaption>"Understanding how lung cancer affects lymphocytes in regulating myelopoiesis."</figcaption>
    </figure>
  </div>
      <div class="project-body">
        <h2 class="project-title"><strong>Myelopoiesis</strong></h2>
        <p class="project-summary">description...</p>
        <p class="project-contact">Contact: <a href="mailto:jak.fontaine@yale.edu">Jake</a></p>
        <p class="project-tags">Keywords: ... </p>
      </div>
    </article>
    
    <!-- Metastasis -->
   <article class="project">
  <div class="project-media">
    <figure>
      <img src="{{ '/assets/sashaimage.png' | relative_url }}" alt="Metastasis" loading="lazy"/>
      <figcaption>Mets.</figcaption>
    </figure>
  </div>
  <div class="project-body">
    <h2 class="project-title"><strong>Immune Crosstalk in Cancer Metastasis</strong></h2>
    <p class="project-summary"> We are broadly focused on how cancers spread from primary tumors to distant organs, with an emphasis on the cellular and molecular mechanisms that prepare these secondary sites to receive tumor cells. In particular, we investigate the crosstalk between the immune system, stromal compartments, and the tumor itself, examining how these interactions contribute to the formation of supportive microenvironments that enable metastasis. By studying these processes, we aim to uncover how the immune and nervous systems shape metastatic niches and ultimately influence tumor progression, with the long-term goal of identifying strategies to disrupt these pathways and improve patient outcomes.</p>
    <p class="project-contact">Contact: <a href="mailto:sasha.coates-park@yale.edu">Sasha</a></p>
    <p class="project-tags">Keywords: ... </p>
  </div>
</article>

    <!-- RNA Sequencing -->
<article class="project">
  <div class="project-media">
    <figure>
      <img src="{{ '/assets/eduardoimage.png' | relative_url }}" alt="RNA sequencing data" loading="lazy"/>
      <figcaption>figcaption...</figcaption>
    </figure>
  </div>
  <div class="project-body">
    <h2 class="project-title"><strong>RNA Sequencing</strong></h2>
    <p class="project-summary">Description...</p>
    <p class="project-contact">Contact: <a href="mailto:eduardo.menotisilva@yale.edu>Eduardo</a></p>
    <p class="project-tags">Keywords: key words...</p>
  </div>
</article>

    <!-- Duplicate <article class="project">…</article> blocks for more projects -->

  </div>
