---
layout: page
title: Repositories
permalink: /repositories/
nav: true
nav_order: 5
---

## Repositories
{% assign repos = site.repositories | sort: "date" | reverse %}

<div class="projects">
  {% for repo in repos %}
    <div class="project-card">

      <h3>{{ repo.title }}</h3>

      {{ repo.content }}

      <p>
        {% if repo.github %}
          <a href="{{ repo.github }}" target="_blank">GitHub Repository</a>
        {% endif %}

        {% if repo.zenodo %}
          |
          <a href="{{ repo.zenodo }}" target="_blank">Zenodo Archive</a>
        {% endif %}
      </p>

    </div>
  {% endfor %}
</div>
