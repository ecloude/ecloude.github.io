---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

My ultimate research goal is to develop intelligent and adaptive learning technologies that enhance the accessibility, inclusivity, and overall quality of digital education, making the benefits of self-regulated learning (SRL) skills accessible to learners globally. Achieving this goal requires studying SRL comprehensively, as a process with four underlying components: cognition, affect, metacognition, and motivation (CAMM) during learning. Studying how CAMM processes unfold and give rise to SRL requires collecting fine-grained and continuous data streams that transpire during learning activities with learning software. 

Because of this, I have selected a curated list of my publications, which are organized by _two_ process-oriented approaches with diverse learning software: **Multimodal Learning Analytics** and **Mixed-multimodal Methods**. The first involves the majority of my completed (PhD) research, involving multimodal data streams (solely relying on quantitative CAMM measures). The second approach involves my active and future work, involving mixed-multimodal methods (merging quantitaive and qualitative CAMM measures). Much of the mixed-multimodal methods work is on-going and in data-collection and analysis phases of the research cycle.

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Multimodal Learning Analytics (MLA)
{% for post in site.publications %}
  {% if post.type == 'MLA' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Mixed-Multimodal Methods
{% for post in site.publications %}
  {% if post.type == 'mixed-methods' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
