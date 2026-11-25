---
layout: profile
title: "CV"
seo_title: "CV | Runqiu Hu (胡闰秋)"
description: "Education and technical skills of Runqiu Hu (胡闰秋), with a list of research publications."
permalink: /cv/
redirect_from:
  - /resume
---

## Education
* Ph.D. in Traffic Engineering, The University of Hong Kong (defense completed on October 21, 2026; degree conferral pending)
* M.S. in Computer Technology, Southeast University (China), 2021
* B.S. in Information Security, Nanjing University of Posts and Telecommunications, 2018

## Methods and tools

* **Optimization and AI** — Mixed-integer linear programming, multiobjective optimization, constraint programming, and answer set programming
* **Programming** — Python, C++, and Java
* **Software** — Gurobi, IBM CPLEX, MiniZinc, and Neo4j

## Publications

<ul class="cv-publications">
{% for post in site.publications reversed %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></li>
{% endfor %}
</ul>
