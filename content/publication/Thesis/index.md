---
title: "Expected smoothness for stochastic variance-reduced methods and sketch-and-project methods for structured linear systems (PhD thesis)"
authors:
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution. Work done during an internship at Sony AI'
#   - 'Equal contribution'
#   - 
#   -
#   - 
  
date: "2021-12-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Télécom Paris, Institut Polytechnique de Paris"
# publication_short: ""

abstract: 'The considerable increase in the number of data and features complicates the learning phase requiring the minimization of a loss function. Stochastic gradient descent (SGD) and variance reduction variants (SAGA, SVRG, MISO) are widely used to solve this problem. In practice, these methods are accelerated by computing these stochastic gradients on a "mini-batch": a small group of samples randomly drawn.Indeed, recent technological improvements allowing the parallelization of these calculations have generalized the use of mini-batches.In this thesis, we are interested in the study of variants of stochastic gradient algorithms with reduced variance by trying to find the optimal hyperparameters: step and mini-batch size. Our study allows us to give convergence results interpolating between stochastic methods drawing a single sample per iteration and the so-called "full-batch" gradient descent using all samples at each iteration. Our analysis is based on the expected smoothness constant which allows to capture the regularity of the random function whose gradient is calculated.We study another class of optimization algorithms: the "sketch-and-project" methods. These methods can also be applied as soon as the learning problem boils down to solving a linear system. This is the case of ridge regression. We analyze here variants of this method that use different strategies of momentum and acceleration. These methods also depend on the sketching strategy used to compress the information of the system to be solved at each iteration. Finally, we show that these methods can also be extended to numerical analysis problems. Indeed, the extension of sketch-and-project methods to Alternating-Direction Implicit (ADI) methods allows to apply them to large-scale problems, when the so-called "direct" solvers are too slow.'

# Summary. An optional shortened abstract.
summary: 

# tags:
# - Source Themes
# featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://theses.hal.science/tel-03590678v1/document'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
