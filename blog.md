---
layout: page
title: My Blog
permalink: /blog/
---

{% for post in site.posts %}
<a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
