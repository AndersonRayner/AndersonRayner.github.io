---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Online Self-Supervised Thermal Water Segmentation for Aerial Vehicles"
authors: 
- Connor Lee
- Jonathan Gustafsson Frennert
- Lu Gan
- Matthew Anderson
- Soon-Jo Chung
date: 2023-07-18

# Schedule page publish date (NOT publication's date).
publishDate: 2023-07-18

# Publication type.
publication_types: 
  - paper-conference

# Publication name and optional abbreviated publication name.
publication: "2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)"
publication_short: "IROS"

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
# https://arxiv.org/pdf/1911.10269.pdf
links:
- name: code
  url: https://github.com/connorlee77/uav-thermal-water-segmentation
  icon_pack: fab
  icon: github
- name: youtube
  url: https://www.youtube.com/watch?v=SksOtntVplI
  icon_pack: fab
  icon: youtube

# Featured image
image:
  caption: ""
  focal_point: "smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [robotics]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""

---

We present a new method to adapt an RGB-trained water segmentation network to target-domain aerial thermal imagery using online self-supervision by leveraging texture and motion cues as supervisory signals. This new thermal capability enables current autonomous aerial robots operating in near-shore environments to perform tasks such as visual navigation, bathymetry, and fl ow tracking at night. Our method overcomes the problem of scarce and difficult-to-obtain near-shore thermal data that prevents the application of conventional supervised and unsupervised methods. In this work, we curate the first aerial thermal near-shore dataset, show that our approach outperforms fully-supervised segmentation models trained on limited target-domain thermal data, and demonstrate real-time capabilities onboard an Nvidia Jetson embedded computing platform.
