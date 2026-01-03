---
layout: default
title: Home
permalink: /
---
<section class="hero">
  <div class="hero-inner">
    <p class="badge">Microbiology · Data · Story</p>
    <h1>MicroMosaic helps organizations turn complex biological data into clear insight, credible decisions, and compelling scientific narratives.</h1>
    <p class="subhead">Deep microbiology expertise + enterprise data strategy + science communication that keeps rigor intact.</p>
    <a class="cta" href="{{ '/contact/' | relative_url }}">Start a conversation</a>
    <a class="cta secondary" href="{{ '/services/' | relative_url }}">Explore services</a>
  </div>
</section>

<section class="section">
  <div class="container">
    <h2>Integrated pillars, one partner</h2>
    <p class="lede">MicroMosaic is a hybrid scientific practice: part bioinformatics consultant, part data strategist, part science communicator.</p>
    <div class="pillars-grid">
      <article class="card">
        <h3>Data, Bioinformatics & Analysis</h3>
        <p>Genome-scale analysis across bacteria and fungi, metagenomics, amplicon, RNA-seq, and multi-omics interpretation complete with visual reports.</p>
        <p><strong>Outputs:</strong> Clean pipelines, annotated results, interpretive summaries, publication-ready figures.</p>
      </article>
      <article class="card">
        <h3>Science Communication & Translation</h3>
        <p>Research-grounded storytelling for stakeholders, funders, scientists, and the public. Reports, podcasts, blogs, workshops, and visual abstracts.</p>
        <p><strong>Outputs:</strong> Clear narratives, editorial support, audio strategy, data-to-story translation.</p>
      </article>
      <article class="card">
        <h3>Data Strategy, Governance & Leadership</h3>
        <p>Company-wide data architecture, governance, literacy, and AI-readiness that align business goals with scientific integrity.</p>
        <p><strong>Outputs:</strong> Governance frameworks, working groups, cloud/LIMS design, leadership-aligned roadmaps.</p>
      </article>
    </div>
  </div>
</section>

<section class="highlight-section">
  <div class="container">
    <h2>Who MicroMosaic serves</h2>
    <p>Microbiology-forward but not microbiology-exclusive.</p>
    <div class="pillars-grid">
      <div class="card">
        <h3>Environmental & Climate Biotech</h3>
        <p>Microbe-first R&D programs needing reproducible analysis plus strategic guidance before scaling.</p>
      </div>
      <div class="card">
        <h3>Agriculture & Soil Teams</h3>
        <p>Plant-microbe researchers, NGOs, and consortia translating complex datasets to partners and policymakers.</p>
      </div>
      <div class="card">
        <h3>Mission-Driven Organizations</h3>
        <p>Academic labs, nonprofits, and startups who need science communication, data governance, or fractional bioinformatics leadership.</p>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <h2>Recent case studies</h2>
    <p class="lede">Proof that rigor, infrastructure, and story can live together.</p>
    <div class="case-grid">
      {% assign featured_cases = site.case_studies | sort: 'title' %}
      {% for case in featured_cases %}
      <article class="card">
        <p class="case-tag">{{ case.services | join: ' · ' }}</p>
        <h3>{{ case.title }}</h3>
        <p>{{ case.summary }}</p>
        <a class="cta secondary" href="{{ case.url | relative_url }}">Read case study</a>
      </article>
      {% endfor %}
    </div>
  </div>
</section>

<section class="section">
  <div class="container contact-panel">
    <h2>Ready to co-design data, infrastructure, and story?</h2>
    <p>Bring your questions, constraints, and context. MicroMosaic brings rigorous science, clear strategy, and communication that travels.</p>
    <a class="cta" href="{{ '/contact/' | relative_url }}">Talk through your project</a>
  </div>
</section>
