---
title: "A deep learning enhanced framework for multi-physics joint inversion"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Yanyan Hu
- admin
- Xuqing Wu
- Jiajia Sun
- Jiuping Chen
- Yueqin Huang
- Jiefu Chen

# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Geophysics (under review)*"
publication_short: ""

abstract: Using joint inversion to reveal underlying geology has drawn considerable research attention due to the availability of multiple geophysical datasets, ever-increasing computational resources, advanced inversion methodologies, and reduced uncertainties. A key issue of joint inversion is to develop effective strategies to link different geophysical data in a unified mathematical framework, where the information obtained from different models can complement each other. In this paper, we propose a deep learning enhanced (DLE) joint inversion framework to simultaneously reconstruct different physical models by fusing different types of geophysical data. Traditionally, structure similarity constraints are pursued by joint inversion algorithms using manually crafted formulations (e.g. cross gradient). In this work, the constraint is constructed by a deep neural network (DNN) during the learning process. The framework is designed to combine the DNN and the traditional independent inversion workflow together and improve the joint inversion result iteratively. The network can be easily extended to incorporate multi-physics without structural changes. Numerical experiments on the joint inversion of 2D DC resistivity data and seismic travel time show that the DLE framework achieves more accurate recovered property values and structural features than independent inversions and conventional cross gradient based joint inversion. In addition, this learning-based framework demonstrates excellent generalization abilities when tested on datasets using divergent geological structures. It can also handle different sensing configurations and nonconforming discretization.

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
