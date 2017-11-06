---
title: Projects
layout: single
permalink: /projects/
author_profile: true
date: 2014-10-27 22:03:38.000000000 +00:00
type: pages
published: true
status: publish
categories: []
tags: []
header:
  overlay_image: /assets/images/desert.png
  caption: "Desert map design by ©Mapbox"
excerpt: ""
---

{% for item in site.projects %}
  <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
  <p>{{ item.description }}</p>
  <a href="{{ item.url }}" class="btn btn--danger">read more</a>

  <br/>
{% endfor %}

