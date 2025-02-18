---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "How to compute Hessian-vector products?"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2024-04-04T13:49:32+02:00
lastmod: 2024-04-04T13:49:32+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

With [Thomas Moreau](https://tommoral.github.io), [Samuel Vaiter](https://www.samuelvaiter.com) and [Pierre Ablin](https://pierreablin.com) we wrote a blogpost that received a [highlight](https://blog.iclr.cc/2024/04/02/blogposts-track-iclr-2023-announcing-accepted-blogposts/) in the blogpost track of ICLR2024. It explains the different ways to compute Hessian-Vector products with automatic differentiation and provides a benchmark comparing `Jax` and `PyTorch` in HVP computation. [You can check it out here!](https://iclr-blogposts.github.io/2024/blog/bench-hvp/)