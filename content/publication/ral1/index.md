---
title: "Design, Execution, and Post-Mortem Analysis of Prolonged Autonomous Robot Operations"
authors:
- admin
- Peter Lehner
- Martin Johannes Schuster
- Sebastian Riedel
- Rico Belder
- Armin Wedler
- Daniel Leidner
- Michael Beetz
- Freek Stulp
date: "2018-04-01T00:00:00Z"
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

abstract: In the context of space missions and terrestrial applications, both mission goals and task implementations for autonomous robots are becoming increasingly complex. Thus, the challenge of monitoring the achievement of task objectives and checking the correctness of their implementation is becoming more and more difficult. To tackle these problems, we propose an unified architecture that supports different stakeholders during the different phases of the deployment. 1) the design phase; 2) the runtime phase; 3) the post-mortem analysis phase. Furthermore, we implement this architecture by enhancing our task programming framework RAFCON with powerful logging, debugging and profiling capabilities. We demonstrate the efficiency of our approach in the context of the ROBEX mission, during which the DLR Lightweight Rover Unit autonomously deployed several seismometers in an unknown rough terrain on Mt. Etna, Sicily. The analysis results for a state machine consisting of more than 1500 states and more than 1900 transitions are presented. Finally, we give a comparison between our framework and related software tools.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- RAFCON
- Task Analysis
- Profiling
- Robotics
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/8260865
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
projects:
- robex

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
