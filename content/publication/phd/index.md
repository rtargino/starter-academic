---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Statistical Methods in Financial Risk Management
subtitle: ''
summary: ''
authors:
- Rodrigo S Targino
tags: []
categories: []
date: '2017-01-01'
lastmod: 2020-09-21T17:11:59-03:00
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
publishDate: '2020-09-21T20:11:59.342181Z'
publication_types:
- 7
abstract: This thesis studies two different problems regarding financial companies' capital, which is a buffer used to cover unexpected losses. The first problem is related to understanding the capital, in a process called allocation and the second is connected to its management. For the capital allocation problem we follow the Euler principle and develop simulation-based algorithms to efficiently compute the contribution of individual names to the portfolio's overall capital. Although the algorithms proposed in this thesis are general enough to be applied to any portfolio, we focus on the allocation of operational risk and insurance capital. In both cases the algorithms proposed in this thesis are based on Sequential Monte Carlo (SMC) methods. In the context of operational risk we assume annual losses in the business lines are jointly modelled through a copula, and no parameter uncertainty is involved. In this case we are able to use the copula dependence structure to devise efficient algorithms. For the allocation of the one-year reserve risk and the one-year premium risk of insurance companies we develop a novel and fully Bayesian claims reserving model, and discuss how to perform allocations under parameter uncertainty. Further to understanding the company's capital we develop a class of financial instruments to facilitate the transference of operational risks, which would naturally lead to capital reductions. As the annual amount due to operational losses can be extremely large "full insurance coverage" is very expensive, preventing some companies from accessing the insurance market. To circumvent this problem we propose a class of insurance products that last for T years but the policyholder is only allowed to make claims for insurance coverage in k, less or equal to T, years. For some combinations of annual coverage and loss distribution we are able to derive the optimal usage strategy for these products in closed form and for general cases we present an approximation scheme based on density series expansion.
publication: ''
url_pdf: http://discovery.ucl.ac.uk/1551579/
---
