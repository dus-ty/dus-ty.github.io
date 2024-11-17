---
layout: posts1
title: postpage
---

### Posts

I hope you find some of my posts insightful.

<p>
  {% for post in site.posts %}
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
      <br>
      <small>{{ post.description }}</small>
      <br>
  {% endfor %}
<p>