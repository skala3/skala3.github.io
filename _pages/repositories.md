---
layout: page
permalink: /repositories/
title: Repositories
description: GitHub repositories and open source contributions.
nav: true
nav_order: 3
---

{% if site.data.repositories.github_repos %}
<div class="projects">
  <div class="grid">
    {% for repo in site.data.repositories.github_repos %}
      {% include repository/repo.html repository=repo %}
    {% endfor %}
  </div>
</div>
{% endif %}
