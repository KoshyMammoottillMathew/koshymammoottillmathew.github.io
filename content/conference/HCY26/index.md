---
title: "Mobility-Aware Semi-Synchronous Hierarchical Federated Learning for Internet of Vehicles"
authors:
- Zih-Heng Huang
- admin
- Li-Hsing Yen
date: "2026-09-15T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Intelligent Transportation Systems Conference 2026*
publication_short: In *ITSC 2026*

abstract: Hierarchical Federated Learning (HFL) is well-suited to the Internet of Vehicles (IoV), as it mitigates communication bottlenecks and addresses the challenges of spatially non-independent and identically distributed (non-IID) datasets through edge-based client (vehicle) selection and model aggregation. However, traditional fully synchronous aggregation protocols struggle with vehicle heterogeneity, while asynchronous methods often suffer from instability during training and excessive communication costs. Furthermore, existing client selections typically preclude high-mobility vehicles, thereby underutilizing their potential to mitigate non-IID effects. To address these limitations, we propose an adaptive semi-synchronous HFL architecture. Unlike static approaches, our alternating reinforcement learning framework adaptively manages the degree of semi-synchrony at each edge server and jointly employs a client-selection mechanism that leverages heterogeneity context, such as mobility and computational capability, derived from vehicle microscopic features to ensure robust and efficient HFL training. Simulations with SUMO-controlled vehicle mobility confirm robust convergence and demonstrate higher accuracy and lower global training loss than counterparts.

# Summary. An optional shortened abstract.
summary: our alternating reinforcement learning framework adaptively manages the degree of semi-synchrony at each edge server and jointly employs a client-selection mechanism that leverages heterogeneity context, such as mobility and computational capability, derived from vehicle microscopic features to ensure robust and efficient HFL training.

tags:
- HFL
- IoV
- RL

featured: false

hugoblox:
  ids: 
    doi: ""

links:
- type: pdf
  url: HCYITSC26.pdf
# - type: preprint
#  provider: arxiv
#  id: 1512.04133v1
# - type: code
#  url: https://github.com/HugoBlox/hugo-blox-builder
- type: slides
  url: ""
# - type: dataset
#  url: "#"
# - type: poster
#  url: "#"
# - type: source
#  url: "#"
# - type: video
#  url: https://youtube.com
#- type: custom
#  label: Custom Link
#  url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
<!--
This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
-->
