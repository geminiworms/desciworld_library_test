---
layout: page
title: Home
id: home
permalink: /
---

<h1>this is the test grounds for the DeSciWorld library</h1>

{% for note in site.notes %}
  <h3>{{note.title}}</h3>
{% endfor %}

