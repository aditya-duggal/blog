---
layout: page
title: Book Summaries
permalink: /Book Summaries/
---

This is where I'll try and keep an updated list of interesting book summaries.

{% for posts in site.posts}

<li> {{ post.date | date: %B %Y"}} <a href= "{{post.url}}">{{post.title}}</a> </li>

{% endfor %}
