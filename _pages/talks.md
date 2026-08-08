---
layout: single
title: "Research Activities"
permalink: /research-activities/
author_profile: false
---

<div class="publications-page research-activities-page">
  {% for section in site.data.research_activities.sections %}
    <section class="research-activities-page__section" aria-labelledby="{{ section.id }}-title">
      <h2 id="{{ section.id }}-title">{{ section.title }}</h2>
      <ol class="publication-list">
        {% for activity in section.items %}
          {% include research-activity-item.html activity=activity %}
        {% endfor %}
      </ol>
    </section>
  {% endfor %}
</div>
