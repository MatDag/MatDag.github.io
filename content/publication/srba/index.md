---
title: 'A Lower Bound and a Near-Optimal Algorithm for Bilevel Empirical Risk Minimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mathieu Dagréou
  - Thomas Moreau
  - Samuel Vaiter
  - Pierre Ablin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In AISTATS
# publication_short: In *ICW*

abstract: Bilevel optimization problems, which are problems where two optimization problems are nested, have more and more applications in machine learning. In many practical cases, the upper and the lower objectives correspond to empirical risk minimization problems and therefore have a sum structure. In this context, we propose a bilevel extension of the celebrated SARAH algorithm. We demonstrate that the algorithm requires {{< math >}}$\mathcal{O}((n+m)^{\frac12}ε^{−1})${{< /math >}} gradient computations to achieve {{< math >}}$ε${{< /math >}}-stationarity with {{< math >}}$n+m${{< /math >}} the total number of samples, which improves over all previous bilevel algorithms. Moreover, we provide a lower bound on the number of oracle calls required to get an approximate stationary point of the objective function of the bilevel problem. This lower bound is attained by our algorithm, which is therefore optimal in terms of sample complexity.

# Summary. An optional shortened abstract.
summary: We provide a lower bound for AID algorithm solving bilevel ERM problems. We show that SRBA, a bilevel adaptation of SARAH, is near optimal in term of sample complexity, similarly to its single level counterpart.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2302.08766.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
  - name: arXiv
    url: https://arxiv.org/abs/2302.08766
  - name: PMLR
    url: https://proceedings.mlr.press/v238/dagreou24a.html

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
