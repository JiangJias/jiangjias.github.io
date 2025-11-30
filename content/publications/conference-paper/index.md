---
title: 'APP-Miner: Detecting API Misuses via Automatically Mining API Path Patterns'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Robert Ford

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-09-05T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: Extracting API patterns from the source code has been extensively employed to detect API misuses. However, recent studies manually provide pattern templates as prerequisites, requiring prior software knowledge and limiting their extraction scope. This paper presents APP-Miner (API path pattern miner), a novel static analysis framework for extracting API path patterns via a frequent subgraph mining technique without pattern templates. The critical insight is that API patterns usually consist of APIs’ data-related operations and are commonplace. Therefore, we define API paths as the control flow graphs composed of APIs’ data-related operations, and thereby the maximum frequent subgraphs of the API paths are the probable API path patterns. We implemented APP-Miner and extensively evaluated it on four widely used open-source software: Linux kernel, OpenSSL, FFmpeg, and Apache httpd. We found 116, 35, 3, and 3 new API misuses from the above systems, respectively. Moreover, we gained 19 CVEs.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - API Misuse
  - Specification Inference
  - Control Flow Graph
  - Frequent Subgraph Mining
  - Static Analysis

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/SP54263.2024.00043

# Custom links
links:
  - type: pdf
    url: ""
  - type: code
    url: https://github.com/JiangJias/APP-Miner
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  - type: video
    url: https://www.youtube.com/watch?v=7YgqAM2LTbQ&list=PL0pRF4xvoD0kKDUYKpKpbOiVipYN2gmS0&index=180&t=14s

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
