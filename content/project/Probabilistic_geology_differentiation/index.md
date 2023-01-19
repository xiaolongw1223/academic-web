---
title: Probabilistic geology differentiation
summary: We proposed mixed Lp norm joint inversion framework to construct 3D probabilistic subsurface geological units
tags:
- uncertainty
- MinEx
- differentiation
date: "2021-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: ""
  preview_only: false

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### Figure Caption
(Top) The probabilities of spatial distribution for Units 2 to 9. Warmer colors represent higher probabilities, and colder colors indicate lower probabilities. (Bottom) The probabilities of geological units at different locations indicated by black boxes.

### Research Summary
[Geology differentiation](https://sites.google.com/view/jiajiasun/research/geology-differentiation) takes geophysical measurements and inversion results one step closer to the goal of characterizing subsurface geology. It provides a natural way to incorporate prior geological knowledge, physical property measurements and the inverted physical property models into one framework, and helps us to extract more information from geophysical data sets. The results of geology differentiation are typically in the form of a 3D quasi-geology model which shows the spatial distribution of various geological units identified during the geology differentiation process. It is, therefore, of practical significance to be able to quantify the uncertainties of the geological units in a quasi-geology model.

We have developed an effective workflow to construct 3D probabilistic quasi-geology models in the deterministic inversion framework. Two essential components of our workflow are the generation of a large sequence of equivalent physical property models and the acceptance/rejection of these models. We have used mixed Lp norm joint inversion to generate a large sequence of density contrast and susceptibility models. The prior physical property measurements on drill core samples have been used to accept only these models that are consistent with physical property measurements. We have performed geology differentiation for all these accepted models and obtained a set of 3D quasi-geology models, based on which we quantify uncertainties of spatial distributions for each geological unit and calculate probabilities of geological unit types at any location in a study area.
