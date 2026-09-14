---
title: "Dynamic Carbon-Aware Hybrid Task Offloading for Collaborative Edge-Cloud Computing"
authors:
- Pin-Chun Chen
- Li-Hsing Yen
- admin
- Ze-Yu Jin
- Chien-Chao Tseng
date: "2026-04-08T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-01-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Wireless Communications and Networking Conference 2026*
publication_short: In *WCNC 2026*

abstract: Collaborative edge-cloud computing is an emerging paradigm that balances processing efficiency and user experience by offloading edge workloads to the cloud (i.e., vertical offload- ing). Adding the option of horizontal offloading (i.e., edge-to-edge offloading) can further enhance the flexibility of this architecture. However, prior work ignored temporal and spatial variations in carbon emissions when making offloading decisions. Our study aims to jointly optimize the carbon footprint and the balance of edge servers’ workloads, which is challenged by dynamic workload arrivals to edge servers and time-and-location-varying carbon intensity (CI). We propose an online algorithm Lyapunov optimization framework to configure offloading workload and transmission power for mixed vertical and horizontal offloading. Simulations based on historical CI data reveal that the proposed algorithm can efficiently reduce carbon footprint while balancing queue backlogs among edge and cloud servers.

# Summary. An optional shortened abstract.
summary: Our study aims to jointly optimize the carbon footprint and the balance of edge servers’ workloads, which is challenged by dynamic workload arrivals to edge servers and time-and-location-varying carbon intensity (CI). We propose an online algorithm Lyapunov optimization framework to configure offloading workload and transmission power for mixed vertical and horizontal offloading.

tags:
- MEC
- Sustainability
- Resource Management
- Optimization

featured: false

hugoblox:
  ids: 
    doi: 10.1109/WCNC65185.2026.11555269

links:
- type: pdf
  url: CYC+WCNC26.pdf
# - type: preprint
#  provider: arxiv
#  id: 1512.04133v1
# - type: code
#  url: https://github.com/HugoBlox/hugo-blox-builder
- type: slides
  url: https://docs.google.com/presentation/d/1pYvnxOl970naLIADFWumFNixp66kmgim/edit?usp=drive_link&ouid=112463056428975256886&rtpof=true&sd=true
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
