---
layout: archive
title: "Awards and Honors"
permalink: /AwardsHonors/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

<img src="https://onedrive.live.com/embed?resid=9CDDD6D29488136D%211958&authkey=%21AENl1yvirdDtJVU&width=5794&height=3863" width="5794" height="3863" />