---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

The Microbial Biotechnology Division is currently involved in several research projects, including enzyme development and the discovery of new therapeutic compounds. In addition, we are developing probiotic strains with potential benefits for human health.

#{% include tags.html tags="publication, resource, website" %}

#{% include search-info.html %}

#{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
