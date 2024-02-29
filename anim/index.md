---
layout: default
title: Ramble
nav_order: 1
description: "The ramble section of Rubberocket, where I ramble about stuff in blog form!"
permalink: /anim/
---

# Animations
### All the animations I've uploaded to this site in the past and present.

<ul>
  {% for post in site.categories.video %}
    {% if post.url %}
        <li><a href="{{post.url}}">{{post.title}}</a></li>
    {% endif %}
  {% endfor %}
</ul>