---
layout: news
title: Newsletters
permalink: /news/
---

{% for newsletter in site.news %}
  <h2>
    <a href="{{site.url}}{{ newsletter.url }}">
      {{ newsletter.name }}
    </a>
  </h2>
{% endfor %}
