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

<span class='anchor' id='about-me'></span>

{% include_relative includes/about_me.md %}
{% include_relative includes/publications.md %}
{% include_relative includes/honors.md %}
{% include_relative includes/educations.md %}

# 📋 Academic Service
- **Peer Reviewer**
  - Scientific Data, Science of the Total Environment, Environmental Research, SCIENCE CHINA Earth Sciences, Scientific Reports, etc.
- **Conference Coordinator**
  - 3rd Congress of China Geodesy and Geophysics

# 🔈 Presentations
- **Oral Presentation**
  - *2023.08* The 4th Atmospheric Oxygen Workshop, Bowdoin College, United States
  - *2023.05* The 8th Youth Geoscience Forum, Wuhan, China
- **Poster Presentation**
  - *2023.05* The 8th Youth Geoscience Forum, Wuhan, China
  - *2020.08* Climatological, Meteorological and Environmental factors in the COVID-19 pandemic, online symposium, WMO

# 💻 Language and Skills
- **English**
  - spoken, read and written
  - TOEFL: 109/120
  - CET-6: 634/710
  - CET-4: 628/710
- **Chinese**
  - native speaker
- **Software**
  - Python, MATLAB, R, NCAR Command Language, FORTRAN, Photoshop, CorelDRAW, LaTeX, etc.
- **Models & Methods**
  - Machine Learning
  - WRF-Chem
  - High Performance Computing
  - STILT
  - Hysplit
