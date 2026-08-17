---
layout: default
title: Team
description: Research team members
---

<div class="page-heading">
  <p class="eyebrow">OUR PEOPLE</p>
  <h1>Research Team</h1>
  <p>Add researchers, students, technicians, collaborators, and supervisors here.</p>
</div>

<div class="people-grid">
{% for person in site.people %}
<a class="person-card" href="{{ person.url | relative_url }}">
  <div class="avatar">{{ person.initials }}</div>
  <div>
    <p class="eyebrow">{{ person.role }}</p>
    <h3>{{ person.name }}</h3>
    <p>{{ person.short_bio }}</p>
  </div>
</a>
{% endfor %}
</div>
