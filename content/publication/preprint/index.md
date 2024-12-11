---
title: "A novel inversion algorithm for weak lensing using quasi-conformal geometry"
authors:
- admin
date: "2022-06-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: One of the challenges in weak gravitational lensing by galaxies and clusters is to infer the projected mass density distribution from the observable image ellipticities, which is known as inversion problem. In this thesis we derive a new inversion algorithm for weak gravitational lensing to reconstruct the deflection field out of the reduced shear, which is in principle observable from the image ellipticities. We propose both an algorithm for the planar case, i.e. for fields for which the flat sky approximation can be assumed, and an algorithm for the general (curved) case, i.e. for fields, where the curvature cannot be neglected and the flat-sky approximation loses its validity. Using a complex formalism we show that for the planar case the lens mapping is a quasi-conformal mapping with Beltrami coefficient given by the negative of the reduced shear. Our proposed algorithm then computes this quasi-conformal mapping with
a finite element approach via a reduction to two elliptic PDEs. By introducing notions from quasi-conformal geometry like the Beltrami differential we generalize our inversion algorithm
to curved fields by trying to describe the lens mapping as quasi-conformal mapping between appropriate Riemann surfaces. The lens mapping can then be computed with methods from
computational quasi-conformal geometry. To the best of our knowledge, this is the first work which combines methods from quasi-conformal geometry with weak lensing in order to construct
new inversion algorithms. We implemented and tested our proposed algorithm for planar fields with different source and lens configurations and compared it to the well-known KS 93 algorithm
and its extension to the non-linear regime. However, the implementation of the algorithm for curved fields could not be done and will be the subject of further work.

# Summary. An optional shortened abstract.
summary: A novel inversion algorithm for weak lensing using quasi-conformal geometry

tags:
- Computational Astrophysics | Weak Gravitational Lensing

featured: true

# links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

links:
- name: Custom Link
  url: uploads/Bachelor Thesis Physics Jan Jakob.pdf
url_pdf: 
  url: uploads/Bachelor Thesis Physics Jan Jakob.pdf
url_code: 'https://github.com/JanJakob1'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
