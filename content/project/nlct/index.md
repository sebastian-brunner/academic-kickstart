---
title: NLCT
summary: NonLinear Covariance Transform library
tags:
- Software
- Uncertainty
- Statistics
- Unscented Transform
date: "2014-02-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Sponza Pointcloud during Optimization
  focal_point: Center

links:
#- icon: home
#  icon_pack: fab
#  name: Team Homepage
#  url: https://www.bbunits.de/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# TODO: add links to cvt library
# TODO: add master thesis publication + refer with slides to it
# TODO: upload video to my channel

# It uses the Unscented transform and linearization for approximation of non-linear covariance transformations.

---

NLCT is a lightweight library written in C++ to:

* convert the covariance matrices for poses between different representations: Quaternions, Euler Angle (both fixed and moving frames)
* compute the composition of multiple certain and uncertain poses
* transform the covariance of a pose from one coordinate frame into another

For all functions the user can choose the computation method: UNSCENTED, JACOBIAN, SAMPLING. The computation methods are a trade-off between accuracy and computation speed. The library includes functions for normalization, representation conversions and pose transformations (like composition, inversion etc.).


