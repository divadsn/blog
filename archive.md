---
layout: default
sitemap:
  exclude: true
permalink: /archive/
title: Archived posts
---
<section id="archive">
  <h1 class="header">Archived posts</h1>
  {% for post in site.posts %}
    {% unless post.next %}
      <h3 class="subheader">{{ post.date | date: '%B %Y' }}</h3>
      <ul class="this">
    {% else %}
      {% capture year %}{{ post.date | date: '%m%Y' }}{% endcapture %}
      {% capture nyear %}{{ post.next.date | date: '%m%Y' }}{% endcapture %}
      {% if year != nyear %}
        </ul>
        <h3>{{ post.date | date: '%B %Y' }}</h3>
        <ul class="past">
      {% endif %}
    {% endunless %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  </ul>
</section>
