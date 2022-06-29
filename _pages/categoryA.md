---
layout: default
permalink: /categoryA
---
<h1>category A</h1>

<ul>
  {% for categoryA in notes.categories.categoryA %}
    <li>
      <a href="">{{categoryA.title}}</a>
      <p>{{categoryA.meta}}</p>
    <li>
  {% endfor %}
<ul>
