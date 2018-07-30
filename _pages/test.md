---
layout: post
title: "test"
cover: 5.png
permalink: test
---


{% for p in site.pages %}
  {{ p.path }}
{% endfor %}
