---
layout: page
title: Case Studies
lede: "Concrete examples of how rigorous analysis, strategy, and storytelling come together."
permalink: /case-studies/
---
<div class="case-grid">
  {% assign sorted_cases = site.case_studies | sort: 'title' %}
  {% for case in sorted_cases %}
  <article class="card">
    <p class="case-tag">{{ case.context }}</p>
    <h3><a href="{{ case.url | relative_url }}">{{ case.title }}</a></h3>
    <p>{{ case.summary }}</p>
    <p><strong>Pillars:</strong> {{ case.services | join: ', ' }}</p>
    <a class="cta secondary" href="{{ case.url | relative_url }}">Read more</a>
  </article>
  {% endfor %}
</div>
