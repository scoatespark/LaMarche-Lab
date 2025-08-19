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
    border-radius: calc(var(--radius) - 4px); 
    overflow:hidden; 
    background: color-mix(in oklab, Canvas 94%, black 3%);
    border: 1px solid color-mix(in oklab, CanvasText 20%, Canvas 85%);
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
    <!-- Project 1 -->
    <article class="project">
      <div class="project-media">
        <figure>
          <img src="/assets/images/research/adar1-b16.png" alt="Heatmap-like microscopy images showing immune cell niches after loss of ADAR1 in B16 melanoma" loading="lazy"/>
          <figcaption>Loss of ADAR1 reshapes the B16 melanoma tumor microenvironment.</figcaption>
        </figure>
      </div>
      <div class="project-body">
        <h2 class="project-title"><strong>The role of RNA editing and dsRNA sensing in anti‑tumor immunity</strong></h2>
        <p class="project-summary">We identified the RNA‑editing enzyme ADAR1 as a target to improve immune checkpoint blockade. We now investigate how unedited dsRNA activates innate pathways to enhance tumor rejection and how these mechanisms can be translated into durable patient benefit.</p>
        <p class="project-contact">Contact: <a href="mailto:firstname.lastname@yale.edu">Firstname Lastname</a></p>
        <p class="project-tags">Keywords: ADAR1, dsRNA, interferon signaling, checkpoint blockade</p>
      </div>
    </article>

    <!-- Project 2 -->
    <article class="project">
      <div class="project-media">
        <figure>
          <img src="/assets/images/research/ifn-rescue-screen.png" alt="Scatter plot from a genome-wide CRISPR screen highlighting interferon pathway genes" loading="lazy"/>
          <figcaption>Genome‑wide CRISPR screen for rescue of an IFN‑sensitization phenotype identifies key nodes.</figcaption>
        </figure>
      </div>
      <div class="project-body">
        <h2 class="project-title"><strong>Identification of novel drug targets for immunotherapy</strong></h2>
        <p class="project-summary">Using pooled CRISPR/Cas9 functional genomics, we discover and validate genes that overcome resistance to immunotherapy. We combine <em>in vitro</em> and <em>in vivo</em> models to define the patient subsets most likely to benefit from targeted interventions.</p>
        <p class="project-contact">Contact: <a href="mailto:pi.lastname@yale.edu">PI Lastname</a></p>
        <p class="project-tags">Keywords: CRISPR screens, interferon pathway, resistance mechanisms</p>
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
        <p class="project-summary">        </p>
        <p class="project-contact">Contact: <a href="mailto:firstname.lastname@yale.edu">Firstname Lastname</a></p>
        <p class="project-tags">Keywords: ADAR1, dsRNA, interferon signaling, checkpoint blockade</p>
      </div>
    </article>
    
    <!-- RNA Sequencing -->
<article class="project">
  <div class="project-media">
    <figure>
      <img src="{{ '/assets/eduardoimage.png' | relative_url }}" alt="RNA sequencing data" loading="lazy"/>
      <figcaption>RNA seq data...</figcaption>
    </figure>
  </div>
  <div class="project-body">
    <h2 class="project-title"><strong>RNA Sequencing</strong></h2>
    <p class="project-summary">Using pooled CRISPR/Cas9 functional genomics, we discover and validate genes that overcome resistance to immunotherapy. We combine <em>in vitro</em> and <em>in vivo</em> models to define the patient subsets most likely to benefit from targeted interventions.</p>
    <p class="project-contact">Contact: <a href="mailto:"Menoti Silva, Eduardo" <eduardo.menotisilva@yale.edu>">Eduardo</a></p>
    <p class="project-tags">Keywords: CRISPR screens, interferon pathway, resistance mechanisms</p>
  </div>
</article>

    <!-- Duplicate <article class="project">…</article> blocks for more projects -->

  </div>
