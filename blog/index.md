---
title: Students
nav:
  order: 4
  tooltip: Lab Member
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Lab Member

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
{% for student in site.data.students %}
<div class="student-card" style="margin-bottom: 2rem;">
  <img src="{{ '/assets/img/students/' | append: student.photo | relative_url }}" 
       alt="{{ student.name }}" width="160" style="border-radius: 8px; float: left; margin-right: 20px;">
  
  <h3 style="margin-top: 0;">{{ student.name }}</h3>
  <p>
    <strong>{{ student.role }}</strong> ({{ student.years }})<br>
    Research: <em>{{ student.topic }}</em><br>
    Email: <a href="mailto:{{ student.email }}">{{ student.email }}</a>
    {% if student.website %} · <a href="{{ student.website }}">Website</a>{% endif %}
    {% if student.scholar %} · <a href="{{ student.scholar }}">Google Scholar</a>{% endif %}
  </p>
  <div style="clear: both;"></div>
</div>
{% endfor %}
