---
title: "Towards Autonomous Planetary Exploration: The Lightweight Rover Unit (LRU), its Success in the SpaceBotCamp Challenge, and Beyond"
authors:
- Martin Johannes Schuster
- admin
- Kristin Bussmann
- Stefan Buettner
- Andreas Doemel
- Matthias Hellerer
- Hannah Lehner
- Peter Lehner
- Oliver Porges
- Josef Reill
- Sebastian Riedel
- Mallikarjuna Vayugundla
- Bernhard Vodermayer
- Tim Bodenmueller
- Christoph Brand
- Werner Friedl
- Iris Grixa
- Heiko Hirschmueller
- Michael Kassecker
- Zoltan-Csaba Marton
- Christian Nissler
- Felix Ruess
- Michael Suppa
- Armin Wedler

date: "2017-11-01T00:00:00Z"
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
publication: "*Journal of Intelligent & Robotic Systems*"
publication_short: "JINT"

abstract: Planetary exploration poses many challenges for a robot system. From weight and size constraints to extraterrestrial environment conditions, which constrain the suitable sensors and actuators. As the distance to other planets introduces a significant communication delay, the efficient operation of a robot system requires a high level of autonomy. In this work, we present our Lightweight Rover Unit (LRU), a small and agile rover prototype that we designed for the challenges of planetary exploration. Its locomotion system with individually steered wheels allows for high maneuverability in rough terrain and stereo cameras as its main sensors ensure the applicability to space missions. We implemented software components for self-localization in GPS-denied environments, autonomous exploration and mapping as well as computer vision, planning and control modules for the autonomous localization, pickup and assembly of objects with its manipulator. Additional high-level mission control components facilitate both autonomous behavior and remote monitoring of the system state over a delayed communication link. We successfully demonstrated the autonomous capabilities of our LRU at the SpaceBotCamp challenge, a national robotics contest with focus on autonomous planetary exploration. A robot had to autonomously explore an unknown Moon-like rough terrain, locate and collect two objects and assemble them after transport to a third object -- which the LRU did on its first try, in half of the time and fully autonomously. The next milestone for our ongoing LRU development is an upcoming planetary exploration analogue mission to perform scientific experiments at a Moon analogue site located on a volcano.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- LRU
- Space
- Autonomy
- RAFCON
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.1007/s10846-017-0680-9
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
  caption: 'Image credit: [**JINT**](https://link.springer.com/journal/10846)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- spacebotcamp

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---
