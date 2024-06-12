---
layout: page
title: Notes
permalink: /notes/
description: "Hi there! I'm going to share the skills and knowledge I've picked up at university and through independent study here. I'm doing this for two reasons. First, my major isn't computer science or mathematics related, which often leads to questions about my abilities.  I hope that these notes can give a good first impression to people who are meeting me for the first time. I want to be a person who is professional in his field of research :). Second, there are so many great resources out there for beginners in most areas, including the one I'm discussing here. However, despite these wonderful teachers, there might be a lack of "classmates" for those who have to study majors by themselves. I hope that anyone who wants to learn more about the subjects will see me as a classmate who is also learning these courses. I've listed these materials as my own skill tree and included some references at the top of each topic. I really hope that these materials will be made available on this site for anyone who might find them useful. If you have any questions about the materials, please don't hesitate to send me an email."
nav: true
nav_order: 2
display_categories: [Math, Artificial Intelligence, Computer Science]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.notes | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.notes | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
