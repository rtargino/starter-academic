---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Transform MCMC schemes for sampling intractable factor copula models
subtitle: ''
summary: ''
authors: []
tags: []
categories: []
date: '2022-11-02'
lastmod: 2021-05-18T10:35:08-03:00
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
publishDate: '2021-11-30T16:55:59.203291Z'
publication_types:
- '2'
abstract: In financial risk management, modelling dependency within a random vector
  is crucial and a standard approach is the use of a copula model. A flexible family
  of copulas, known as the factor copulas, is formed by the copulas extracted from
  factor models. Sampling from a factor copula is equivalent to sampling from the
  factor model and applying the cumulative distribution function (c.d.f.) to each
  component of the sample. Nonetheless, in many models of interest the c.d.f.'s are
  not explicitly known. In this talk I'll present theoretical and numerical properties
  of a transform Markov Chain Monte Carlo (MCMC) scheme developed to efficiently compute
  expectations conditional to rare events in which the unconditional distribution
  is given by an intractable factor copula.
location: 'Department of Statistics and Applied Probability (PSTAT), UCSB'
url_pdf: https://www.dropbox.com/s/603yuetkg9sodjr/Slides-Targino.pdf?dl=0
---
