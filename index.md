---
---

# Welcome to my website!

I'm a postdoctoral researcher interested in all things pangenomes. My previous work focused on developing computational tools to explore pangenome diversity and evolution in bacteria. Now I've switched to fungal pangenomes, where I'm working on tools to model pangenome evolution and identify hypermutation.

I'm currently at the University of Neuchâtel (Switzerland) at the [Laboratory of Evolutionary Genetics](https://www.unine.ch/lab-evol-gen/). Previously I was in the [Pathogen Informatics and Modelling group](https://bacpop.org) at EMBL-EBI (UK), and before that the [MRC Centre for Infectious Disease Analysis](https://www.imperial.ac.uk/mrc-global-infectious-disease-analysis) (UK).

{% include section.html %}

## Highlights

{% capture text %}

My research focus is development of bioinformatics tools to study pangenome diversity in a range of organisms. This ranges from pangenome-graph approaches to improve genome annotation and read alignment, to statistical methods for studying pangenome evolution.

{%
  include button.html
  link="publications"
  text="See my publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research_thumbnail.png"
  link="publications"
  title="My Publications"
  text=text
%}

{% capture text %}

My research interests revolve around studying pangenome diversity and evolution across the tree of life. Previously I focused on bacteria, and now I work on fungi.

{%
  include button.html
  link="projects"
  text="Browse my projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects_thumbnail.png"
  link="projects"
  title="My Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

I've written a number of tools that might be helpful for your bioinformatics analysis, spanning genome annotation and pangenome evolution study, to experimental evolution analysis and simulating eukaryotic pangenomes.

{%
  include button.html
  link="tools"
  text="My Tools"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/ggCaller_logo_new.png"
  link="tools"
  title="Browse my Tools"
  text=text
%}
