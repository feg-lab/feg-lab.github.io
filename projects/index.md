---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

We study natural populations using a combination of field-work, genomics, and common-garden experiments. 

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{%
  include feature.html
  image="images/group-photo.jpg"
  title="eQTL"
  text="Our team is made up of people all around the globe"
  flip=true
%}


{% include list.html component="card" data="projects" filter="!group" style="small" %}
