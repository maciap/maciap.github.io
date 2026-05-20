---
layout: page
permalink: /repositories/
title: new repositories
description: Recent research software.
nav: true
nav_order: 5
---

{% if site.data.repositories.github_users %}

## GitHub profile

{% for user in site.data.repositories.github_users %}
{% include repository/repo_user.liquid username=user %}
{% endfor %}

---

{% endif %}

{% if site.data.repositories.github_repos %}

## Recent repositories

{% for repo in site.data.repositories.github_repos %}
{% include repository/repo.liquid repository=repo %}
{% endfor %}

{% endif %}