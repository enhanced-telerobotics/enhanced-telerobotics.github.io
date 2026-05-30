---
layout: page-fullwidth
title: "Research"
permalink: "/research/"
---

{% for category in site.data.research.categories %}
<section class="research-category">
  <h2>{{ category.title }}</h2>
  <div class="research-card-list">
    {% assign category_projects = site.data.research.projects | where_exp: "project", "project.categories contains category.id" %}
    {% for project in category_projects %}
      {% include research-card.html project=project %}
    {% endfor %}
  </div>
</section>
{% endfor %}
