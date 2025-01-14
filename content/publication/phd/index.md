---
title: 'Contributions to stochastic bilevel optimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mathieu Dagréou


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['7']

# Publication name and optional abbreviated publication name.
# publication: In AISTATS
# publication_short: In *ICW*

abstract: Bilevel problems are a type of optimization problem characterized by a hierarchical structure. In these problems, one wants to minimize an outer function under the constraint that some variables minimize an inner function. These problems are gaining popularity in the machine learning community due to their wide range of applications, such as hyperparameter optimization. In this thesis, we explore approximate implicit differentiation-based algorithms to address bilevel problems where both the outer and inner functions are empirical means over potentially large sample sets. This empirical risk minimization framework is a classical approach in many machine learning tasks. First, we introduce a general algorithmic framework that allows any first-order stochastic solver, initially designed for single-level problems, to be adapted to bilevel problems. We provide and analyze two instantiations of this framework:an adaptation of the stochastic gradient descent and of the SAGA algorithm to bilevel problems. Our analysis demonstrates that these algorithms have complexities comparable to their single-level counterparts. Then, we interest ourselves in the complexity of bilevel optimization in the nonconvex/strongly convex setting. We propose an algorithm class that includes several stochastic approximate implicit differentiation based methods and establish a lower bound on the number of oracle calls required to reach an approximate stationary point. Then, we propose an algorithm whose complexity matches this lower bound. The performances of the proposed methods are evaluated numerically by a benchmark comparing those methods to other bilevel algorithms on quadratic functions, hyperparameter selection problems, and the datacleaning task.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://theses.hal.science/tel-04877851v1/file/136702_DAGREOU_2024_archivage.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'publication/phd/phd_defense.pdf'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=8-m63WB4G-Y&t=8012s&pp=ygUHZGFncmVvdQ%3D%3D'

links:
  - name: 'hal'
    url: 'https://theses.hal.science/tel-04877851'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
