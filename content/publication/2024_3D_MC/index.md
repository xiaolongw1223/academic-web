---
title: "3D Monte Carlo geometry inversion using gravity data"

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
doi: "10.1190/geo2023-0498.1"

# Schedule page publish date (NOT publication's date).
publishDate: "" #"2022-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Geophysics*"
publication_short: ""

abstract: Diverse Monte Carlo methods have gained widespread use across a broad range of applications. However, the challenge of 3D Monte Carlo sampling remains due to the curse of dimensionality. To date, only a few works have been published regarding 3D Monte Carlo sampling. This study aims to develop an efficient 3D transdimensional Monte Carlo framework for reconstructing the spatial geometry of an anomalous body using gravity data. Our framework also can quantify the uncertainty of the shape of an anomalous body recovered from geophysical measurements. To improve the computational efficiency of 3D Monte Carlo sampling, we develop a sparse geometry parameterization strategy. This approach adequately approximates the shape of a complex 3D anomalous body using a set of simple geometries, such as ellipsoids. Each ellipsoid can be characterized by a few parameters, such as the centroid, axes, and orientations, significantly reducing the number of parameters to be sampled. During the sampling, we randomly perturb the number, locations, sizes, and orientations of the ellipsoids. To impose prior structural constraints from other geophysical methods, such as seismic imaging, we design a new method by placing a fixed layer oriented along the top boundary of the anomalous body. The fixed layer is then connected to the randomly sampled ellipsoids using an alpha shape, allowing us to estimate the geometry of the anomalous source body. The current work focuses on the reconstruction of salt bodies. We start with a synthetic spherical salt model and then conduct a more realistic study using a simplified 3D SEG/EAGE salt model, which has a much more complex geometry than the synthetic spherical model. Finally, we apply our method to the Galveston Island salt dome, offshore Texas. The numerical results demonstrate that our framework can effectively recover the shape of an anomalous body and quantify the uncertainty of the reconstructed geometry.

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
