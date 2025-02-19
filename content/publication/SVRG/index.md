---
title: 'Towards closing the gap between the theory and practice of SVRG (NeurIPS 2019)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Othmane Sebbouh
  - admin
  - Samy Jelassi
  - Francis Bach
  - Robert M. Gower

# Author notes (optional)
# author_notes:
#   - 'Work done during an internship at Sony AI'
#   - 'Main supervisor'
#   - 
#   - 

date: '2019-12-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS 2019*
publication_short: In *NeurIPS 2019*

abstract: Among the very first variance reduced stochastic methods for solving the empirical risk minimization problem was the SVRG method (Johnson & Zhang 2013). SVRG is an inner-outer loop based method, where in the outer loop a reference full gradient is evaluated, after which $m \in \mathbb{N}$ steps of an inner loop are executed where the reference gradient is used to build a variance reduced estimate of the current gradient. The simplicity of the SVRG method and its analysis have led to multiple extensions and variants for even non-convex optimization. We provide a more general analysis of SVRG than had been previously done by using arbitrary sampling, which allows us to analyse virtually all forms of mini-batching through a single theorem. Furthermore, our analysis is focused on more practical variants of SVRG including a new variant of the loopless SVRG (Hofman et al 2015, Kovalev et al 2019, Kulunchakov and Mairal 2019) and a variant of k-SVRG (Raj and Stich 2018) where $m=n$ and where n is the number of data points. Since our setup and analysis reflect what is done in practice, we are able to set the parameters such as the mini-batch size and step size using our theory in such a way that produces a more efficient algorithm in practice, as we show in extensive numerical experiments. 

# Summary. An optional shortened abstract.
summary:

# tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1908.02725.pdf'
url_code: 'https://github.com/gowerrobert/StochOpt.jl'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
