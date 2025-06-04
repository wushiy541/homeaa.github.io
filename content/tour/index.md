---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to BoGuan
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: E-cargo ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'    
      - title: LDM ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 深度学习 ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 大模型 ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  - block: hero
    content:
      title: |
        BoGuan Group
      image:
        filename: welcome.jpg
      text: |
        The **BoGuan Team** has been a center of excellence for research, teaching, and practice in E-cargo, deep learning, and large language models since its founding in 2019 at Southwest University.
  - block: about.biography
    content:
      title: 导师
      username: 吳恩達
  - block: markdown
    content:
      title: 论文
      text: >
        我的研究主要聚焦于人工智能领域，特别是机器学习和张量计算。以下是我近期的学术成果，涵盖了高维数据处理、多分类算法等前沿研究方向。

  - block: features
    content:
      title: 论文列表
      text: 点击论文标题可查看详细信息
      items:
        - name: "[A low-rank support tensor machine for multi-classification](https://doi.org/10.1016/j.ins.2024.121398)"
          description: "Information Sciences, 2025"
          icon: file-pdf
          icon_pack: fas
          url: "https://doi.org/10.1016/j.ins.2024.121398"
      
        - name: "[分布式机器人协同控制新方法](/papers/robot-control)"
          description: "计算机学报, 2024"
          icon: file-pdf
          icon_pack: fas
          url: "/papers/robot-control"
    design:
      # 强制垂直布局
      columns: '1'
      # 可选：调整卡片样式
      css_class: 'feature-vertical'
  - block: markdown
    content:
      title: 论文列表
      text: |
        ### 2025年
        - [A low-rank support tensor machine for multi-classification](./papers/tensor-machine) - *Information Sciences*
        - 分布式机器人协同控制新方法 - *计算机学报*

        ### 2024年
        - 机器学习新进展 - *人工智能学报*
        - 深度学习算法研究 - *计算机研究与发展*
  - block: collection
    title: 论文1
    text: ""
    count: 99
    filters:
      folders:
         - papers
      publication_type: 'article'
    design:
      view: citation
      columns: '1'
  - block: collection
    title: 竞赛1
    text: "bbbb"
    count: 99
    filters:
      folders:
        - papers
      publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
