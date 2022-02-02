---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Co-scheduling high-performance computing applications
subtitle: ''
summary: ''
authors:
- Guillaume Aupy
- Anne Benoit
- Loïc Pottier
- Padma Raghavan
- Yves Robert
- Manu Shantharam
tags:
- '"mine"'
- '"ensl"'
categories: []
date: '2017-05-01'
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
publishDate: '2022-02-01T01:51:16.069567Z'
publication_types:
- '6'
abstract: Big data applications play an increasing role in high-performance computing.
  They are perfect candidates for co-scheduling, as they obey flexible speedup models,
  alternating I/O operations and intensive computation phases. In this chapter, we
  discuss co-scheduling on failure-prone platforms. Checkpointing helps to mitigate
  the impact of a failure on a given application, but it must be complemented by redistributions
  to rebalance the load among all applications. Co-scheduling usually involves partitioning
  the applications into packs, and then scheduling each pack in sequence, as efficiently
  as possible. The objective is therefore to determine a partition into packs, and
  an assignment of processors to applications, that minimize the sum of the execution
  times of the packs. On the theoretical side, we assess the problem complexity. On
  the practical side, we design several polynomial-time heuristics to deal with the
  general problem with failures and redistribution costs. The proposed heuristics
  show very good performance while executing in very short time, hence validating
  the approach.
publication: '*Big Data Management and Processing*'
url_pdf: https://doi.org/10.1201/9781315154008-5
doi: 10.1201/9781315154008-5
---
