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
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/google_scholar_citations.json" %}
<span class='anchor' id='about-me'></span>

{% include_relative includes/intro.md %}

{% include_relative includes/news.md %}

# 📝 Publications 

<div class="year-badge">
    <b>2024 🐲</b>
</div>
{% include_relative publications/2024-11-15-SEAGULL.md %}
{% include_relative publications/2024-03-11-PromptIQA.md %}

<div class="year-badge">
    <b>2023 🐰</b>
</div>
{% include_relative publications/2023-07-26-HCLIQA.md %}

<div class="year-badge">
    <b>2022 🐯</b>
</div>
{% include_relative publications/2023-03-02-TeacherIQA.md %}

>  🌟 The full publication list is on <a href="https://scholar.google.com/citations?user=ozllxV4AAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-white?style=flat&logo=Google%20Scholar" style="max-width 100%; height: auto;"></a>.

{% include_relative includes/projects.md %}

{% include_relative includes/honors.md %}

{% include_relative includes/edu.md %}


