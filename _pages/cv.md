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
* Ph.D. in Traffic Engineering, The University of Hong Kong (defense completed on October 21, 2026; degree conferral pending)
* M.S. in Computer Technology, Southeast University (China), 2021
* B.S. in Information Security, Nanjing University of Posts and Telecommunications, 2018

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
