---
title: "On the Hardness of Robustness Transfer: A Perspective from Rademacher Complexity over Symmetric Difference Hypothesis Space (preprint)"

authors:
  - Yuyang Deng
  - admin
  - Junyuan Hong
  - Mehrdad Mahdavi
  - Lingjuan Lyu

# Author notes (optional)
author_notes:
  - 'Equal contribution. Work done during an internship at Sony AI'
  - 'Equal contribution'
  - 
  -
  - 
  
date: "2023-02-23T00:00:00Z"
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

abstract: Recent studies demonstrated that the adversarially robust learning under {{</* math */>}}$\ell_\infty${{</* /math */>}} attack is harder to generalize to different domains than standard domain adaptation. How to transfer robustness across different domains has been a key question in domain adaptation field. To investigate the fundamental difficulty behind adversarially robust domain adaptation (or robustness transfer), we propose to analyze a key complexity measure that controls the cross-domain generalization, the adversarial Rademacher complexity over symmetric difference hypothesis space {{</* math */>}}$\mathcal{H} \Delta \mathcal{H}${{</* /math */>}}. For linear models, we show that adversarial version of this complexity is always greater than the non-adversarial one, which reveals the intrinsic hardness of adversarially robust domain adaptation. We also establish upper bounds on this complexity measure. Then we extend them to the ReLU neural network class by upper bounding the adversarial Rademacher complexity in the binary classification setting. Finally, even though the robust domain adaptation is provably harder, we do find positive relation between robust learning and standard domain adaptation. We explain *how adversarial training helps domain adaptation in terms of standard risk*. We believe our results initiate the study of the generalization theory of adversarially robust domain adaptation, and could shed lights on distributed adversarially robust learning from heterogeneous sources, e.g., federated learning scenario. 

# Summary. An optional shortened abstract.
summary: 

# tags:
# - Source Themes
# featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/pdf/2302.12351.pdf'
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
