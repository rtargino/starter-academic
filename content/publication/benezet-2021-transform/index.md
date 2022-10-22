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
date: '2022-01-01'
lastmod: 2022-10-22T12:37:56-07:00
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
publishDate: '2022-10-22T19:37:56.291090Z'
publication_types:
- '2'
abstract: 'In financial risk management, modelling dependency within a random vector
  X is crucial, a standard approach is the use of a copula model. Say the copula model
  can be sampled through realizations of X having copula function C: had the marginals
  of Y been known, sampling Xi, the i-th component of X, would directly follow by
  composing Yi with its cumulative distribution function (c.d.f.) and the inverse
  c.d.f. of Xi. In this work, the marginals of Y are not explicit, as in a factor
  copula model. We design an algorithm which samples X through an empirical approximation
  of the c.d.f. of the Y-marginals. To be able to handle complex distributions for
  Y or rare-event computations, we allow Markov Chain Monte Carlo (MCMC) samplers.
  We establish convergence results whose rates depend on the tails of X, Y and the
  Lyapunov function of the MCMC sampler. We present numerical experiments confirming
  the convergence rates and also revisit a real data analysis from financial risk
  management.'
publication: '*Methodology and Computing in Applied Probability (in press)*'
links:
- name: URL
  url: https://hal.archives-ouvertes.fr/hal-03334526
---
