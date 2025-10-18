---
layout: default # or a specific layout for index pages
title: Blog Posts
permalink: /blog/
---

<h1>{{ page.title }}</h1>

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
      </h3>
      <p class="post-meta">
        <time datetime="{{ post.date | date_to_xmlschema }}">
          {{ post.date | date: "%b %-d, %Y" }}
        </time>
      </p>
      {{ post.content | strip_html | truncatewords: 50 }}
      <p>
        <a href="{{ post.url | relative_url }}">Read more &rarr;</a>
      </p>
      <hr>
    </li>
  {% endfor %}
</ul>