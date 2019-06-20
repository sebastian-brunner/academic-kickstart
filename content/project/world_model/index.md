---
title: Semantic World Model
summary: Semantic World Model based on a Graph Database
tags:
- Software
- Graph Database
- Semantic Knowledge
date: "2014-02-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Visualization of a mobile robot's world model
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

# TODO: add publication

# not added text: This is done via a so called object-graph-mapping (OGM) using the neomodel library \footnote{\url{https://github.com/robinedwards/neomodel}}.

# Two examples would be 1) the GeometricScene-Adapter, which provides services to get a reduced object tree with everything relevant for building a geometric scene representation for motion planning, and 2) a ROS-Tf-Adapter, which takes care of periodically publishing the world as ROS-Tf-tree as well as updating externally published transformations (for example robot\_flange => robot\_base) in the world model.
---

The world model is implemented using the graph database Neo4j (https://neo4j.com/) as backend.
Neo4j represents data using a property-graph model, meaning the database is a graph composed of nodes and interconnected by edges, both of which can store arbitrary properties in a key-value fashion.
For our world model, we directly represent objects in the world model as nodes in the database graph and correspondingly edges in the graph build up the world model tree structure.
The relative position and orientation between two objects are stored as properties of the connecting edge.
We define and ensure a common type-system for objects in the world, by defining a type-hierarchy with precisely listed required and optional properties for each object type (e.g. every PhysicalObject has to have a mass; every Grasp a width and force).

A database as backend in general provides useful features to keep the world model consistent at any time, e.g. synchronized multi-client read-/write-access and transaction support for batching multiple modifications into an atomic operation.
In particular, we use transactions with pre-/post-transaction sanity checks to allow complex yet safe operations on the world model. In case of a software error or violated sanity checks (e.g. a world model object suddenly has two parents), the world model is automatically rolled back to the consistent state before this modification.
As a graph database, Neo4j offers a pattern-related query language called \textit{CYPHER}, which makes it very easy to query the world model for e.g. "all rigid bodies for which a grasp is defined."

We use YAML-files as a human read-/writeable way to specify the initial world model, but also complex object templates (e.g. complete subgraphs of PhysicalObjects together with attached Grasps and Markers, etc.). To add such templates into the world model, we developed a domain-specific module and API for higher level operations based on the raw CYPHER-access to the database.
Other more complex operations include querying the relative transformation between arbitrary objects in the graph or maintaining unique labels for nodes. This API is the basis for several adapter modules which make operations accessible via ROS services. New functionality or composite operations can be added in a modular way by writing additional adapters as necessary.


