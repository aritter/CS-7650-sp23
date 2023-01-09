---
layout: home
title: CS 7650
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

Although this is an in-person course, we plan to stream lectures using Zoom.  The link is available [here](https://gatech.zoom.us/j/99252718114).

- Location: Instructional Center 211
- Time: MW 2:00 pm - 3:15 pm
- [Piazza](https://piazza.com/gatech/spring2023/cs7650/) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/482255) (homework assignments, submission and grading)
- [Tentative Course Schedule](https://docs.google.com/spreadsheets/d/1JivbsuLLw5a1Fm6mY1oL_7eb0jumnUzkTNYV1RXMb1w/edit?usp=sharing)

{% for module in site.modules %}
{{ module }}
{% endfor %}
