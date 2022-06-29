---
layout: page
title: Home
id: home
permalink: /
---
<body>
<h1>this is the test grounds for the DeSciWorld library</h1>

{% for notes in site.notes %}
  <h3>{{notes.title}}</h3>
{% endfor %}

</body>
