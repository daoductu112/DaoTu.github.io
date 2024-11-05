---
layout: default
title: "Blog"
---
# Blog

Here are my blog posts:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
