---
layout: page
title: gastronomy
permalink: /gastronomy/
nav: false
description: A trinational table — Switzerland · France · Italy.
_styles: >
  .atlas-epigraph {
    border-left: 3px solid var(--global-divider-color);
    padding: 0.1rem 0 0.1rem 1.2rem;
    margin: 1.5rem 0 2rem;
    font-style: italic;
    color: var(--global-text-color-light, var(--global-text-color));
  }
  .atlas-epigraph cite {
    display: block;
    font-style: normal;
    font-size: 0.85rem;
    opacity: 0.7;
    margin-top: 0.4rem;
    letter-spacing: 0.02em;
  }

  .atlas-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1rem;
    margin: 1.4rem 0 2.4rem;
  }
  .atlas-card {
    position: relative;
    display: flex;
    flex-direction: column;
    padding: 1.4rem 1.6rem 1.5rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    background: var(--global-card-bg-color);
    color: var(--global-text-color);
    text-decoration: none !important;
    transition: border-color 0.18s ease, transform 0.18s ease, box-shadow 0.18s ease;
  }
  .atlas-card:hover {
    border-color: var(--global-theme-color);
    transform: translateY(-2px);
    box-shadow: 0 6px 22px rgba(0, 0, 0, 0.07);
    color: var(--global-text-color);
  }
  html[data-theme="dark"] .atlas-card:hover {
    box-shadow: 0 6px 22px rgba(0, 0, 0, 0.35);
  }

  .atlas-card .atlas-num {
    display: block;
    font-family: Georgia, "Times New Roman", serif;
    font-size: 0.78rem;
    color: var(--global-theme-color);
    letter-spacing: 0.24em;
    margin-bottom: 0.2rem;
  }
  .atlas-card .atlas-title {
    display: block;
    font-size: 1.6rem;
    font-weight: 500;
    font-family: Georgia, "Times New Roman", serif;
    letter-spacing: -0.01em;
    line-height: 1.15;
    margin-bottom: 0.5rem;
    color: var(--global-text-color);
  }
  .atlas-card .atlas-meta {
    display: block;
    font-size: 0.72rem;
    color: var(--global-text-color-light, var(--global-text-color));
    font-family: "JetBrains Mono", "SF Mono", Menlo, monospace;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    opacity: 0.75;
    margin-bottom: 0.65rem;
  }
  .atlas-card .atlas-desc {
    display: block;
    font-size: 0.92rem;
    line-height: 1.5;
    color: var(--global-text-color);
    opacity: 0.85;
    flex: 1;
  }
  .atlas-card .atlas-arrow {
    display: block;
    margin-top: 0.85rem;
    font-size: 0.72rem;
    font-family: "JetBrains Mono", "SF Mono", Menlo, monospace;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--global-theme-color);
  }
  .atlas-card .atlas-arrow::after {
    content: " →";
    transition: margin-left 0.18s ease;
    display: inline-block;
  }
  .atlas-card:hover .atlas-arrow::after { margin-left: 4px; }

  .atlas-card.preparing {
    opacity: 0.58;
    cursor: not-allowed;
    pointer-events: none;
  }
  .atlas-card.preparing .atlas-arrow { color: var(--global-text-color-light, #999); }
  .atlas-card.preparing .atlas-arrow::after { content: " (in preparation)"; }

  .atlas-foot {
    border-top: 1px solid var(--global-divider-color);
    padding-top: 1.2rem;
    margin-top: 2rem;
    font-size: 0.88rem;
    color: var(--global-text-color);
    opacity: 0.78;
  }

  @media (max-width: 640px) {
    .atlas-grid { grid-template-columns: 1fr; gap: 0.85rem; }
    .atlas-card { padding: 1.2rem 1.3rem 1.3rem; }
    .atlas-card .atlas-title { font-size: 1.4rem; }
  }
---

<div class="atlas-epigraph">
  Tell me what you eat, and I shall tell you what you are.
  <cite>— Jean Anthelme Brillat-Savarin, <em>La Physiologie du Goût</em> (1825)</cite>
</div>

Living near CERN places one at the confluence of three formidable culinary traditions: Switzerland's Alpine dairy heritage to the north and east, France's gastronomic patrimony to the west, and Northern Italy's *cucina* across the southern passes. Within a 200-kilometre radius, one can taste the cheeses of Gruyère, the *charcuterie* of Lyon, the *prosciutti* of Parma, and the wines of the Valais — distinct yet historically interwoven.

These pages collect what I have read, tasted, and noted during my stay at CERN, with references to AOP/DOP/IGP designations and pairings drawn from local tradition. They are intended as a personal field guide rather than a comprehensive treatise.

## The four chapters

<div class="atlas-grid">

  <a class="atlas-card preparing" href="#">
    <span class="atlas-num">I — VIN</span>
    <span class="atlas-title">Wine</span>
    <span class="atlas-meta">in preparation</span>
    <span class="atlas-desc">From the Chasselas of Lavaux to the Nebbiolo of Piedmont — domaine visits, indigenous grape varieties (Petite Arvine, Cornalin, Mondeuse, Savagnin, Nebbiolo, Vernatsch), and pairings with the dishes catalogued in the chapters below.</span>
    <span class="atlas-arrow">enter</span>
  </a>

  <a class="atlas-card" href="{{ '/assets/html/cheese-atlas.html' | relative_url }}">
    <span class="atlas-num">II — FROMAGE</span>
    <span class="atlas-title">Cheese</span>
    <span class="atlas-meta">32 cheeses · 25 AOP/DOP</span>
    <span class="atlas-desc">Gruyère, Vacherin Mont-d'Or, Beaufort, Comté, Bleu de Gex, Parmigiano Reggiano, Castelmagno, Robiola di Roccaverano… organised by region (Switzerland, Savoie–Jura, Northern Italy), milk type, and family.</span>
    <span class="atlas-arrow">enter</span>
  </a>

  <a class="atlas-card" href="{{ '/assets/html/charcuterie-atlas.html' | relative_url }}">
    <span class="atlas-num">III — CHARCUTERIE</span>
    <span class="atlas-title">Charcuterie</span>
    <span class="atlas-meta">30 items · 20 AOP/DOP/IGP</span>
    <span class="atlas-desc">Longeole de Genève, Saucisson vaudois, Bündnerfleisch, Saucisse de Morteau, Prosciutto di Parma, Bresaola della Valtellina, Lardo d'Arnad — preserved meats from the three borders.</span>
    <span class="atlas-arrow">enter</span>
  </a>

  <a class="atlas-card" href="{{ '/assets/html/meat-cuts-atlas.html' | relative_url }}">
    <span class="atlas-num">IV — BOUCHERIE</span>
    <span class="atlas-title">Meat Cuts</span>
    <span class="atlas-meta">52 cuts · 6 animals</span>
    <span class="atlas-desc">French cuts of bœuf, veau, porc, agneau, volaille, and gibier, with cross-references to American and Italian terminologies, suggested cooking methods, and wine pairings. Includes simplified diagrams for beef and pork.</span>
    <span class="atlas-arrow">enter</span>
  </a>

</div>

<div class="atlas-foot">
  Each atlas opens in a self-contained page with its own filtering interface; clicking any item brings up a detail view with tasting notes, pairings, and historical background. URLs are shareable (each item has its own hash fragment), and the pages work on both desktop and mobile.
</div>
