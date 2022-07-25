---
title: "DL 3D gravity inversion"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Keenan Barker
- Jiajia Sun

# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "" #"2022-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*(in prep)*"
publication_short: ""

abstract: #Accurate delineation of salt body shapes is critical for hydrocarbon exploration. Various imaging methods based on seismic data have been developed. Due to the density contrast between salt and sedimentary rocks, gravity data have also been used as a de-risking tool to constrain the salt body shapes. However, quantifying uncertainties of the salt body shapes recovered from gravity data remains under-explored. Our goal is to understand and quantify how different constraint affect uncertainties of the salt body shapes reconstructed from gravity data. We adopt a trans-dimensional Markov chain Monte Carlo (MCMC) approach to explore the uncertainties. To address the computational challenges with MCMC sampling, we resort to two methods: sparse geometry parameterization and randomized  parallel tempering. The first employs a set of simple geometries to approximate the complex shapes of salt bodies, greatly reducing the number of parameters to be sampled and making the MCMC approach computationally feasible. The second serves to further improve the acceptance ratio and computational efficiency. To quantify the uncertainties of the recovered salt body shapes, we design several scenarios to simulate different constraints on the top boundary of salt bodies from seismic imaging. The results from different scenarios are compared to understand how uncertainties are reduced when stronger constraints are imposed. In addition, we investigate the effect of an uncertain salt density on the salt body reconstruction and the case of depth-varying densities in the sedimentary background. We apply our methods to the modified 2D SEG-EAGE and Sigsbee salt models and successfully quantify the uncertainties of the recovered salt body shapes in different scenarios.

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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- 3D_deep_learning_gravity_inversion

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
