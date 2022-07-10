---
title: 'Centrifugal Compressor Aero-Mechanical Design: A Machine Learning Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Numerical NSI

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2021-06-01T00:00:00Z'
doi: https://doi.org/10.1115/GT2021-59473

# Schedule page publish date (NOT publication's date).
publishDate: '2021-09-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ASME Turbo Expo 2021*
publication_short: In *ASME*

abstract: The present paper presents an enhanced method for multi-disciplinary design and optimization of centrifugal compressors based on Machine Learning (ML) algorithms. The typical approach involves the preliminary design, the geometry parameterization, the generation of aero-mechanical databases and a surrogate-model based optimization. This procedure is able to provide excellent results, but it is time consuming and has to be repeated for each new design. The aim of the proposed procedure is to actively exploit the simulations performed in the past for subsequent designs thanks to the predictive capabilities of the ML surrogate model. A commercial 3D (three dimensional) computational fluid dynamics (CFD) solver for the aerodynamic computations and a commercial finite element code for the mechanical integrity calculations, coupled with scripting modules, have been adopted. Two different compressors, with different geometry and operating conditions, have been designed and two aero-mechanical databases have been developed. Then, these two databases have been joined and have been used for the training and validation of the surrogate model. To assess the performance of this approach, two new compressors have been designed, case 1 with operating conditions between those of the databases used for training and validation and case 2 with operating conditions far above. The use of an optimizer coupled to the prediction of the surrogate model has enabled to define the “best set” of model parameters, in compliance with aero-mechanical objectives and constraints. The accuracy of the ML algorithm forecast has been evaluated through CFD and FEM simulations carried out iteratively on the optimal samples, with new simulations added to the database for further training of the surrogate model. The results have been presented with reference to cases 1 and 2 and highlight all the benefits of the proposed approach.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Presented approach's pipeline diagram'
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
slides: example
---
slides: ""
# {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
