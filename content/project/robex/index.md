---
title: Robex
summary: Moon-analogue demonstration mission on Mt. Etna, Sicily
tags:
- Robotics
- Autonomy
- System Architecture
- Space
date: "2017-06-26T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Demo Site with LRU rover
  focal_point: Smart


url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=MVtToA8TlLc"
links:
- icon: home
  icon_pack: fas
  name: Project Homepage
  url: http://www.robex-allianz.de/en/
- icon: home
  icon_pack: fas
  name: Project Blog
  url: https://www.dlr.de/dlr/en/desktopdefault.aspx/tabid-10081/151_read-23091/#/gallery/27370
- icon: robot
  icon_pack: fas
  name: Robot Specifications
  url: https://www.dlr.de/rm/en/desktopdefault.aspx/tabid-11431/#gallery/27820
  
 
#http://www.robex-allianz.de/en/
#https://www.youtube.com/watch?v=MVtToA8TlLc
#https://www.youtube.com/watch?v=-wXQf0b1bqQ
#https://www.dlr.de/dlr/en/desktopdefault.aspx/tabid-10081/151_read-23091/#/gallery/27370

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example



---

For the Demonstration Mission Space a dedicated scenario was chosen by the ROBEX lunar scientists. The scenario describes the installation of an active seismic network (ASN) on the Moon’s surface. Main focus here is the measurement of the internal structure and the composition of the upper layer, the lunar regolith. Other questions are the existence and composition of a central core of the Moon and if there is any seismic activity. The seismometers are planned to be transported by a rover and put down on surface by means of a robotic arm.

The analogue mission on the Mt. Etna basically consisted of two individual experiments: First, our rover mapped the lander site, deployed the seismic instrument, waited until one measurement cycle was done, took it up again and repeated the measurement on several points of interest. In the second experiment, the rover had to set up a seismic network consisting of four instruments that had to be arranged at three corner points and the center point of an equilateral triangle of about 100 m. Both scenarios required the robot to be equipped with highly robust navigation, perception and manipulation capabilities in order to place the instruments carefully and precisely onto the ground. Our robot was able to perform these tasks fully autonomously.

My responsibilities: Autonomous Task Control, System Architecture, Task Execution Logging and Profiling, Semantic World Modeling
