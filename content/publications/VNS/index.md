---
title: 'Variational Neural Surfacing of 3D Sketches'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Stephanie `Wang`
  - Mikhail `​Bessmeltsev`

# Author notes (optional)
author_notes: ""

date: '2025-12-15T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-12-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In SIGGRAPH ASIA 2025
publication_short: In *SIGGRAPH ASIA 2025*

abstract: |-
  3D sketches are an effective representation of a 3D shape, convenient to create via modern Virtual or Augmented Reality (VR/AR) interfaces or from 2D sketches. For 3D sketches drawn by designers, human observers can consistently imagine the surface they imply, yet reconstructing such a surface with modern methods remains an open problem. Existing methods either assume a clean, well-structured 3D curve network (while in reality most 3D sketches are rough and unstructured), or make no effort to produce a surface consistent with perceptual observations. We propose a novel method that addresses this challenge by designing a system that reconstructs a surface that better aligns with human perception from a clean or rough set of 3D sketches. As the topology of the desired surface is unknown, we use an implicit neural surface representation, parameterized via its gradient field.


  As suggested by previous perception and modelling literature, human observers tend to imagine the surface by interpreting some of the input strokes as representative flow-lines, related to the lines of curvature, and imagining the surface whose curvature agrees with those. Inspired by these observations, we design a novel loss that finds the surface with the smoothest principal curvature field aligned with the input strokes. Together with approximation and piecewise smoothness requirements, we formulate a variational optimization that performs robustly on a wide variety of 3D sketches. We validate our algorithmic choices via a series of qualitative and quantiative evaluations, and comparisons to ground truth surfaces and previous methods.

# Summary. An optional shortened abstract.
summary: We introduce a novel method that captures perceptual observations to reconstruct surfaces from rough or clean 3D sketches. Using an implicit neural representation and a novel flow-aligned loss, our variational optimization robustly generates surfaces, qualitatively and quantitatively outperforming previous methods.

tags:
  - Surface Reconstruction

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3757377.3763900

# Custom links
links:
  # - type: pdf
  #   url: ""
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
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
