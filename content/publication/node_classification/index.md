---
title: "When Do Graph Neural Networks Help with Node Classification: Investigating the Homophily Principle on Node Distinguishability"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sitao Luan
- Chenqing Hua
- Minkai Xu
- Qincheng Lu
- Jiaqi Zhu
- Xiao-Wen Chang
- Jie Fu
- Jure Leskovec
- Doina Precup
author_notes:
-
-
-
-
- 
-
- "Corresponding Author"
-
- 

date: "2023-09-21T01:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-21T01:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS*
publication_short: In *NeurIPS*

abstract: Homophily principle, i.e. nodes with the same labels are more likely to be connected, was believed to be the main reason for the performance superiority of Graph Neural Networks (GNNs) over Neural Networks (NNs) on Node Classification (NC) tasks. Recently, people have developed theoretical results arguing that, even though the homophily principle is broken, the advantage of GNNs can still hold as long as nodes from the same class share similar neighborhood patterns, which questions the validity of homophily. However, this argument only considers intra-class Node Distinguishability (ND) and ignores inter-class ND, which is insufficient to study the effect of homophily. In this paper, we first demonstrate the aforementioned insufficiency with examples and argue that an ideal situation for ND is to have smaller intra-class ND than inter-class ND. To formulate this idea and have a better understanding of homophily, we propose Contextual Stochastic Block Model for Homophily (CSBM-H) and define two metrics, Probabilistic Bayes Error (PBE) and Expected Negative KL-divergence (ENKL), to quantify ND, through which we can also find how intra- and inter-class ND influence ND together. We visualize the results and give detailed analysis. Through experiments, we verified that the superiority of GNNs is indeed closely related to both intra- and inter-class ND regardless of homophily levels, based on which we define Kernel Performance Metric (KPM). KPM is a new non-linear, feature-based metric, which is tested to be more effective than the existing homophily metrics on revealing the advantage and disadvantage of GNNs on synthetic and real-world datasets.

# Summary. An optional shortened abstract.
summary: NeurIPS 2023



tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: https://arxiv.org/abs/2304.14274

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
