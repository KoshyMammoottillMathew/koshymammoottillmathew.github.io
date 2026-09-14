---
title: 'P4-TINS: P4-Driven Traffic Isolation for Network Slicing With Bandwidth Guarantee and Management'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chi-Yu Li
  - Chien-Chao Tseng
  - Min-Zhi Hu

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-09-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Network and Service Management"
publication_short: "IEEE Trans. Netw. Serv. Manag. (TNSM)"

abstract: Network slicing is an essential technology for 5G mobile networks. It partitions network resource logically into multiple isolated slices, each of which can satisfy a suite of network requirements for one specific service. However, it cannot be fulfilled by the current SDN (Software-Defined Networks), since the conventional SDN data-plane technology, OpenFlow, is not flexible enough to offer fine-grained network resource control or queue/packet scheduling. It leads to many research studies developing corresponding solutions on programmable switches. In this work, we focus on the support of the bandwidth guarantee and management for network slices. Although several studies with the similar goal have been proposed, they do not consider interference among different flow types or use the built-in meter for easy deployment on COTS (Commercial Off-The-Shelf) P4 switches. To this end, we first conduct a case study to examine the interference cases. We then propose a solution, designated as P4-TINS (P4-driven Traffic Isolation for Network Slicing), to resolve the interference by isolating different types of traffic flows in priority queues and set the P4 switch’s bucket size based on the time granularity of its bandwidth management operation. It cannot only ensure the guaranteed bandwidth for each slice but also enable coexistent slices to fairly share residual bandwidth. We have confirmed its effectiveness experimentally based on our prototype over an ONOS (Open Network Operating System) controller and a COTS P4 switch.

# Summary. An optional shortened abstract.
summary: Network slicing is an essential technology for 5G mobile networks. It partitions network resource logically into multiple isolated slices, each of which can satisfy a suite of network requirements for one specific service. However, it cannot be fulfilled by the current SDN. We then propose a solution, designated as P4-TINS (P4-driven Traffic Isolation for Network Slicing).

tags:
  - SDN
  - Networking

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/TNSM.2022.3159232

# Custom links
links:
  - type: pdf
    url: CLT+TNSM22.pdf
  #- type: code
  #  url: ""
  #- type: dataset
  #  url: ""
  #- type: slides
  #  url: ""
  #- type: source
  #  url: ""
  #- type: video
  #  url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""

---
<!--
> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
-->
