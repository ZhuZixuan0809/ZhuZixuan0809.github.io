---
layout: archive
permalink: /activities/
title: "Activities and Contests"
author_profile: true
---

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
