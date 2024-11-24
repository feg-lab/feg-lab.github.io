---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

We study natural populations using a combination of field-work, genomics, and common-garden experiments.  

# {% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{%
  include card.html
  image="images/space.jpg"
  # link="https://nasa.gov/"
  title="Molecular mechanisms of dwarfism and organ allometry in Atlantic salmon"
  # subtitle="A cool card"
  description="Species radiations can be driven by changes in body proportions (allometric changes), that is, natural selection acting on size and not in shape. Discovering the genetic and developmental basis of allometry has both fundamental importance for understanding the emergence of biological diversity, as well as in practical terms such as in understanding cancers. Only a few allometry mechanisms are known to explain adaptive differences in organ size within a vertebrate species. Salmon show a fascinating adaptation of organ allometry associated with a trade-off in life history strategies; dwarf landlocked ecotypes prioritize egg size over egg number, and in consequence have ovaries that are 50% smaller compared to their sea-migrating congeners. The decreased ovary size in dwarf salmon provides a unique model to study how allometry emerges within a single species and interplays with life history strategy. My work in collaboration with Prof Dylan Fraser at Concordia University is dissecting the genotype-phenotype-fitness map of ovary allometry from the molecular to the species level with an integrative approach combining cellular genomics, gene editing, and a powerful quantitative genetics framework."
  # tooltip="A cool tooltip"
  # tags="tag A, tag B, tag C"
  # repo="greenelab/lab-website-template"
  style="small"
%}



{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
