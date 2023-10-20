---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

[Society for Learning Analytics Research (SoLAR)](https://www.youtube.com/watch?v=HwZyua3DvG4)

Find more information here

{% for post in site.talks reversed %}
  {% include archive-single-talk.md %}
{% endfor %}
