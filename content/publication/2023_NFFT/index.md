---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Learning-based Minimally-Sensed Fault-Tolerant Adaptive Flight Control"
authors: ['Michael O’Connell', 'Joshua Cho', 'Matthew Anderson', 'Soon-Jo Chung']
date: 2023-12-18
#doi: "10.2514/6.2021-1409"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-04-30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Robotics and Automation Letters"
publication_short: "RA-L"

abstract: "This paper presents a novel sparse failure identification method along with rapid control reconstitution using deep neural networks for detecting and compensating for motor failures in multirotor aircraft. The presented method leverages a reformulation of the Neural-Fly online adaptation algorithm and a unique control allocation update approach to prevent motor saturation and improve tracking performance in the presence of modeling errors and actuator faults. Experimental fl ight results demonstrate the ability of the method to maintain control of an aircraft by isolating motor failures and reallocating control in under one second, whilst also reducing the trajectory tracking error by 48 % compared to the baseline. When direct motor speed sensing is available, the proposed allocation algorithm and control architecture enables almost instantaneous failure compensation. The fi ndings of this study contribute to the development of robust fault detection and compensation strategies for over-actuated aircraft, enhancing aircraft safety and reliability in a wide range of applications."

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
url_video: https://www.youtube.com/watch?v=5mpEVbIzybM

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
projects: [aero]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
