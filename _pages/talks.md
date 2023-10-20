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

In this webinar, Elizabeth Cloude disscusses the state-of-the-art research findings, theoretical, methodological, and analytical approaches, and their challenges. It prsents an interdisciplinary perspective that merges an affect framework with complex adaptive systems theory. New research tools and directions are examined, describing how the design of educational technologies can positively influence affect, engagement, knowledge acquisition, and learning outcomes. Finally, opportunities and challenges regarding affect learning analytics are also discussed.

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
