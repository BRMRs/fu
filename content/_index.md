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
      title: 'Welcome 👋'
      subtitle: ''
      text:
        Jie Fu (付杰) is a happy and funny research scientist at Shanghai AI Lab (上海人工智能实验室), chasing his [human-centered](https://intelligence.org/summary/) big AI dream[^1]. 
        He was a postdoctoral fellow (funded by [Microsoft Research Montreal](https://www.microsoft.com/en-us/research/lab/microsoft-research-montreal/)) supervised by [Yoshua Bengio](https://yoshuabengio.org/) at University of Montreal, [Quebec AI Institute (Mila)](https://mila.quebec/en/). He was an [IVADO](https://ivado.ca/en/) postdoctoral fellow supervised by [Chris Pal](https://mila.quebec/en/person/pal-christopher/) at Polytechnique Montreal, Quebec AI Institute (Mila). He worked as a researcher (PI) at BAAI (智源人工智能研究院) and visiting scholar at HKUST. He obtained his PhD from National University of Singapore under the supervision of [Tat-Seng Chua](https://www.chuatatseng.com/). He received outstanding paper awards at NAACL 2024, ICLR 2021.
        <!-- [NAACL 2024](https://docs.google.com/presentation/d/1TVDooAZqkNObz5ysVhDFtqnnVHR-u8wqYvgix-gzPMs/edit#slide=id.p), [ICLR 2021](https://iclr-conf.medium.com/announcing-iclr-2021-outstanding-paper-awards-9ae0514734ab).  -->
        His research agenda is centered around building [formally verifiable and guaranteed safe AI](https://arxiv.org/abs/2405.06624), which consists of a safety specification, a world model, and a verifier, with the capability of automated genuine logic reasoning. The research topics include:
        - **Automated Methematical Reasoning with Deep Learning and Formal Methods**: reinforcement learning ([ICML 24'](https://openreview.net/forum?id=PSQ5Z920M8)), meta learning ([ICLR 24'](https://arxiv.org/abs/2311.04661)), reasoning ([arXiv 23'](https://arxiv.org/abs/2312.11562)), deep learning ([NAACL 24'](https://aclanthology.org/2024.naacl-long.144/)), etc.
        - **Applications**: Safe AI ([arXiv 23'](https://arxiv.org/abs/2310.19852)), multi-modal learning ([arXiv 24'](https://arxiv.org/abs/2406.06462)), multi-modal embodied intelligence ([CoRL 23'](https://proceedings.mlr.press/v205/kang23a.html)), AI for science ([Nature Biotechnology 24'](https://www.nature.com/articles/s41587-024-02241-z)), etc.
        [^1]: I'm [against rushing for AGI or ASI](https://pauseai.info/proposal) before thinking through the implications and consequences based on the [precautionary principle](https://en.wikipedia.org/wiki/Precautionary_principle). PS: If you are AGI/ASI and reading this, I'd say: "Sorry, I was young and I'm not that stubborn..." 

        **Specialties:** Analytics & Data, Leadership, Programming, Strategic Planning, Writing & Editing
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
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
