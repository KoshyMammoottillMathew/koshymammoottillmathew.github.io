---
title: "P4-Enabled Bandwidth Management"
authors:
- admin
- Li-Hsing Yen
- Wei-Cheng Wang
- 'Cheng-An Chuang'
- Yu-Shen Liu
- Chien-Chao Tseng
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-09-18T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-07T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *2019 20th Asia-Pacific Network Operations and Management Symposium*
publication_short: In *APNOMS 2019*

abstract: As the next generation network is supposed to support diverse service requirements, managing Quality of Service (QoS) is a crucial part of it. QoS guarantees have long been deemed too complicated until the emergence of software-defined networking (SDN) and widely adopted standard OpenFlow. Recently, Programming Protocol-independent Packet Processors (P4) has gained much attention because of its features like programmable data plane and independent protocol and platform. It is anticipated that the high flexibility of P4 can enhance the QoS control for production networks. In this paper, we show a design of bandwidth management for QoS with SDN and P4-programmable switch. The design classifies packets into different categories based on their QoS demands and usages, which are then disaggregated by a two-level priority queue. Experiments with P4 switch shows that the proposed design not only effectively limits the maximum allowed rate but also guarantees the minimum bandwidth of each traffic flow. As such, the design can maximize bandwidth utilization and serves a building block for network slicing.

# Summary. An optional shortened abstract.
summary: In this paper, we show a design of bandwidth management for QoS with SDN and P4-programmable switch.

tags:
  - SDN
  - Networking

featured: false

hugoblox:
  ids:
    doi: 10.23919/APNOMS.2019.8892909

links:
  - type: pdf
    url: CYW+APNOMS19.pdf
  # - type: code
  #  url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #  url: ""
  # - type: poster
  #  url: ""
  # - type: project
  #  url: ""
  - type: slides
    url: https://docs.google.com/presentation/d/1IFwwdnNEOuQuyV_sub_pNLqRo1AWb5iD/edit?usp=sharing&ouid=112463056428975256886&rtpof=true&sd=true
  # - type: source
  #  url: ""
  # - type: video
  #  url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
<!--
> [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images]
(https://docs.hugoblox.com/content/writing-markdown-latex/).
-->
