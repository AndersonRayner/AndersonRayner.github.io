---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "MAGIC-VFM - Meta Adaptive Control for Ground Vehicles with Visual Foundation Models"
authors: [ 'Elena Sorina Lupu', 'Fengze Xie', 'James A. Preiss', 'Matthew Anderson', 'Jedidiah Alindogan', 'Soon-Jo Chung' ]
date: 2024-01-24
#doi: "10.2514/6.2021-1409"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-12-20

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Robotics"
publication_short: "TRO"

abstract: "Planning and control of ground vehicles are challenging because of complex dynamic interactions with the terrain.  Therefore, accurate modeling of terrain interaction forces is important to optimize their driving performance.  We present an offline meta-learning algorithm to construct a rapidly-tunable model of residual dynamics and disturbance using both visual foundation models and vehicle states.  This model is then integrated with composite adaptive control for the control matrix to adapt to changes in both the terrain and vehicle dynamics conditions in real time.  We provide mathematical guarantees of stability and robustness for this controller that provides rapid adaptation for the last layer of the deep neural network, which encodes the terrain disturbance.  The effectiveness of our meta-adaptive algorithm is demonstrated through results of simulation and experimentation using a tracked vehicle.  In particular, the experimental results show its superior performance outdoors on different slopes with varying slippage and track degradation disturbances.  We also compare our controller against an adaptive controller that does not use the visual foundation model terrain features, 
thereby showing significant improvement over the baseline in both hardware experimentation and simulation."

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
url_pdf:
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
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
slides: ""
---
