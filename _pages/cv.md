---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Profile
======

Yuqi Ping is a researcher at Harbin Institute of Technology (Shenzhen). Research interests include UAV systems, multimodal large language models, vision-language navigation, communication and control co-design, and low-altitude airspace intelligence.

Research Interests
======

- UAV systems and autonomous aerial networks
- Multimodal large language models
- Vision-language navigation
- Communication and control co-design
- UAV swarm localization, tracking, and trajectory planning
- Low-altitude airspace security

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks
======

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching
======

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
