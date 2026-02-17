---
title: "Operator Learning Using Random Features for Phase-Field Tumor Models"
authors:
- admin
date: "2025-08-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['Preprint']

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: In mathematical oncology tumor evolution can be described by phase-field equations that model the spatio-temporal dynamics of cell populations together with various biophysical mechanisms. Recent surveys outline multiple families of such models, ranging from the prototypical Cahn-Hilliard equation to multiphase formulations incorporating nonlocal cell adhesion, stochastic fluctuations, and mixed-dimensional couplings to vascular networks. All these partial differential equation systems are highly nonlinear, high-dimensional, and computationally demanding to solve with classical numerical schemes, motivating the development of efficient surrogate models. Supervised operator learning has emerged as a promising data-driven framework for approximating solution operators between infinite-dimensional function spaces. Among theses approaches, the random feature method for operator learning provides a well-balanced approach, combining scalability with rigorous theoretical guarantees. It frames training as a convex quadratic optimization problem, admits convergence and complexity bounds, and can be interpreted as a low-rank approximation of operator-valued kernel ridge regression with close connections to Gaussian process regression. Within this framework, we construct random-features for the Cahn-Hilliard equation as the prototypical model for tumor growth, demonstrating accurate prediction of its solution operator and proving convergence of the method in this setting. Building on these results, we try to extend the framework to the four-species phase-field tumor growth model. The random feature method has seen limited application to partial differential equations, with only a few isolated examples in the literature, such as the Burgers equation or Darcy flow. Our work provides new insights into the method’s capabilities and extends its applicability to more complex partial differential equations. Our numerical experiments illustrate that random-feature operator learning provides a scalable, transferable, and discretization-invariant surrogate for the Cahn-Hilliard equation, offering a promising computational tool for mathematical oncology

# Summary. An optional shortened abstract.
summary: Operator Learning Using Random Features for Phase-Field Tumor Models

tags:
- Scientific Machine Learning | Operator Learning | Tumor Growth Modeling

featured: true

# links:
# - name: Custom Link
# url: 'http://arxiv.org/abs/2501.17157'
url_pdf: ''
url_code: 'https://github.com/JanJakob1/rfm-tumor-models'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

#links:
#- name: Custom Link
#  url: uploads/Bachelor Thesis Physics Jan Jakob.pdf
#url_pdf: '#'
#url: uploads/Bachelor Thesis Physics Jan Jakob.pdf
#url_code: 'https://github.com/JanJakob1'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work was carried out during my bachelor thesis in mathematics at the Engineering Mathematics and Computiung Lab (EMCL) at Heidelberg University under the supervision of [Prof. Vincent Heuveline](https://www.urz.uni-heidelberg.de/en/the-urz/organization/prof-dr-vincent-heuveline).

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
