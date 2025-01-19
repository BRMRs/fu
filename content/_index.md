---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: li-yang-5h_dMuX_7RE-unsplash.webp
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "15"
          description: |
            Publications
        - statistic: "1,000+"
          description: |
            Citations
        - statistic: "78"
          description: |
            h-index
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        Jie Fu (付杰) is a happy and funny research scientist at Shanghai AI Lab (上海人工智能实验室), chasing his [human-centered](https://intelligence.org/summary/) big AI dream[^1]. 
        - **Automated Methematical Reasoning with Deep Learning and Formal Methods**: reinforcement learning ([ICML 24'](https://openreview.net/forum?id=PSQ5Z920M8)), meta learning ([ICLR 24'](https://arxiv.org/abs/2311.04661)), reasoning ([arXiv 23'](https://arxiv.org/abs/2312.11562)), deep learning ([NAACL 24'](https://aclanthology.org/2024.naacl-long.144/)), etc.
    
        - **Applications**: Safe AI ([arXiv 23'](https://arxiv.org/abs/2310.19852)), multi-modal learning ([arXiv 24'](https://arxiv.org/abs/2406.06462)), multi-modal embodied intelligence ([CoRL 23'](https://proceedings.mlr.press/v205/kang23a.html)), AI for science ([Nature Biotechnology 24'](https://www.nature.com/articles/s41587-024-02241-z)), etc.
    design:
      columns: '1'
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ["25px", "0", "25px", "0"]
  - block: collection
    content:
      title: Research Projects
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: project
      # Choose how many pages you would like to display (0 = all pages)
      count: 1
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    content:
      title: Selected Publications
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: publication
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
