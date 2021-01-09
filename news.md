---
layout: news
title: Newsletters
permalink: /news/
---

{% for newsletter in site.news %}
  <h2>
    <a href="{{host}}{{port}}{{site.baseurl}}{{ newsletter.url }}">
      {{ newsletter.name }}
    </a>
  </h2>
{% endfor %}
