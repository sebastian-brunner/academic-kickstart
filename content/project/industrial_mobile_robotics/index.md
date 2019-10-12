---
title: Industrial Mobile Manipulation
summary: Industrial, Autonomous Mobile Manipulation
tags:
- Robotics
- Mobile
- Industrial
- Autonomy
- System Architecture
- Python
date: "2018-07-02T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: AIMM robot manipulating filled boxes
  focal_point: Smart


url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=uNiaRL_CDhA"
links:
- icon: home
  icon_pack: fas
  name: Automatica Scenario
  url: https://www.dlr.de/content/de/artikel/news/2018/2/20180619_dlr-highlights-auf-der-automatica-2018_28474.html
- icon: home
  icon_pack: fas
  name: FoF Homepage
  url: https://factory-of-the-future.dlr.de/
- icon: robot
  icon_pack: fas
  name: Robot Specifications
  url: https://www.dlr.de/rm/en/desktopdefault.aspx/tabid-11409/#gallery/29194


---

The [AIMM](https://www.dlr.de/rm/en/desktopdefault.aspx/tabid-11409) robot is an industrial mobile manipulator able to autonomously perceive and manipulate its environment. It was used for various scenarios (especially pre-assembly and logistics) in multiple projects and demos: [FoF](https://factory-of-the-future.dlr.de/), [EuRoC](http://www.euroc-project.eu/), [Automatica 2018](https://messe-muenchen.de/en/technical/events/automatica-2018.php), [TAPAS](http://www.tapas-project.eu/) and [Automatica 1016](https://messe-muenchen.de/en/technical/events/automatica-2016.php).

I am a core developer of AIMM's software stack. My main responsibilities are creating software for autonomous task control and belief state modeling. We put a high effort in the system architecture of AIMM, as it is a complex, mobile robot with 13 DOFs (including a impedance controlled LWR 4+), four cameras systems (able to produce depth information using [SGM](https://core.ac.uk/download/pdf/11134866.pdf)) and laser scanners. It features six computers: One for low-level realtime control, one for navigation, one for object detection and scene reconstruction, one for path planning, one for data logging and processing and one for high level autonomy. On top of the multitude of software models we employ four different middlewares: 'links and nodes' for realtime control, 'sensornet' for high bandwidth sensor data, 'ROS' for third party library integration and data visualization and Kuka's Sunrise middleware. We use continuous integration to develop and release new software. Furthermore, we employ a powerful release and dependency management toolchain to track and deploy consistent software versions to AIMM.

My responsibilities: Autonomous Task Control, System Architecture, Task Execution Logging and Profiling, Semantic World Modeling
