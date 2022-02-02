---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Co-Scheduling Algorithms for Cache-Partitioned Systems
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
publishDate: '2022-02-01T01:51:15.971269Z'
publication_types:
- '1'
abstract: 'Cache-partitioned architectures allow subsections of the shared last-level
  cache (LLC) to be exclusively reserved for some applications. This technique dramatically
  limits interactions between applications that are concurrently executing on a multicore
  machine. Consider n applications that execute concurrently, with the objective to
  minimize the makespan, defined as the maximum completion time of the n applications.
  Key scheduling questions are: (i) which proportion of cache and (ii) how many processors
  should be given to each application? Here, we assign rational numbers of processors
  to each application, since they can be shared across applications through multi-threading.
  In this paper, we provide answers to (i) and (ii) for perfectly parallel applications.
  Even though the problem is shown to be NP-complete, we give key elements to determine
  the subset of applications that should share the LLC (while remaining ones only
  use their smaller private cache). Building upon these results, we design efficient
  heuristics for general applications. Extensive simulations demonstrate the usefulness
  of co-scheduling when our efficient cache partitioning strategies are deployed.'
publication: '*2017 IEEE International Parallel and Distributed Processing Symposium
  Workshops, IPDPS Workshops 2017, Orlando / Buena Vista, FL, USA, May 29 - June 2,
  2017*'
url_pdf: https://doi.org/10.1109/IPDPSW.2017.60
doi: 10.1109/IPDPSW.2017.60
---
