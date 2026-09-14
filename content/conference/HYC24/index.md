---
title: "CNN Inference Workload Distribution Considering Accumulative Effect of Receptive Fields"
authors:
- I-Ting Ho
- Li-Hsing Yen
- admin
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-10-24T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *2024 International Computer Symposium*
publication_short: In *ICS 2024*

abstract: Operating an artificial intelligence and machine learning (AI/ML) model requires significant computing power, posing a substantial challenge for edge devices with limited resources. A potential way to accelerate the operations is to distribute the workload to multiple collaborative devices. For the inference using a convolutional neural network (CNN), the workload distributed is complicated by the overlapping input tensors among workers due to the accumulative effect of receptive fields (AERF). This factor incurs extra communication time, which was overlooked by prior studies. In this paper, we propose an approach to CNN inference time minimization by aggregating the inference workload distributed to multiple heterogeneous computing devices. Our result shows a 10% speed-up against the benchmark.

# Summary. An optional shortened abstract.
summary: In this paper, we propose an approach to CNN inference time minimization by aggregating the inference workload distributed to multiple heterogeneous computing devices.

tags:
  - AI
  - CNN
  - Resource Management

featured: false

hugoblox:
  ids:
    doi: 10.1109/ICS64339.2024.00011

links:
  - type: pdf
    url: HYCICS24.pdf
  # - type: code
  #  url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #  url: ""
  # - type: poster
  #  url: ""
  # - type: project
  #  url: ""
  - type: slides
    url: https://docs.google.com/presentation/d/1AqSNfDqD7JGhaRW-bImPQ-1ngwUOoX7u/edit?usp=drive_link&ouid=112463056428975256886&rtpof=true&sd=true
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
