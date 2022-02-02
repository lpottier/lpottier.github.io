---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Co-scheduling HPC workloads on cache-partitioned CMP platforms
subtitle: ''
summary: ''
authors:
- Guillaume Aupy
- Anne Benoit
- Brice Goglin
- Loïc Pottier
- Yves Robert
tags:
- '"mine"'
- '"ensl"'
categories: []
date: '2019-04-01'
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
publishDate: '2022-02-01T01:51:15.661803Z'
publication_types:
- '2'
abstract: ' With the recent advent of many-core architectures such as chip multiprocessors
  (CMPs), the number of processing units accessing a global shared memory is constantly
  increasing. Co-scheduling techniques are used to improve application throughput
  on such architectures, but sharing resources often generates critical interferences.
  In this article, we focus on the interferences in the last level of cache (LLC)
  and use the Cache Allocation Technology (CAT) recently provided by Intel to partition
  the LLC and give each co-scheduled application their own cache area. We consider
  m iterative HPC applications running concurrently and answer to the following questions:
  (i) How to precisely model the behavior of these applications on the cache-partitioned
  platform? and (ii) how many cores and cache fractions should be assigned to each
  application to maximize the platform efficiency? Here, platform efficiency is defined
  as maximizing the performance either globally, or as guaranteeing a fixed ratio
  of iterations per second for each application. Through extensive experiments using
  CAT, we demonstrate the impact of cache partitioning when multiple HPC applications
  are co-scheduled onto CMP platforms. '
publication: '*International Journal of High Performance Computing Applications*'
url_pdf: https://doi.org/10.1177/1094342019846956
doi: 10.1177/1094342019846956
---
