---
title: "Robust Bayesian Learning for Individualized Treatment Rules Under Unmeasured Confounding"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
# - Wei Jin
- admin
- Yang Ni
- Yanxun Xu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-11-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Submitted
# publication_short: In *ICW*

abstract: Data-driven personalized decision-making has become increasingly important in many scientific fields. Most existing methods rely on the assumption of no unmeasured confounding to establish causal inferences before proceeding with decision-making for identifying the optimal individualized treatment rule (ITR). However, this assumption is often violated in practice, especially in observational studies. While techniques like instrumental variables or proxy variables can help address unmeasured confounding, such additional data sources are not always available. Moreover, robustly learning the optimal ITR from observational data is challenging when data are unbalanced, where certain combinations of treatments and patient characteristics are underrepresented. In this paper, we develop a novel Bayesian approach to robustly learn the optimal ITR for continuous treatments under unmeasured confounding. For causal identification, we propose a Bayesian causal model that achieves unique identification under certain mild distributional assumptions, without requiring additional data sources. For policy optimization, we develop a practical algorithm that robustly learns the optimal ITR by identifying a conservative policy. Through simulations and an application to a large-scale kidney transplantation dataset, we demonstrate the proposed method’s identifiability, utility, and robustness, highlighting its value in advancing precision medicine.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: Code
#   url: https://github.com/bluejw/BayesDCG

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
