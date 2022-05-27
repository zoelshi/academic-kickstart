---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-Reconstruction from Points Cloud by Using a Modified Vector-Valued Allen–Cahn Equation"
authors: ["Jin Wang", "Zhengyuan Shi"]
date: 
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: 2020-07-31T21:55:15+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Mathematics"
publication_short: ""

abstract: "The Poisson surface reconstruction algorithm has become a very popular tool of reconstruction from point clouds. If we reconstruct each region separately in the process of multi-reconstruction, then the reconstructed objects may overlap with each other. In order to reconstruct multicomponent surfaces without self-intersections, we propose an efficient multi-reconstruction algorithm based on a modified vector-valued Allen–Cahn equation. The proposed algorithm produces smooth surfaces and closely preserves the original data without self-intersect. Based on operator splitting techniques, the numerical scheme is divided into one linear equation and two nonlinear equations. The linear equation is discretized using an implicit method, and the resulting discrete system of equation is solved by a fast Fourier transform. The two nonlinear equations are solved analytically due to the availability of a closed-form solution. The numerical scheme has merit in that it can be straightforwardly applied to a graphics processing unit, allowing for accelerated implementation that performs much faster than central processing unit alternatives. Various experimental, numerical results demonstrate the effectiveness and robustness of the proposed method."

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

url_pdf: https://doi.org/10.3390/math9121326
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
