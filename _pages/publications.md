---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% for y in archive.years %}
  <h3 class="year">{{y}}</h3>
  {% publications -f papers -q @*[year={{y}}]* %}
{% endfor %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
