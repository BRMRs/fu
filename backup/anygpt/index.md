---
title: "AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jun Zhan
- Junqi Dai
- Jiasheng Ye
- Yunhua Zhou
- Dong Zhang
- Zhigeng Liu
- Xin Zhang
- Ruibin Yuan
- Ge Zhang
- Linyang Li
- Hang Yan
- Jie Fu
- Tao Gui
- Tianxiang Sun
- Yugang Jiang
- Xipeng Qiu
author_notes:
-
- 
-
-
-
-
- 
-
-
-
- 


date: "2024-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: in *ACL*
publication_short: in *ACL*

abstract: Developing a generalist agent is a longstanding objective in artificial intelligence. Previous efforts utilizing extensive offline datasets from various tasks demonstrate remarkable performance in multitasking scenarios within Reinforcement Learning. However, these works encounter challenges in extending their capabilities to new tasks. Recent approaches integrate textual guidance or visual trajectory into decision networks to provide task-specific contextual cues, representing a promising direction. However, it is observed that relying solely on textual guidance or visual trajectory is insufficient for accurately conveying the contextual information of tasks. This paper explores enhanced forms of task guidance for agents, enabling them to comprehend gameplay instructions, thereby facilitating a "read-to-play" capability. Drawing inspiration from the success of multimodal instruction tuning in visual tasks, we treat the visual-based RL task as a long-horizon vision task and construct a set of multimodal game instructions to incorporate instruction tuning into a decision transformer. Experimental results demonstrate that incorporating multimodal game instructions significantly enhances the decision transformer's multitasking and generalization capabilities.

# Summary. An optional shortened abstract.
summary: ACL 2024



tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: https://arxiv.org/abs/2402.12226
- name: Webpage
  url: https://junzhan2000.github.io/AnyGPT.github.io/
- name: Github
  url: https://github.com/OpenMOSS/AnyGPT
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
