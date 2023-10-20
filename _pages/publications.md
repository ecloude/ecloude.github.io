---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Self-regulated Learning Processes

My ultimate research goal is to develop intelligent and adaptive learning technologies that enhance the accessibility, inclusivity, and overall quality of digital education, making the benefits of self-regulated learning (SRL) skills accessible to learners globally.

Achieving this goal requires studying SRL comprehensively, as a process with four underlying components: cognition, affect, metacognition, and motivation (CAMM) during learning. Studying how CAMM processes unfold and give rise to to SRL requires collecting fine-grained and continuous data streams that transpire during learning activities with learning software. Because of this, my publications are organized by two process-oriented approaches with different learning software. The first involves utilizing multimodal data streams (solely relying on quantitative CAMM measures), while the other harnesses the power of mixed-multimodal methods (merging quantitaive and qualitative CAMM measures).

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Multimodal Learning Analytics
{% for post in site.publications reversed %}
  {% if type == 'MLA' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

| Author          | Year   |  Title                                      |  Venue      | Hyperlink  | Learning Software |
| ----------------| -------| ------------------------------------------- | ------------|------------|-------------------| 
| [2020-07-03](#)    | 2020   | Description of the item in the list         |             |            |Game-based Learning|
| [Paper 2](#)    | 2019   | Description of the item in the list         |             |            |                   |
| [Paper 3](#)    | 2022   | Description of the item in the list         |             |            |                   |


## Mixed-Multimodal Methods
{% for post in site.publications reversed %}
  {% if type == 'mixed-methods' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

| Author          | Year   |  Title                                                       |  Venue      |   Hyperlink  |
| ----------------| -------| ------------------------------------------------------------ | ------------|  ------------|  
| [Paper 1](#)    | 2016   | Description of the item in the list                          |             |              |
| [Paper 2](#)    | 2019   | Description of the item in the list                          |             |              |
| [Paper 3](#)    | 2022   | Description of the item in the list                          |             |              |
