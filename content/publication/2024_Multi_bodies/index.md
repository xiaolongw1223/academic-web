---
title: "Reconstruction of multiple target bodies using trans-dimensional Bayesian inversion with different constraints"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jiajia Sun
- Mrinal K. Sen

# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-06-01T00:00:00Z"
doi: "10.1109/TGRS.2024.3382106"

# Schedule page publish date (NOT publication's date).
publishDate: "" #"2022-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Geoscience and Remote Sensing*"
publication_short: ""

abstract: Geophysical geometry inversion aims to reconstruct the geometrical characteristics of subsurface target bodies, which is different from conventional inversion techniques that focus on subsurface physical properties (e.g., density and velocity). The published works on geometry inversion either focus on recovering one “optimal” model without considering uncertainty or are limited to situations where only a single anomalous body is sought when uncertainty is quantified. We aim to recover the geometries of multiple anomalous bodies and quantify their uncertainty in the trans-dimensional Bayesian framework. We adopt a sparse geometry parameterization strategy which allows approximating the shapes of anomalous bodies via a set of simple geometries (e.g., ellipses). To address the problem of multiple bodies in an area of study, we propose two strategies. The first strategy randomly samples a tuning parameter associated with the computation of the alpha shapes. In the second strategy, we devise two categories of geometries for sampling parent and child geometries. Each child geometry is assigned to one parent geometry, and various geometrical families represent the multiple target bodies. To understand the effects of multiple data constraints and structural constraints, we design several scenarios, where the borehole gravity and gravity gradient data serve as additional data constraints and seismic imaging provides the structural constraint on the top of target bodies. We apply our method to the modified Pluto salt model consisting of three salt bodies with drastically different shapes and volumes. The results demonstrate that our framework is capable of recovering the disconnected anomalous bodies while taking into account multiple data constraints as well as structural constraints.

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
- Geometry_inversion_and_uncertainty_quantification

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
