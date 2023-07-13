---
title: "News"
layout: textlay
excerpt: "Security and Artificial Intelligence Lab at VinUniversity."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}

<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}
