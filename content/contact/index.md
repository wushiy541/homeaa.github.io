---
title: Contact
date: 2022-10-24

type: landing
sections:
  - block: contact
    content:
      title: Contact
      text: |-
        欢迎成绩优异、有良好反思与自我管理能力的学生加入我们团队。
      email: lbzhang@swu.edu.cn
      address:
        street: 天生路2号
        city: 重庆
        postcode: '400715'
        country: 中国
      coordinates:
        latitude: '29.828845'
        longitude: '106.434215'
      directions: 导航西南大学出版社大楼即可
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
