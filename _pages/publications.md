---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="publications-page">
  <p class="publications-page__intro">
    You can also find my work on
    <a href="https://scholar.google.com/citations?user=eeS-QRwAAAAJ&amp;hl=en">Google Scholar</a>.
  </p>

  <section aria-labelledby="published-work-title">
    <h2 id="published-work-title" class="visually-hidden">Published work</h2>
    <ol class="publication-list">
      {% for paper in site.data.publications.peer_reviewed %}
        {% include publication-item.html paper=paper %}
      {% endfor %}
    </ol>
  </section>

  <section class="publications-page__section" aria-labelledby="preprints-title">
    <h2 id="preprints-title">Preprints</h2>
    <ol class="publication-list">
      {% for paper in site.data.publications.preprints %}
        {% include publication-item.html paper=paper %}
      {% endfor %}
    </ol>
  </section>
</div>
