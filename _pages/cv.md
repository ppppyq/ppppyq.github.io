---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

- **Degree**, Your University, YYYY - Present
- **Degree**, Previous University, YYYY - YYYY

Research Experience
======

- **Research Assistant**, Lab / Group, YYYY - Present
  - Briefly describe your research direction, responsibilities, or main outcomes.

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

Awards and Honors
======

- Award name, YYYY

Skills
======

- Programming: Python, C/C++, JavaScript
- Tools: Git, Linux, LaTeX
