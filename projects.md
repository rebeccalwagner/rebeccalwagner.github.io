---
layout: page
title: Projects
permalink: /projects/
---

{% assign sorted = site.projects | sort: "year" | reverse %}
{% for project in sorted %}
### {{ project.title }} ({{ project.year }})
{{ project.description }}

[🔗 View on GitHub]({{ project.repo }})

{% endfor %}