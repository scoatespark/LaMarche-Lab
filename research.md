---
layout: page
title: Research
permalink: /research/
published: false
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
    font-weight: 500;
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
    font-weight: 600; 
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
    <figure class="research-figure">
  <img src="{{ '/assets/jakeimage.jpg' | relative_url }}" 
       alt="myelopoiesis" 
       class="research-image">
  <figcaption>
    Understanding how lung cancer affects lymphocytes in regulating myelopoiesis
  </figcaption>
</figure>
  </div>
  <div class="project-body">
    <h2 class="project-title"><strong>Lung Cancer-Driven Regulation of Myelopoiesis</strong></h2>
    <p class="project-summary">We are investigating how lung cancer alters myelopoiesis by studying the signals that tumors send to lymphocytes and other immune cells, and how these changes reprogram the bone marrow to influence myeloid cell development and support cancer progression</p>
    <p class="project-contact">Contact: <a href="mailto:jake.fontaine@yale.edu">Jake</a></p>
    <p class="project-tags">Keywords: Myelopoiesis, Bone Marrow, Lymphocytes </p>
  </div>
</article>
    
    <!-- Metastasis -->
   <article class="project">
  <div class="project-media">
    <figure class="research-figure">
  <img src="{{ '/assets/Sashaimage.png' | relative_url }}" 
       alt="metastasis" 
       class="research-image">
  <figcaption>
    Immunofluorescence staining of dural meninges showing nociceptors (magenta), 
    myeloid cells (green), basophils (red), and nuclei (blue). 
    This image highlights spatial interactions between nociceptors and immune cell populations 
    within the tissue microenvironment.
  </figcaption>
</figure>
  </div>
  <div class="project-body">
    <h2 class="project-title"><strong>Immune Crosstalk in Cancer Metastasis</strong></h2>
    <p class="project-summary">We are broadly focused on how cancers spread from primary tumors to distant organs, with an emphasis on the cellular and molecular mechanisms that prepare these secondary sites to receive tumor cells. In particular, we investigate the crosstalk between the immune system, stromal compartments, and the tumor itself, examining how these interactions contribute to the formation of supportive microenvironments that enable metastasis. By studying these processes, we aim to uncover how the immune and nervous systems shape metastatic niches and ultimately influence tumor progression, with the long-term goal of identifying strategies to disrupt these pathways and improve patient outcomes</p>
    <p class="project-contact">Contact: <a href="mailto:sasha.coates-park@yale.edu">Sasha</a></p>
    <p class="project-tags">Keywords: Metastasis, Premetastatic Niche, Tumor Microenvironment, Myeloid Cells </p>
  </div>
</article>

    <!-- RNA Sequencing -->
   <article class="project">
  <div class="project-media">
    <figure class="research-figure">
  <img src="{{ '/assets/eduardoimage.png' | relative_url }}" 
       alt="RNA Sequencing Data" 
       class="research-image">
  <figcaption>
    UMAP visualization of single-cell transcriptomic data generated in-house. Each point represents an individual cell, and cells are grouped according to transcriptional similarity. Distinct colors indicate different cell clusters.
  </figcaption>
</figure>
  </div>
  <div class="project-body">
    <h2 class="project-title"><strong>Gene Expression in Human Cancers</strong></h2>
    <p class="project-summary">We use RNA sequencing data from published human studies to connect our research directly to what is happening in patients. By analyzing these datasets, we can see which genes are active or inactive in tumors and the surrounding tissues, and how these patterns differ between cancers that spread and those that remain localized. This approach highlights the cells and signals that may be most important for metastasis, while also allowing us to compare our experimental findings with human data.</p>
    <p class="project-contact">Contact: <a href="mailto:eduardo.menotisilva@yale.edu">Eduardo</a></p>
    <p class="project-tags">Keywords: RNA Sequencing, Human Datasets, Metastasis, Cellular Pathways, Translational Research</p>
  </div>
</article>

    <!-- Duplicate <article class="project">…</article> blocks for more projects -->

  </div>
