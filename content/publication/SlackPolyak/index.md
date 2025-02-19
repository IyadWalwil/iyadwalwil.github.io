---
title: "Cutting some slack for SGD with adaptive Polyak stepsizes (preprint)"

authors:
  - Robert M Gower
  - Mathieu Blondel
  - admin
  - Fabian Pedregosa

# Author notes (optional)
# author_notes:
#   - 'Equal contribution. Work done during an internship at Sony AI'
#   - 'Equal contribution'
#   - 
#   -
#   - 
  
date: "2022-02-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

abstract: Tuning the step size of stochastic gradient descent is tedious and error prone. This has motivated the development of methods that automatically adapt the step size using readily available information. In this paper, we consider the family of SPS (Stochastic gradient with a Polyak Stepsize) adaptive methods. These are methods that make use of gradient and loss value at the sampled points to adaptively adjust the step size. We first show that SPS and its recent variants can all be seen as extensions of the Passive-Aggressive methods applied to nonlinear problems. We use this insight to develop new variants of the SPS method that are better suited to nonlinear models. Our new variants are based on introducing a slack variable into the interpolation equations. This single slack variable tracks the loss function across iterations and is used in setting a stable step size. We provide extensive numerical results supporting our new methods and a convergence theory.

# Summary. An optional shortened abstract.
summary: 

# tags:
# - Source Themes
# featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/pdf/2202.12328.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
