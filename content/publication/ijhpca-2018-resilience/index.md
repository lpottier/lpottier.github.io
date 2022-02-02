---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Resilient co-scheduling of malleable applications
subtitle: ''
summary: ''
authors:
- Anne Benoit
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
publishDate: '2022-02-01T01:51:15.561674Z'
publication_types:
- '2'
abstract: ' Recently, the benefits of co-scheduling several applications have been
  demonstrated in a fault-free context, both in terms of performance and energy savings.
  However, large-scale computer systems are confronted by frequent failures, and resilience
  techniques must be employed for large applications to execute efficiently. Indeed,
  failures may create severe imbalance between applications and significantly degrade
  performance. In this article, we aim at minimizing the expected completion time
  of a set of co-scheduled applications. We propose to redistribute the resources
  assigned to each application upon the occurrence of failures, and upon the completion
  of some applications, in order to achieve this goal. First, we introduce a formal
  model and establish complexity results. The problem is NP-complete for malleable
  applications, even in a fault-free context. Therefore, we design polynomial-time
  heuristics that perform redistributions and account for processor failures. A fault
  simulator is used to perform extensive simulations that demonstrate the usefulness
  of redistribution and the performance of the proposed heuristics. '
publication: '*International Journal of High Performance Computing and Applications*'
url_pdf: https://doi.org/10.1177/1094342017704979
doi: 10.1177/1094342017704979
---
