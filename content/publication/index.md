---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        BoGuan Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **BoGuan Team** has been a center of excellence for research, teaching, and practice in E-cargo, deep learning, and large language models since its founding in 2019 at Southwest University.
  - block: hero
    title: 张里博简介
    image: avatar.jpg     # 头像路径，如果有可替换
    name: 张里博
    role: 副教授
    organization: 西南大学 人工智能学院
    org_url: https://ai.swu.edu.cn/
    email: lbzhang@swu.edu.cn
    bio: 研究方向包括分布式机器人、移动计算和可编程物质。
    interests:
      - 大模型
      - 深度学习
      - LDM
      - E-cargo
    education:
      - degree: 副教授
        period: 2023.07至今
        school: 西南大学人工智能学院
      - degree: 讲师
        period: 2019.07–2023.06
        school: 西南大学人工智能学院
      - degree: 硕博连读（导师：周献中、李华雄）
        period: 2013.09–2019.03
        school: 南京大学工程管理学院
      - degree: 学士
        period: 2009.09–2013.06
        school: 浙江工业大学理学院
      - degree: 访问学者（导师：Lexing Xie、Chritian Walder）
        period: 2017.02–2018.02
        school: 澳大利亚国立大学工程与计算机学院
    social:
      - icon: envelope
        icon_pack: fas
        link: mailto:lbzhang@swu.edu.cn
      - icon: google-scholar
        icon_pack: ai
        link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
      - icon: github
        icon_pack: fab
        link: https://scholar.google.com/citations?user=8I-krtYAAAAJ&hl=zh-CN&oi=ao
  - block: collection
    content:
      title: 论文
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'
  
  - block: collection
    content:
      title: 竞赛
      text: ""
      count: 5
      filters:
        folders:
          - publication
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
