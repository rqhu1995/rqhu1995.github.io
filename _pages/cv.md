---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* Ph.D in Traffic Engineering, The University of Hong Kong, 2026 (expected)
* M.S. in Computer Technology, Southest University (China), 2021
* B.S. in Information Security, Nanjing Univerisity of Posts and Telecommunications, 2018

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
