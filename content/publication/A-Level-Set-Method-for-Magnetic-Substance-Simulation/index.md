---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Level-Set Method for Magnetic Substance Simulation"
authors: [admin, Bo Zhu, Bin Wang, Baoquan Chen]
authors_detailed: ["CFCS, Peking University & AICFVE, Beijing Film Academy", Dartmouth College, "AICFVE, Beijing Film Academy", "CFCS, Peking University & AICFVE, Beijing Film Academy"]
author_notes: ["", "" , corresponding authors, corresponding authors]
date: 2020-07-15T00:00:00+08:00
doi: "10.1145/3386569.3392445"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-19T14:46:14+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*ACM Transactions on Graphics*. 39, 4, Article 29, 15 pages. In *Proceedings of the 47th Annual Conference on Computer Graphics and Interactive
Techniques (SIGGRAPH 2020)*"
publication_short: "*ACM Transactions on Graphics*. 39(4), 1--15"

abstract: "We present a versatile numerical approach to simulating various magnetic phenomena using a level-set method. At the heart of our method lies a novel two-way coupling mechanism between a magnetic field and a magnetizable mechanical system, which is based on the interfacial Helmholtz force drawn from the Minkowski form of the Maxwell stress tensor. We show that a magnetic-mechanical coupling system can be solved as an interfacial problem, both theoretically and computationally. In particular, we employ a Poisson equation with a jump condition across the interface to model the mechanical-to-magnetic interaction and a Helmholtz force on the free surface to model the magnetic-to-mechanical effects. Our computational framework can be easily integrated into a standard Euler fluid solver, enabling both simulation and visualization of a complex magnetic field and its interaction with immersed magnetizable objects in a large domain. We demonstrate the efficacy of our method through an array of magnetic substance simulations that exhibit rich geometric and dynamic characteristics, encompassing ferrofluid, rigid magnetic body, deformable magnetic body, and multi-phase couplings."

# Summary. An optional shortened abstract.
summary: "This paper presents a versatile, numerical approach to simulating various magnetic phenomena using a level-set method, which contains a novel two-way coupling mechanism between a magnetic field and magnetizable objects."

tags: [magnetic simulation, fluid simulation, ferrofluid, level-set method, immersed boundary]
categories: [Physical Simulation]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ACM
  url: https://dl.acm.org/doi/abs/10.1145/3386569.3392445
  icon_pack: ai
  icon: acm

url_pdf: http://vcl.pku.edu.cn/file/upload_file/image/research/att202005141845/A%20Level-Set%20Method%20for%20Magnetic%20Substance%20Simulation.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=0cCJKg3Oa9U

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
