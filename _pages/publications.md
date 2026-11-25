---
layout: profile
title: "Publications"
seo_title: "Publications | Runqiu Hu (胡闰秋)"
description: "Publications by Runqiu Hu (胡闰秋) on transportation, shared mobility, and operations research."
permalink: /publications/
---

<p class="document-intro">Also available on <a href="{{ site.author.googlescholar }}">Google Scholar</a>.</p>

<div class="publication-list">
{% for post in site.publications reversed %}
  <article class="publication-item">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></h2>
    {{ post.content | markdownify }}
  </article>
{% endfor %}
</div>
