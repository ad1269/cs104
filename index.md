---
layout: home
title: Home
nav_exclude: true
seo:
  type: Course
  name: CS104 Alabama A&M
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## About the Class

CS104 is an introductory class using the Python programming language, designed for students with no formal exposure to computer science or programming. The goal is to provide fundamentals that will prepare students to either take further computer science courses, or use computer science in their field of study.

## Course Materials
{% for module in site.modules %}
{{ module }}
{% endfor %}
