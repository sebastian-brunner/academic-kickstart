---
title: Bundle Adjustment on FPGAs
summary: Logistics League, International Robocup
tags:
- Software
- Bundle Adjustment
- SLAM
- Computer Vision
- C++
date: "2014-03-31T00:00:00Z"

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
url_code: "https://github.com/sebastian-brunner/mcsba"
url_pdf: ""
url_slides: ""
#url_video: "https://www.youtube.com/watch?v=77V-7LzMBY8"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# TODO: add links to cvt library
# TODO: add master thesis publication + refer with slides to it
# TODO: upload video to my channel

---

My master thesis gives a detailed insight into bundle adjustment as a powerful tool for globally optimizing maps created by feature based simultaneous localization and mapping (SLAM). Background knowledge, especially concerning the mathematical theory, is be illustrated clearly. Different problems affecting robustness and efficiency are examined and solutions are given. Therefore a major part focuses on the parallel implementation in OpenCL, a language for parallelizing algorithms for different processor architectures like CPUs, GPUs and FPGAs. The algorithm is tested against different synthetic and real datasets and the results are shown graphically using Point Clouds and the CVT library. In addition, different implementations are compared with each other concerning robustness and performance. It is illustrated that a hybrid OpenCL bundle adjustment implementation, which is using a GPU and a CPU simultaneously, outperforms all other approaches.
