---
layout: page
title: Home
id: home
permalink: /
---

# this is the test grounds for the DeSciWorld library

{% for notes in site.notes %}
<h3>{{notes.title}}</h3>
{% end for %}

