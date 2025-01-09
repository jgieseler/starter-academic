---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Single-spacecraft techniques for shock parameters estimation: A systematic approach'
subtitle: ''
summary: ''
authors:
- D. Trotta
- L. Vuorinen
- H. Hietala
- T. Horbury
- N. Dresing
- J. Gieseler
- A. Kouloumvakos
- D. J. Price
- F. Valentini
- E. Kilpua
- R. Vainio

tags:
- Coronal Mass Ejection
- Python
- SERPENTINE
- SerPyShock
- Shock
categories: []
date: '2022-10-19'
lastmod: 2022-10-19T17:00:00+02:00
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
projects: ["SERPENTINE"]
publishDate: '2022-10-19T17:00:00.395038Z'
publication_types:
- '2'
abstract: 'Spacecraft missions provide the unique opportunity to study the properties of collisionless shocks utilising in situ measurements. In the past years, several diagnostics have been developed to address key shock parameters using time series of magnetic field (and plasma) data collected by a single spacecraft crossing a shock front. A critical aspect of such diagnostics is the averaging process involved in the evaluation of upstream/downstream quantities. In this work, we discuss several of these techniques, with a particular focus on the shock obliquity (defined as the angle between the upstream magnetic field and the shock normal vector) estimation. We introduce a systematic variation of the upstream/downstream averaging windows, yielding to an ensemble of shock parameters, which is a useful tool to address the robustness of their estimation. This approach is first tested with a synthetic shock dataset compliant with the Rankine-Hugoniot jump conditions for a shock, including the presence of noise and disturbances. We then employ self-consistent, hybrid kinetic shock simulations to apply the diagnostics to virtual spacecraft crossing the shock front at various stages of its evolution, highlighting the role of shock-induced fluctuations in the parameters’ estimation. This approach has the strong advantage of retaining some important properties of collisionless shock (such as, for example, the shock front microstructure) while being able to set a known, nominal set of shock parameters. Finally, two recent observations of interplanetary shocks from the Solar Orbiter spacecraft are presented, to demonstrate the use of this systematic approach to real events of shock crossings. The approach is also tested on an interplanetary shock measured by the four spacecraft of the Magnetospheric Multiscale (MMS) mission. All the Python software developed and used for the diagnostics (SerPyShock) is made available for the public, including an example of parameter estimation for a shock wave recently observed in-situ by the Solar Orbiter spacecraft.'
publication: '*Front. Astron. Space Sci.*'
doi: 10.3389/fspas.2022.1005672
url_pdf : https://www.frontiersin.org/articles/10.3389/fspas.2022.1005672/pdf
---
