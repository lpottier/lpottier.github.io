---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A Performance Model to Execute Workflows on High-Bandwidth-Memory Architectures
subtitle: ''
summary: ''
authors:
- Anne Benoit
- Swann Perarnau
- Loïc Pottier
- Yves Robert
tags:
- '"mine"'
- '"ensl"'
categories: []
date: '2018-01-01'
lastmod: 2022-01-31T17:51:15-08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-02-01T01:51:15.870499Z'
publication_types:
- '1'
abstract: 'This work presents a realistic performance model to execute scientific
  workflows on high-bandwidth-memory architectures such as the Intel Knights Landing.
  We provide a detailed analysis of the execution time on such platforms, taking into
  account transfers from both fast and slow memory and their overlap with computations.
  We discuss several scheduling and mapping strategies: not only tasks must be assigned
  to computing resources, but also one has to decide which fraction of input and output
  data will reside in fast memory and which will have to stay in slow memory. We use
  extensive simulations to assess the impact of the mapping strategies on performance.
  We also conduct experiments for a simple 1D Gauss-Seidel kernel, which assess the
  accuracy of the model and further demonstrate the importance of a tuned memory management.
  Our model and results lay the foundations for further studies and experiments on
  dual-memory systems.'
publication: '*Proceedings of the 47th International Conference on Parallel Processing,
  ICPP 2018, Eugene, OR, USA, August 13-16, 2018*'
url_pdf: https://doi.org/10.1145/3225058.3225110
doi: 10.1145/3225058.3225110
---
