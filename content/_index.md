---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        MICCAI RISE group
      image:
        filename: RISE-MICCAI-logo2.jpg
      text: |
        - # Why RISE?
            - Researchers of under-represented origins (Africa, Latin America, South/South-East Asian, and Middle-East) who work in the field of Medical Image Computing and Computer-Aided 
            - Interventions (MICCAI) are barely represented in the community (~around 2% participation to MICCAI 2020).
            - Strengthen the presence of minority researchers from Low-to-Middle Income Countries (LMIC) in MICCAI.
            - Build collaborative bridges across countries and co-develop international cutting-edge research projects in medicine with a wider global outreach and impact.

        - # Mission Statement
            - Propel inclusiveness and geographic diversity within MICCAI,
            - Strengthen the presence of minority researchers in Low-to-Middle Income Countries (LMICs) at MICCAI,
            - Empower MICCAI researchers in LMICs,
            - Pave the way for future research stars to rise in LMICs and under-represented communities, and
            - Build a strong research network within LMICs as well as across continents and different parties to help reduce global disparities in health and imaging.


  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title: title
      subtitle: 'Sub title'
      text: Some text
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '2'
---
