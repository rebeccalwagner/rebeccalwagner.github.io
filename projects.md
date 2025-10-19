---
layout: page
title: Projects
permalink: /projects/
---

{% assign sorted = site.projects | sort: "year" | reverse %}
{% for project in sorted %}
<div style="display: flex; align-items: center; margin-bottom: 30px;">

  {% if project.image %}
  <div style="flex: 0 0 180px; margin-right: 20px;">
    <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" style="width: 100%; border-radius: 8px;">
  </div>
  {% endif %}

  <div style="flex: 1;">
    <h3 style="margin-top: 0;">{{ project.title }} ({{ project.year }})</h3>
    <p>{{ project.description }}</p>
    {% if project.repo %}
    <a href="{{ project.repo }}" target="_blank" style="color:#0A66C2; text-decoration:none; font-weight:bold;">🔗 View on GitHub</a>
    {% endif %}
  </div>

</div>
<hr>
{% endfor %}