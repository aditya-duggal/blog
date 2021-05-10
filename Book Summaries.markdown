---
layout: page
title: Book Summaries
permalink: /Book Summaries/
---

This is where I'll try and keep an updated list of interesting book summaries.

{% for post in site.posts %}

<li> <a href= "{{post.url}}"> {{post.title}} </a> </li>

{% endfor %}

{{ post.date | date: "%-d %B %Y" }}