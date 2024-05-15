---
title: 'Algorithmes stochastiques et réduction de variance grâce à un nouveau cadre pour l’optimisation bi-niveaux'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mathieu Dagréou
  - Pierre Ablin
  - Samuel Vaiter
  - Thomas Moreau

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In XXVIIIème Colloque Francophone de Traitement du Signal et des Images GRETSI
# publication_short: In *ICW*

abstract: L’optimisation bi-niveaux a de nombreuses applications en apprentissage automatique. Cet article présente un nouveau cadre pour la résolution de tels problèmes. Ce cadre permet d’éviter les différents obstacles qui se posent pour le calcul efficace du gradient de la fonction objectif. Il rend possible l’utilisation de n’importe quel estimateur non biaisé de directions de descente. Nous proposons une adaptation de l’algorithme de la descente de gradient stochastique et de l’algorithme SAGA à notre cadre. Des expériences numériques valident l’efficacité de l’approche proposée.

# Summary. An optional shortened abstract.
summary: Nous proposons un nouveau cadre qui permet d'adapter facilement n'importe quel algorithme stochastique pour des problèmes bi-niveaux. Dans ce cadre, on proposo SOBA, une adaptation de la SGD, et SABA, une adaptation de SAGA.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://gretsi.fr/data/colloque/pdf/2022_dagreou712.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
