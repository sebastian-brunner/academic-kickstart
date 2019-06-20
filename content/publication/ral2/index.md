---
title: "Autonomous Parallelization of Resource-Aware Robotic Task Nodes"
authors:
- admin
- Andreas Doemel
- Peter Lehner
- Michael Beetz
- Freek Stulp
date: "2019-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
#publication: In *IEEE Robotics and Automation Letters*
#publication_short: In *RA-L*
publication: "*IEEE Robotics and Automation Letters*"
publication_short: "RA-L"

abstract: Robot task programming often leads to inefficient plans, as opportunities for parallelization and precomputation are usually not exploited by the programmer. This inefficiency is often especially obvious in mobile manipulation, where path planning and pose estimation algorithms are time-consuming operations. In this paper, we introduce the concept of Resource-Aware Task Nodes (RATNs), a powerful descriptive action model for robots. Next, we propose an algorithm that executes so-called Concurrent Dataflow Task Networks (CDTNs), robot plans consisting of RATNs. It optimizes programmed plans based on two sources of information. 1) The control flow represented in the original task plan, whose constraints are relaxed to generate opportunities for parallelization and precomputation. 2) Dependencies between actions pertaining to resources, data flows and world model changes, the latter being equivalent to preconditions and effects. CDTNs have been integrated in our open-source task programming framework RAFCON, and we show that it leads to 11-29% improvement in terms of execution time in two simulated mobile manipulation scenarios.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- RAFCON
- Autonomy
- Planning
- Scheduling
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/8620533
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**IEEE**](https://ieeexplore.ieee.org)'
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---
