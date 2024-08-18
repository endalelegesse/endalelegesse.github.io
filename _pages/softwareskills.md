---
layout: archive
title: "Software Skills"
permalink: /softwareskills/
author_profile: true
---

{% if site.author.googlescholar %}

{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}