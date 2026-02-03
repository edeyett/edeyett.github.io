---
layout: default
title: Home
permalink: /
---
<section class="hero">
  <div class="container hero-center">
    <img class="hero-logo-large" src="{{ '/branding/logo.png' | relative_url }}" alt="MicroMosaic logo">
    <h2>Elizabeth Deyett, PhD</h2>
    <p class="hero-subline"><strong>Systems · Strategy · Stories</strong></p>
    <p class="hero-pitch"><strong>From microbial bioinformatics to data strategy to science communication, MicroMosaic supports organizations with focused, independent expertise—grounded in rigor, clarity, and scientific integrity.</strong></p>
    <div>
      <span class="badge">Microbial bioinformatics</span>
      <span class="badge">Data strategy &amp; management</span>
      <span class="badge">Science communication</span>
    </div>
    <div class="cta-row">
      <a class="cta" href="https://calendly.com/edeyett-proton/30min">Start a conversation</a>
      <a class="cta secondary" href="{{ '/case-studies/' | relative_url }}">See case studies</a>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <h2>About the practice</h2>
    <div class="about-highlight golden" style="display:grid;grid-template-columns:minmax(280px,1.3fr) minmax(200px,0.7fr);gap:1.5rem;align-items:center;">
      <div>
        <p>I’m a microbial ecologist with a PhD in Genetics, Genomics & Bioinformatics, rooted in environmental microbiology. Field work taught me to see ecosystems as living systems, not just sample sites. Graduate research trained me to read genomes with precision. Collaboration taught me how to listen across disciplines, incentives, and ways of thinking.</p>
        <p>Industry work made something else clear: good science doesn’t fail because of lack of effort or expertise. It fails when analysis, data systems, culture, and communication drift into separate lanes — eroding biological meaning, trust, and ultimately, decision-making.</p>
        <p>The practice unites microbial bioinformatics, data strategy and governance, and science communication — including writing, editorial work, and talks that help organizations think together — so scientific work remains rigorous, durable, and meaningful as it moves from data to decision.</p>
        <p>This is where I work best: at the intersection of microbes, computation, and human systems — helping science scale without losing integrity, meaning, or the people doing the work.</p>
      </div>
      <div style="display:flex;justify-content:flex-end;align-items:center;">
        <img src="{{ '/branding/portraits/3.png' | relative_url }}" alt="Elizabeth portrait" style="max-width:260px;">
      </div>
    </div>
    <div class="pillars-grid" style="margin-top:2rem;">
      <article class="card pop-teal">
        <h3>What guides the work</h3>
        <ul>
          <li>Rigor first — methods, assumptions, and limits made explicit</li>
          <li>Clear communication without oversimplifying or talking down</li>
          <li>Ecological respect for microbes and the systems they shape</li>
          <li>Design and storytelling that make science hard to ignore</li>
          <li>Microbe-first wonder paired with serious scientific standards</li>
        </ul>
      </article>
      <article class="card pop-gold">
        <h3>How we work together</h3>
        <ul>
          <li>Flexible engagement: embedded teammate or independent lead</li>
          <li>Clear scoping, timelines, and a written statement of work</li>
          <li>Direct collaboration with scientists and stakeholders when embedded</li>
          <li>Autonomy when needed—share inputs, receive clean outputs</li>
          <li>Durable handoffs with documentation and decision notes</li>
        </ul>
      </article>
      <article class="card pop-crimson">
        <h3>Who benefits</h3>
        <ul>
          <li>Environmental biotech and climate-focused teams</li>
          <li>Microbial R&amp;D groups in industry or academia</li>
          <li>NGOs translating science for funders and communities</li>
          <li>Mission-driven startups building with microbial systems</li>
          <li>Journals, conferences, and science communication partners</li>
          <li>Graduate students, postdocs, and scientific communities</li>
        </ul>
      </article>
    </div>
  </div>
</section>

<section class="highlight-section">
  <div class="container">
    <h2>Selected services</h2>
    <div class="pillars-grid">
      <article class="card service-card pop-teal">
        <h3>Bioinformatics &amp; Analysis</h3>
        <ul>
          <li>Genome, metagenome, amplicon, and RNA-seq pipelines</li>
          <li>Comparative genomics and phylogenetics</li>
          <li>Interpretation sessions + visualization libraries + dashboards</li>
          <li>Exploratory vs production-grade pipeline design</li>
          <li>QC strategy, metadata support, and handoff docs</li>
        </ul>
      </article>
      <article class="card service-card pop-gold">
        <h3>Science Communication</h3>
        <ul>
          <li>Editorial support for manuscripts, journals, and feature stories</li>
          <li>Podcast strategy, interviews, and sponsored series</li>
          <li>Stakeholder briefs, decks, and narrative translation</li>
          <li>Workshops on data literacy and interpretation</li>
          <li>Science events, conference materials, and creative campaigns</li>
        </ul>
      </article>
      <article class="card service-card pop-crimson">
        <h3>Data Strategy &amp; Governance</h3>
        <ul>
          <li>Roadmapping for data governance and literacy</li>
          <li>LIMS/ELN evaluation, metadata schema, and standards</li>
          <li>Cloud architecture and cost-aware infrastructure</li>
          <li>AI readiness, tooling audits, and adoption playbooks</li>
          <li>Fractional leadership or advisory partnerships</li>
        </ul>
      </article>
    </div>
    <div class="cta-row" style="margin-top:2rem;">
      <a class="cta secondary" href="{{ '/services/' | relative_url }}">Explore all services</a>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <h2>Selected work</h2>
    <p class="lede">Infrastructure builds, culture change, and science storytelling—always microbiology-forward.</p>
    <div class="case-grid">
      {% assign featured_cases = site.case_studies | sort: 'title' %}
      {% for case in featured_cases %}
      <article class="card {% cycle 'pop-teal','pop-gold','pop-crimson' %}">
        <p class="case-tag">{{ case.context }}</p>
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
    <p>Bring your questions, constraints, and context. I’ll bring rigorous science, clear strategy, and communication that travels.</p>
    <div class="cta-row">
      <a class="cta" href="{{ '/contact/' | relative_url }}">Talk through your project</a>
      <a class="cta secondary" href="https://calendly.com/edeyett-proton/30min">Schedule a meeting</a>
    </div>
  </div>
</section>
