---
title: "News"
layout: textlay
excerpt: "GM2M at Edinburgh Napier University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
  *{{ article.date }}*  
  {{ article.headline | markdownify}}
{% endfor %}
