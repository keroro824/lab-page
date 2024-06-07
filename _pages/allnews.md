---
title: "News"
layout: textlay
excerpt: "InfiniAI Lab at CMU."
sitemap: false
permalink: /lab-page/allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
