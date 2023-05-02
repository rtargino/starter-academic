---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Avoiding zero probability events when computing Value at Risk contributions
subtitle: ''
summary: ''
authors: []
tags: []
categories: []
date: '2023-06-06'
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
abstract: In this talk I will discuss the process of risk allocation for a generic multivariate model when the risk measure is chosen as the Value-at-Risk (VaR). We recast the traditional Euler contributions from an expectation conditional on an event of zero probability to a ratio involving conditional expectations whose conditioning events have strictly positive probability. We derive an analytical form of the proposed representation of VaR contributions for various parametric models. Our numerical experiments show that the estimator using this novel representation outperforms the standard Monte Carlo estimator in terms of bias and variance. Moreover, unlike the existing estimators, the proposed estimator is free from hyperparameters under a parametric setting.
location: 'SIAM Financial Mathematics 2023'
url_pdf: https://www.dropbox.com/s/f3p11iquw0i4b6m/slides_Euler_Malliavin.pdf?dl=0
---
