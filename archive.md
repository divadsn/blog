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
    {% capture month %}{{ post.date | date: '%m%Y' }}{% endcapture %}
    {% capture newmonth %}{{ post.next.date | date: '%m%Y' }}{% endcapture %}
    {% if month != newmonth %}
      {% if forloop.index != 1 %}</ul>{% endif %}
      <h3 class="subheader">{{ post.date | date: '%B %Y' }}</h3>
      <ul>
    {% endif %}
    <li><span class="time">{{ post.date | date: "%Y.%m.%d" }}</span> - <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% if !post.next %}</ul>{% endif %}
  {% endfor %}
</section>
