---
layout: default
title: Animations
nav_order: 1
description: "The animation section of Rubberocket, where most of the animations of the site reside."
permalink: /anim/
---

# Animations
### All the animations I've uploaded to this site in the past and present.

<ul>
  {% for post in site.categories.anim %}
    {% if post.url %}
        <li><a href="{{post.url}}">{{post.title}}</a></li>
    {% endif %}
  {% endfor %}
</ul>