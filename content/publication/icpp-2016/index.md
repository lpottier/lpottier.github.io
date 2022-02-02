---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Resilient Application Co-scheduling with Processor Redistribution
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
date: '2016-08-01'
lastmod: 2022-01-31T17:51:16-08:00
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
publishDate: '2022-02-01T01:51:16.166898Z'
publication_types:
- '1'
abstract: Recently, the benefits of co-scheduling several applications have been demonstrated
  in a fault-free context, both in terms of performance and energy savings. However,
  large-scale computer systems are confronted to frequent failures, and resilience
  techniques must be employed to ensure the completion of large applications. Indeed,
  failures may create severe imbalance between applications, and significantly degrade
  performance. In this paper, we propose to redistribute the resources assigned to
  each application upon the striking of failures, in order to minimize the expected
  completion time of a set of co-scheduled applications. First, we introduce a formal
  model and establish complexity results. When no redistribution is allowed, we can
  minimize the expected completion time in polynomial time, while the problem becomes
  NP-complete with redistributions, even in a fault-free context. Therefore, we design
  polynomial-time heuristics that perform redistributions and account for processor
  failures. A fault simulator is used to perform extensive simulations that demonstrate
  the usefulness of redistribution and the performance of the proposed heuristics.
publication: '*45th International Conference on Parallel Processing, ICPP 2016, Philadelphia,
  PA, USA, August 16-19, 2016*'
url_pdf: https://doi.org/10.1109/ICPP.2016.21
doi: 10.1109/ICPP.2016.21
---
