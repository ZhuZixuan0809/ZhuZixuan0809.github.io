---
layout: archive
permalink: /activities/
title: "Activities and Contests"
author_profile: true
---

{% for post in site.activites reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
