---
layout: archive
title: "Workshops"
permalink: /workshops/
author_profile: true
---

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}