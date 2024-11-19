---
layout: default
title: "Home"
description: "A space to share my tech projects, cybersecurity learnings, and ideas."
permalink: /
---  


I wanted a space to post the different projects I hope to start in the coming year. My goal is to keep it simple—no ads, no distractions, just the ideas I’m working on (no matter how uninteresting they might be). Simple was the plan...right after the hours of setup and fine-tuning to get things to this point.

Enjoy!  
<br><br>
<h3>Recent Posts</h3>  

<ul>
  {% for post in site.posts limit:3 %}  
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
      <br>
      <small>{{ post.description }}</small>
      <br><br>
  {% endfor %}
</ul>