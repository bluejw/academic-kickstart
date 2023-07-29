---
title: "A Bayesian Nonparametric Approach for Inferring Drug Combination Effects on Mental Health in People with HIV"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
# - Wei Jin
- admin
- Yang Ni
- Leah H. Rubin
- Amanda B. Spence
- Yanxun Xu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-06-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Biometrics, 78(3), 988-1000. [Winner of the Joint Statistical Meetings (JSM) Student Paper Award, Mental Health Statistics Section]
# publication_short: In *ICW*

abstract: Although combination antiretroviral therapy (ART) with three or more drugs is highly effective in suppressing viral load for people with HIV (human immunodeficiency virus), many ART agents may exacerbate mental health-related adverse effects including depression. Therefore, understanding the effects of combination ART on mental health can help clinicians personalize medicine with less adverse effects to avoid undesirable health outcomes. The emergence of electronic health records offers researchers' unprecedented access to HIV data including individuals' mental health records, drug prescriptions, and clinical information over time. However, modeling such data is challenging due to high dimensionality of the drug combination space, the individual heterogeneity, and sparseness of the observed drug combinations. To address these challenges, we develop a Bayesian nonparametric approach to learn drug combination effect on mental health in people with HIV adjusting for sociodemographic, behavioral, and clinical factors. The proposed method is built upon the subset-tree kernel that represents drug combinations in a way that synthesizes known regimen structure into a single mathematical representation. It also utilizes a distance-dependent Chinese restaurant process to cluster heterogeneous populations while considering individuals' treatment histories. We evaluate the proposed approach through simulation studies, and apply the method to a dataset from the Women's Interagency HIV Study, showing the clinical utility of our model in guiding clinicians to prescribe informed and effective personalized treatment based on individuals' treatment histories and clinical characteristics.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: https://onlinelibrary.wiley.com/doi/full/10.1111/biom.13508
- name: arXiv
  url: https://arxiv.org/abs/2004.05487
- name: Code
  url: https://github.com/bluejw/BayesDrugComb
- name: Shiny
  url: https://wjin.shinyapps.io/Rshiny/

# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#    caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#    focal_point: ""
#    preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#   slides: example
---
