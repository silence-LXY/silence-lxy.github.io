---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

{% include_relative includes/about_me.md %}
{% include_relative includes/publications.md %}
{% include_relative includes/presentations.md %}
{% include_relative includes/honors.md %}
{% include_relative includes/educations.md %}
{% include_relative includes/academic_service.md %}
{% include_relative includes/skills.md %}
