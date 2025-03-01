---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        We are seeking trainees eager to advance the mechanistic understanding of neuro-immune interactions in health and disease, leveraging state-of-the-art technology. Our focus spans neurodevelopmental disorders, neurodegenerative diseases, aging, infectious diseases, autoimmune conditions, and cancer.
      email: lihui.duan@genetics.ac.cn
      phone: +86 (010) 64806596
      address:
        street: No. 1 West Beichen Road, Chaoyang District
        city: Beijing
        region: Beijing
        postcode: '100101'
        country: China
        country_code: CN
      coordinates:
        latitude: '40.00513345058226'
        longitude: '116.38138696768533'
      directions: Enter Building 2 and take the stairs to Office 406 on Floor 4
      office_hours:
        - 'Monday-Friday 09:00 to 17:00'

      #appointment_url: 'https://calendly.com'
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
