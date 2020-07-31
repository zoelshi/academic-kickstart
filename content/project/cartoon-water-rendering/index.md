---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Cartoon Water Rendering"
summary: ""
authors: []
tags: []
categories: ["rendering", "C-plus-plus"]
date: 2020-07-31T17:37:56+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# Cartoon Water
This project is an implementation of modified **Cartoon Water Rendering with Foam and Surface Smoothing[2]** using OpenGL and **Position Based Fluids[1]** written in CUDA

## Features
**Techniques**
- Imcompressible fluids simulation using Macklin[1].
- Cartoon water rendering[2].
- Screen space surface reconstruction based on Laan[3]. 
- Surface smoothed by applying bilateral filter on depth texture.
- GPU particle neighbor searching using Green[4].

## Dependencies
- CUDA 10.2
- Visual Studio 2017 \
- GPU and driver support OpenGL 4.6


## References
[1] M. Macklin, M. Müller, Position based fluids, ACM Trans. Graph. 32 (2013) 1–5. https://doi.org/10.1145/2461912.2461984. \
[2] L.D.S.R. Neto, A.L. Apolinário, Cartoon Water Rendering with Foam and Surface Smoothing, Brazilian Symp. Games Digit. Entertain. SBGAMES. 2014-December (2014) 230–239. https://doi.org/10.1109/SBGAMES.2014.25. \
[3] W.J. Van Der Laan, S. Green, M. Sainz, Screen space fluid rendering with curvature flow, Proc. I3D 2009 2009 ACM SIGGRAPH Symp. Interact. 3D Graph. Games. 1 (2009) 91–98. https://doi.org/10.1145/1507149.1507164. \
[4] S. Green, “Particle Simulation using CUDA,” cse.uaa.alaska.edu, no. September, pp. 1–12, 2013. \