---
title: "NeBula: TEAM CoSTAR's Robotic Autonomy Solution that Won Phase II of
  DARPA Subterranean Challenge"
authors:
- Ali Agha
- Kyohei Otsu
- Benjamin Morrell
- and more
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-03-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
# publication:
#   name: "Field Robotics"
#   volume: 1
#   issue: 1

# peer_reviewed: true
# open_access: true
# license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# Note: a Test of Time award years after publication uses an explicit `date` that differs from the page date.
# awards:
#   - name: "Test of Time Award"
#     level: winner
#     date: "2025"
#     note: "Awarded for sustained impact 10 years after publication."
#   - name: "Editor's Choice"
#     level: featured

# funding:
#   - funder: "National Science Foundation"
#     grant: "NSF-1234567"

# abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - robotics
featured: false

hugoblox:
  ids:
    arxiv: 10.55417/fr.2022047

links:
  - name: Website
    url: https://costar.jpl.nasa.gov/
  - name: pdf
    url: https://www.journalfieldrobotics.org/Field_Robotics/SI_DARPA_SubT_files/Vol2_47.pdf


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Spot'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - robotics

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


This paper presents and discusses algorithms, hardware, and software architecture developed by the TEAM CoSTAR (Collaborative SubTerranean Autonomous Robots), competing in the DARPA Subterranean Challenge.  Specifically, it presents the techniques utilized within the Tunnel (2019) and Urban (2020) competitions,  where CoSTAR achieved 2nd and 1st place, respectively. We also discuss CoSTAR’s demonstrations in Martian-analog surface and subsurface (lava tubes) exploration. The paper introduces our autonomy solution, referred to as NeBula (Networked Belief-aware Perceptual Autonomy).  NeBula is an uncertainty-aware framework that aims at enabling resilient and modular autonomy solutions by performing reasoning and decision making in the belief space (space of probability distributions over the  robot  and  world  states). We  discuss  various  components  of  the  NeBula  framework, including:  (i) geometric and semantic environment mapping; (ii) a multi-modal positioning system; (iii)  traversability  analysis  and  local  planning;  (iv)  global  motion planning  and exploration  behavior;  (i)  risk-aware  mission  planning; (vi) networking and decentralized reasoning; and (vii) learning-enabled adaptation. We discuss the performance of NeBula on several robot types (e.g.  wheeled, legged, flying), in various environments.  We discuss the specific results and lessons learned from fielding this solution in the challenging courses of the DARPA Subterranean Challenge competition.


