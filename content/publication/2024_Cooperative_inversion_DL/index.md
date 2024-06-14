---
title: "Three-dimensional cooperative inversion of airborne magnetic and gravity gradient data using deep-learning techniques"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:

- Yanyan Hu
- admin
- Xuqing Wu
- Jiajia Sun
- Yueqin Huang
- Jiefu Chen

# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-06-01T00:00:00Z"
doi: "10.1190/geo2023-0225.1"

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

abstract: Using multiple geophysical methods has become a prevailing approach in numerous geophysical applications to investigate subsurface structures and parameters. These multimethod-based exploration strategies have the potential to greatly diminish uncertainties and ambiguities encountered during geophysical data analysis and interpretation. One of the applications is the cooperative inversion of airborne magnetic and gravity gradient data for the interpretation of data obtained in mineral, oil and gas, and geothermal explorations. In this paper, a unified cooperative inversion framework is designed by combining the standard separate inversions with a deep neural network (DNN), which serves as the link between different types of data. A well-trained DNN takes the separately inverted susceptibility and density models as the inputs and provides improved models that will be used as the initial models of deterministic inversions. A two-round iteration strategy is adopted to guarantee the reasonability of the recovered models and overall efficiency of the inversion. In addition, this deep-learning (DL)-based framework demonstrates excellent generalization abilities when tested on models that are entirely distinct from the training data sets. The framework can easily incorporate multiphysics without necessitating any structural changes to the network. Synthetic experiments validate that our DL-based method outperforms conventional separate inversions and cross-gradient-based joint inversion in view of the accuracy of the recovered models and inversion efficiency. Successful application to field data further verifies the effectiveness of our DL-based method.

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
- Deep_learning_enhanced_joint_inversion

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
