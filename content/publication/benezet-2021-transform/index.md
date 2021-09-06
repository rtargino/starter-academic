---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Transform MCMC schemes for sampling intractable factor copula models
subtitle: ''
summary: ''
authors:
- Cyril Benezet
- Emmanuel Gobet
- Rodrigo S. Targino
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-09-06T12:53:52-03:00
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
publishDate: '2021-09-06T16:20:50.471748Z'
publication_types:
- 3
abstract: 'In financial risk management, modelling dependency within a random vector
  $X̧$ is crucial, a standard approach is the use of a copula model. Say the copula
  model can be sampled through realizations of $$̧ having copula function $C$: had
  the marginals of $c ̧been known, sampling $cX,̧ the $i$-th component of $cX$w̧ould
  directly follow by composing $cYi$i̧th its cumulative distribution function (c.d.f.)
  and the inverse c.d.f. of $cXi$.ņ this work, the marginals of $cY$ arņot explicit,
  as in a factor copula model. We design an algorithm which samples $cX$ thrģh an
  empirical approximation of the c.d.f. of the $cY$-marga̧ls. To be able to handle
  complex distributions for $cY$ or ra-̧event computations, we allow Markov Chain
  Monte Carlo (MCMC) samplers. We establish convergence results whose rates depend
  on the tails of $cX$, $cY$ņd they̧apunov function of the MCMC sampler. We present
  numerical experiments confirming the convergence rates and also revisit a real data
  analysis from financial risk management.'
publication: ''
url_pdf: https://hal.archives-ouvertes.fr/hal-03334526
---
