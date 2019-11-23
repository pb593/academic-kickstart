---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GP-ALPS: Automatic Latent Process Selection for Multi-Output Gaussian Process Models"
authors: [Pavel Berkovich, Eric Perim, Wessel Brunisma]
date: 2019-12-08T20:21:42Z
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-23T20:21:42Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "2nd Symposium on Advances in Approximate Bayesian Inference (AABI)"
publication_short: ""

abstract: "A simple and widely adopted approach to extend Gaussian processes (GPs) to multiple outputs is to model each output as a linear combination of a collection of shared, unobserved latent GPs. An issue with this approach is choosing the number of latent processes and their kernels. These choices are typically done manually, which can be time consuming and prone to human biases. We propose Gaussian Process Automatic Latent Process Selection (GP-ALPS), which automatically chooses the latent processes by turning off those that do not meaningfully contribute to explaining the data. We develop a variational inference scheme, assess the quality of the variational posterior by comparing it against the gold standard MCMC, and demonstrate the suitability of GP-ALPS in a set of preliminary experiments."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1911.01929v1
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
