---
title: "Joint Carbon-Latency Optimization for Online Service Function Chain Deployment"
authors:
- Yung-Lun Yang
- admin
- Li-Hsing Yen
date: "2025-12-08T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *2025 IEEE Global Communications Conference*
publication_short: In *GLOBECOM 2025*

abstract: Service function chain (SFC) deployment is to embed virtualized network function (VNF) instances into a cloud-based infrastructure and chain them in sequence to provide a specific network service. Many approaches have been proposed for SFC deployments with diverse objectives. However, no SFC deployment approach factors in the embodied and operational carbon emissions, which are complicated by location- and time-varying carbon intensity (CI) and the amortization of carbon footprint among SFCs when they share VNF instances and communication links. Moreover, prioritizing lower carbon emissions for an SFC might degrade its end-to-end latency and vice versa. This work aims to jointly minimize carbon emissions and latency in SFC deployment, factoring in 1) SFC lifetime, traffic rates, and resource usage, 2) amortized embodied and operational carbon emissions, and 3) processing and propagation delay. We propose a rule to amortize the carbon footprint to SFCs and an SFC deployment algorithm based on Monte Carlo Tree Search (MCTS) with a time-series forecasting method to predict spatial and temporal fluctuations of CIs. Simulations based on real-world historical CI data and dynamic SFC arrivals and departures confirm the effectiveness of the proposed approach.

# Summary. An optional shortened abstract.
summary: We propose a rule to amortize the carbon footprint to SFCs and an SFC deployment algorithm based on Monte Carlo Tree Search (MCTS) with a time-series forecasting method to predict spatial and temporal fluctuations of CIs.

tags:
- SFC
- Sustainability
- NFV
- Resource Management

featured: false

hugoblox:
  ids: 
    doi: 10.1109/GLOBECOM59602.2025.11432042

links:
- type: pdf
  url: YCYGLOBECOM25.pdf
# - type: preprint
#  provider: arxiv
#  id: 1512.04133v1
# - type: code
#  url: https://github.com/HugoBlox/hugo-blox-builder
- type: slides
  url: https://docs.google.com/presentation/d/1UTRFrYOpwnVUw42tF5p77NgMZiSwf_6n/edit?usp=drive_link&ouid=112463056428975256886&rtpof=true&sd=true
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
