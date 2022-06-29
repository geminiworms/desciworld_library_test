---
layout: page
title: Home
id: home
permalink: /
---

<h1>this is the test grounds for the DeSciWorld library</h1>

<div class="notes">
  {% for post in site.notes %}
   <div class="post">
    <h1 class="post-title">
      <a href="{{ site.baseurl }}{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>
    {% if post.tags %} | 
    {% for tag in post.tags %}
    <a href="{{ site.baseurl }}{{ site.tag_page }}#{{ tag | slugify }}" class="post-tag">{{ tag }}</a>
    {% endfor %}
    {% endif %}
  </div>
  {% endfor %}
</div>
