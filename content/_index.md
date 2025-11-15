---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
      #  <h1 style="text-align: center; font-size: 2rem;">MICCAI RISE group</h1>
      #image:
      #  filename: RISE-MICCAI-logo2.jpg
      text: |
        <div style="text-align: center;">
          <img src="images/RISE-MICCAI-logo2.jpg" alt="MICCAI RISE Logo" style="max-width: 300px; width: 100%; display: inline-block;" />
        </div>

        <h2 style="font-size: 1.6rem; font-weight: bold;">Why RISE?</h2>
        <ul>
          <li>Researchers of under-represented origins (Africa, Latin America, South/South-East Asia, and the Middle East) who work in Medical Image Computing and Computer-Aided Interventions (MICCAI) are barely represented in the community (~2% at MICCAI 2020).</li>
          <li>Strengthen the presence of minority researchers from Low-to-Middle Income Countries (LMIC) in MICCAI.</li>
          <li>Build collaborative bridges across countries and co-develop international cutting-edge research projects in medicine with global outreach and impact.</li>
        </ul>

        <h2 style="font-size: 1.6rem; font-weight: bold;">Mission Statement</h2>
        <ul>
          <li>Propel inclusiveness and geographic diversity within MICCAI,</li>
          <li>Strengthen the presence of minority researchers in LMICs,</li>
          <li>Empower MICCAI researchers in LMICs,</li>
          <li>Pave the way for future research stars in LMICs and under-represented communities,</li>
          <li>Build a strong research network across continents to reduce global disparities in health and imaging.</li>
        </ul>

  - block: people
    content:
      title: Meet the RISE Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - RISE Current Board
          - RISE Past Board
      sort_by: Params.weight
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  
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
  
  #- block: markdown
  #  content:
  #    title: title
  #    subtitle: 'Sub title'
  #    text: Some text
  #  design:
  #    columns: '1'
  #    background:
  #      image: 
  #        filename: coders.jpg
  #        filters:
  #          brightness: 1
  #        parallax: false
  #        position: center
  #        size: cover
  #        text_color_light: true
  #    spacing:
  #      padding: ['20px', '0', '20px', '0']
  #    css_class: fullscreen

  - block: collection
    content:
      title: Latest Journal Club
      text: ""
      count: 2
      filters:
        folders:
          - publication
      #  publication_type: 'article'
    design:
      view: citation
      columns: '2'

  #- block: markdown
  #  content:
  #    title:
  #    subtitle:
  #    text: |
  #      {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #  design:
  #    columns: '2'

  - block: markdown
    content:
      text: |
        <script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=1jqmpZjs6GA67LNyyDnP3KRXgVoM0XaMtOGZF3NKH1g&cl=ffffff&w=a"></script>
    design:
      columns: '1'
---
