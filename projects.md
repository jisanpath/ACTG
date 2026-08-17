---
layout: default
title: Projects
description: Current and completed research projects
---

<div class="page-heading">
  <p class="eyebrow">RESEARCH PORTFOLIO</p>
  <h1>Projects</h1>
  <p>Track active studies, completed work, project leads, milestones, and target dates.</p>
</div>

<div class="project-grid">
{% for project in site.projects %}
  {% include project-card.html project=project %}
{% endfor %}
</div>
