---
title: "Uncertainty analysis of 3D potential-field deterministic inversion using mixed L p norms"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jiajia Sun

# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-11-01T00:00:00Z"
doi: "10.1190/geo2020-0672.1"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Geophysics*"
publication_short: ""

abstract: The non-uniqueness problem in geophysical inversion, especially potential-field inversion, is widely recognized. It is argued that uncertainty analysis of a recovered model should be as important as finding an optimal model. However, quantifying uncertainty still remains challenging, especially for $3$D inversions in both deterministic and Bayesian frameworks. Our objective is to develop an efficient method to empirically quantify the uncertainty of the physical property models recovered from 3D potential-field inversion. We worked in a deterministic framework where an objective function consisting of a data misfit term and a regularization term is minimized. We performed inversions using a mixed Lp-norm formulation where various combinations of Lp ($0\leq p\leq2$) norms can be implemented on different components of the regularization term. Specifically, we randomly sampled the p-norm values in multiple times, and generated a large and diverse sequence of physical property models that all reproduce the observed geophysical data equally well. This suite of models offers practical insights into the uncertainty of the recovered model features. We quantified the uncertainty through calculation of standard deviations and interquartile range, as well as visualizations in box plots and histograms. The numerical results for a realistic synthetic density model created based on a ring-shaped igneous intrusive body quantitatively illustrate uncertainty reduction due to different amounts of prior information imposed on inversions. We also applied the method to a field data set over the Decorah area in the northeastern Iowa. We adopted an acceptance-rejection strategy to generate 31 equivalent models based on which the uncertainties of the inverted models as well as the volume and mass estimates are quantified.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://xiaolongw1223.github.io/resource/'
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
  focal_point: ""
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
slides: ""
---
