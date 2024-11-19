---
layout: posts1
title: "Posts"
description: "My posts about things I find interesting. Ranging from cybersecurity, security research, bug bounty findings, and things."
permalink: /postpage/
---  

### Posts

I hope you find my posts insightful.

<p>
  {% for post in site.posts %}
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
      <br>
      <small>{{ post.description }}</small>
      <br>
      <br>
  {% endfor %}
<p>