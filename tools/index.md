---
title: Tools
nav:
  order: 4
  tooltip: Software
---

# {% include icon.html icon="fa-solid fa-wrench" %}Tools

GitHub links to open-source software and analysis tools, developed as part of my research in pangenomics and machine learning to study microbial epidemiology and evolution.

{% include tags.html tags="python, rust, r, c++, snakemake, genomics, pangenomics, simulation, machine learning" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="tools" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="tools" filter="!group" style="small" %}
