---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

The papers listed below have alphabetical author order unless specified otherwise. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.fr/citations?hl=en&user=-BcHcowAAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
