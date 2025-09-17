---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'A new method for determining the onset times of solar energetic particles
  and their uncertainties: Poisson-CUSUM bootstrap hybrid method'
subtitle: ''
summary: ''
authors:
- C. Palmroos
- N. Dresing
- J. Gieseler
- C. P. Gutiérrez
- R. Vainio
tags:
- 'methods: data analysis'
- 'methods: observational'
- 'methods: statistical'
- 'Sun: particle emission'
categories: []
date: '2025-02-01'
lastmod: 2025-09-17T15:57:30+03:00
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
publishDate: '2025-09-17T12:57:30.024322Z'
publication_types:
- '2'
abstract: '*Context.* Solar energetic particle (SEP) events are a type of space weather phenomena in which highly energetic charged particles are released from the Sun into interplanetary space by violent and eruptive phenomena, such as solar flares and coronal mass ejections. In order to assess the origin of SEPs, an accurate timing of their arrival at spacecraft is of utmost importance. Several methods for determining the starting time of an SEP event at an observer exist, but the uncertainty of this starting time is not assessed in a systematic way by the vast majority of studies.<br/><br/>*Aims.* Employing a newly developed hybrid method of Poisson-CUSUM combined with bootstrapping, we show that the uncertainty related to the onset of an event in any particular energy range is often more than the mere time resolution of the measuring apparatus, and furthermore, it is not necessarily symmetric with respect to the past and future of the determined onset. In addition, we provide a software tool to the scientific community that applies the presented method and automates the determination of SEP event onset times and their related uncertainties, and it finally allows one to easily perform a velocity dispersion analysis.<br/><br/>*Methods.* By applying the Poisson-CUSUM method coupled with statistical bootstrapping to SEP event observations, we demonstrate the effectiveness of the method on synthetic and real data, and we compare them to an analysis conducted using a classical approach in which the uncertainty is assumed based on the time resolution of the data.<br/><br/>*Results.* In the example case, the inferred SEP path length and injection time related to the event, acquired by the velocity dispersion analysis, differ from what is obtained without properly assessing the uncertainty related to the onset times in varying energies. We also present the software package, PyOnset, that automates many steps of the method along with providing powerful data-visualization methods and analysis tools. We release the code to the scientific community as open-source software.'
publication: '*Astronomy & Astrophysics*'
doi: 10.1051/0004-6361/202451280
---
