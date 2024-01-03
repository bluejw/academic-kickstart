---
title: "BayTetra: A Bayesian Semiparametric Approach for Testing Trajectory Differences"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
# - Wei Jin
- admin
- Qiuxin Gao
- Yanxun Xu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-01-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In ***Statistics in Medicine***, Under Review
# publication_short: In *ICW*

abstract: Testing differences in longitudinal trajectories among distinct groups of population is an important task in many biomedical applications. Motivated by an application in Alzheimer’s disease, we develop BayTetra, an innovative Bayesian semiparametric approach for estimating and testing group differences in multivariate longitudinal trajectories. BayTetra jointly models multivariate longitudinal data by directly accounting for correlations among different responses, and uses a semiparametric framework based on B-splines to capture the non-linear trajectories with great flexibility. To avoid overfitting, BayTetra encourages parsimonious trajectory estimation through spike-and-slab priors on the spline coefficients. The proposed method converts the challenging task of hypothesis testing for longitudinal trajectories into a more manageable equivalent form based on hypothesis testing for spline coefficients. More importantly, by leveraging posterior inference with natural uncertainty quantification, our Bayesian method offers a more robust and straightforward hypothesis testing procedure than frequentist methods. Extensive simulations demonstrate BayTetra's superior performance over alternatives. Applications to the Biomarkers of Cognitive Decline Among Normal Individuals (BIOCARD) study yield interpretable and valuable clinical insights. A major contribution of this paper is that we have developed an R package **BayTetra**, which implements the proposed Bayesian semiparametric approach and is the first publicly available software for hypothesis testing on trajectory differences based on a flexible modeling framework.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: R Package
  url: https://github.com/bluejw/BayTetra

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
