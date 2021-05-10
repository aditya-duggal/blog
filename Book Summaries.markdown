---
layout: page
title: Book Summaries
permalink: /Book Summaries/
---

This is where I'll try and keep an updated list of interesting book summaries.

{% for post in site.posts %}

<li> {{ post.date | date: "%B %Y" }} <a href= "/blog/{{post.permalink}}"> {{post.title}} </a> </li>

{% endfor %}
