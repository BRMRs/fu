---
title: "Stacking Your Transformers: A Closer Look at Model Growth for Efficient LLM Pre-Training"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Wenyu Du
- Tongxu Luo
- Zihan Qiu
- Zeyu Huang
- Yikang Shen
- Reynold Cheng
- Yike Guo
- Jie Fu
author_notes:
- 
-
-
-
-
-
-
- "Corresponding Author"


date: "2024-05-306T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: LLMs are computationally expensive to pre-train due to their large scale. Model growth emerges as a promising approach by leveraging smaller models to accelerate the training of larger ones. However, the viability of these model growth methods in efficient LLM pre-training remains underexplored. This work identifies three critical obstacles. (O1) lack of comprehensive evaluation, (O2) untested viability for scaling, and (O3) lack of empirical guidelines. To tackle O1, we summarize existing approaches into four atomic growth operators and systematically evaluate them in a standardized LLM pre-training setting. Our findings reveal that a depthwise stacking operator, called Gstack, exhibits remarkable acceleration in training, leading to decreased loss and improved overall performance on eight standard NLP benchmarks compared to strong baselines. Motivated by these promising results, we conduct extensive experiments to delve deeper into Gstack to address O2 and O3. For O2 (untested scalability), our study shows that Gstack is scalable and consistently performs well, with experiments up to 7B LLMs after growth and pre-training LLMs with 750B tokens. For example, compared to a conventionally trained 7B model using 300B tokens, our Gstack model converges to the same loss with 194B tokens, resulting in a 54.6\% speedup. We further address O3 (lack of empirical guidelines) by formalizing guidelines to determine growth timing and growth factor for Gstack, making it practical in general LLM pre-training. We also provide in-depth discussions and comprehensive ablation studies of Gstack. Our code and pre-trained model are available at https://llm-stacking.github.io/.

# Summary. An optional shortened abstract.
summary: NeurIPS 2024 **Spotlight**



tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: https://arxiv.org/abs/2405.15319
- name: Website
  url: https://llm-stacking.github.io/
- name: Twitter
  url: https://x.com/_akhaliq/status/1794938544336568380
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
