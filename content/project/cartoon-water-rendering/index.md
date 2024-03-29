---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Cartoon Water Rendering"
summary: "Real-Time fluid simulation and cartoon rendering"
authors: []
tags: ["Cpp", "rendering", "simulation"]
categories: ["rendering", "simulation"]
#date: 2020-06-16T14:37:56+08:00
lastmod: 2020-06-16T14:37:56+08:00

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
url_slides: "https://zhuanlan.zhihu.com/p/165653176"
url_video: "https://zhuanlan.zhihu.com/p/165653176"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The project is an implementation of modified **Cartoon Water Rendering with Foam and Surface Smoothing[1]** using OpenGL. And the physical simulation of liquid is based on **Position Based Fluids[2]** written in CUDA.

## Technical Introduce
https://zhuanlan.zhihu.com/p/165653176

## Dependencies
- CUDA 10.2
- Visual Studio 2017
- GPU and driver support OpenGL 4.6

## Run the Demo
keyboard shortcut
1. `spacebar`, Run the demo or Stop at some frame.
2. `m`, Sweep the box boundary or Stop the moving boundary.
3. And you can use mouse to adjust the camera's position or direction.

## Features
- Imcompressible fluids simulation based on PBD[2].
- Screen space surface reconstruction based on point splatting[3]. 
- Cartoon water rendering[1].
- GPU particle neighbor searching using Hash table[5].

## Gallery
![](img/sweep0.png)
![](img/sweep2.png)
![](img/sweep3.png)

## References
[1] L.D.S.R. Neto, A.L. Apolinário, Cartoon Water Rendering with Foam and Surface Smoothing, Brazilian Symp. Games Digit. Entertain. SBGAMES. 2014-December (2014) 230–239. https://doi.org/10.1109/SBGAMES.2014.25. \
[2] M. Macklin, M. Müller, Position based fluids, ACM Trans. Graph. 32 (2013) 1–5. https://doi.org/10.1145/2461912.2461984. \
[3] W.J. Van Der Laan, S. Green, M. Sainz, Screen space fluid rendering with curvature flow, Proc. I3D 2009 2009 ACM SIGGRAPH Symp. Interact. 3D Graph. Games. 1 (2009) 91–98. https://doi.org/10.1145/1507149.1507164. \
[4] D. Wolff, OpenGL 4.0 Shading Language Cookbook. Packt Publishing, Jul. 2011. \
[5] S. Green, “Particle Simulation using CUDA,” cse.uaa.alaska.edu, no. September, pp. 1–12, 2013. \
[6] OpenGL Projection Matrix http://www.songho.ca/opengl/gl_projectionmatrix.html