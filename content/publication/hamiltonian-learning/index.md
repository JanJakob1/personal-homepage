---
title: "Improved Hamiltonian Learning with Neural Differential Equations using Classical Shadows"
authors:
- admin
date: "2024-11-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The Hamiltonian Learning (HL) problem consists of the task of inferring the Hamiltonian of a many-body system given a set of state trajectories of that system. The problem is highly relevant for error mitigation, optimal quantum control, quantum simulation, and device certification. In [] T. Heightmann et al. introduced a novel approach to solving the HL problem on quantum many-body spin systems using neural differential equations (NODEs). Their proposed method combines an Ansatz Hamiltonian with NODEs to infer the quantum dynamics of a many-body system. The authors showcased the reliability and expressiveness of their method by solving several previously unsolved HL problems in one-dimensional spin-1/2 chains. However, the loss function used to train the parameters $\theta$ for both the Ansatz Hamiltonian and the neural network is calculated as the average negative log-likelihood of the probabilities |⟨b|ψθ(t)⟩|2 using Born’s rule for the bitstrings b in a subset of the given dataset corresponding to all bitstrings measured at the same timestamp and input state as the estimator ψθ(t). Despite several other challenges, the authors highlight that such a loss function relies on an accurate estimate
of the log-likelihood of a small number of Pauli strings. This could bias the loss function if the number of measurement bases is insufficient or measurements are noisy. At the same time, the authors note the possibility of using classical shadows introduced in [5] to eliminate these disadvantages. In this project, we will elaborate on this idea by modifying the loss function by tracking expectation values in time using classical shadows. We will do this by generating classical shadows for the evolved states |ψθ(t)⟩ and calculating a new loss function on that basis. We expect the method in [4] using our new loss function to have numerous advantages over using the old one. In particular, we expect that the two challenges mentioned in [4] can be resolved. The limited coverage of Pauli bases can be overcome using classical shadows, which enable more accurate reconstruction
of the probabilities |⟨b|ψθ(t)⟩|2 by aggregating data across different random measurement bases, while their randomized nature ensures uniform Hilbert space sampling and mitigates biases from restricted measurement bases. Also, classical shadow protocols are designed to be robust against certain types of noise [6]. For example, we could use error-mitigation techniques to correct systematic errors in our measurements [7]. To explore the benefits of the new loss function, we aim to implement the algorithm with our modified
loss function and benchmark it against the algorithm using the old loss function from.

# Summary. An optional shortened abstract.
summary: In this project we are going to improve the Hamiltonian Learning problem of a many-body system

tags:
- Quantum Information Theory

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

url_pdf: ''
#url: uploads/Bachelor Thesis Physics Jan Jakob.pdf

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

This work was driven by a seminar about geometeric quantization hold by Prof. Gabriele Benedetti.

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->