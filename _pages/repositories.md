---
layout: page
permalink: /repositories/
title: repositories
description: Bioinformatics pipelines and tools developed by the Arsenault Lab.
nav: true
nav_order: 5
---

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="row">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>

{% endif %}
