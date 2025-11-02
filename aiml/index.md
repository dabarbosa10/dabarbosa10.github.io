---
layout: default
title: "AI/ML Topics"
permalink: /aiml/
---

# AI/ML Topics

Below are posts and pages labeled **aiml**.

## Posts
<ul>
  {% assign posts = site.posts | where_exp: "p", "p.categories contains 'aiml'" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%Y-%m-%d" }})</small></li>
  {% endfor %}
</ul>

## Topic Pages
<ul>
  {% for page in site.pages %}
    {% if page.categories and page.categories contains "aiml" and page.url != "/aiml/" %}
      <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
