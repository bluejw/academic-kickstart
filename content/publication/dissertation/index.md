---
title: "Novel Bayesian Methods for Precision Medicine in HIV"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
# - Wei Jin
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-10-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Johns Hopkins Libraries. **[Winner of the Leonard J. Savage Dissertation Award]**
# publication_short: In *ICW*

abstract: Numerous adverse effects (e.g., mental health disorders, chronic kidney failure, and cardiovascular diseases) have been reported for combination antiretroviral therapy (cART) despite its remarkable success in viral suppression in people with HIV. To improve long-term health outcomes and quality of life for people with HIV, there is an urgent need to design personalized optimal cART assignments with the lowest risk of comorbidity in the emerging field of precision medicine for HIV. Large-scale HIV databases offer researchers unprecedented opportunities to optimize personalized cART in a data-driven manner. However, the large number of possible drug combinations for cART makes the estimation a high-dimensional combinatorial problem, imposing challenges in both statistical inference and decision-making. In this dissertation, we focus on developing novel Bayesian methodologies that have clinical utility in guiding clinicians to prescribe informed and effective personalized HIV treatment based on individuals' treatment histories and clinical characteristics. First, we develop a Bayesian nonparametric approach to learn drug combination effects on mental health in people with HIV adjusting for sociodemographic, behavioral, and clinical factors. The proposed method is built upon the subset-tree kernel that represents drug combinations in a way that synthesizes known regimen structure into a single mathematical representation. The subset-tree kernel reduces the dimension of the drug combination space to a manageable size and encourages similar effects for similar cARTs. The proposed method also utilizes a distance-dependent Chinese restaurant process to cluster heterogeneous populations while considering individuals' treatment histories. The second main contribution of this dissertation is the development of a Bayesian regression tree model that studies the heterogeneous longitudinal drug effects of cART regimens and their interaction with genetic variants on depressive symptoms for people with HIV. The proposed method utilizes a Gaussian process to capture the longitudinal drug effects by incorporating individuals' treatment histories in its covariance function. Lastly, we develop a two-step Bayesian decision framework for optimizing personalized sequential cART assignments with proper uncertainty propagation. In the first step, we propose a probabilistic dynamic model for individuals' longitudinal observations using a multivariate Gaussian process. In the second step, we build a probabilistic generative model for cART assignments and design an uncertainty-penalized policy optimization using the uncertainty quantification from the first step. Through both simulation and real data studies, we demonstrate the clinical utility of the proposed methods in assisting HIV physicians to make effective treatment decisions, serving the purpose of both viral suppression and comorbidity risk reduction.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: http://jhir.library.jhu.edu/handle/1774.2/67847
- name: Media
  url: https://engineering.jhu.edu/ams/news/postdoc-receives-2023-leonard-j-savage-award/

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
