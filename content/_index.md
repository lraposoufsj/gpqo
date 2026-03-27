---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Research Group in
        Organic Chemistry (GPQO)
      image:
        filename: banner.jpg
      text: |
        <br>
        The <b>GPQO</b> is based at the Federal University of São João del-Rei (UFSJ), Brazil.
        Our work focuses on organic synthesis, medicinal chemistry, and the development
        of new synthetic methodologies.
        <br><br>
        {{% cta cta_link="./people/" cta_text="Meet the group →" %}}
      design:
        background:
          color: black
          text_color_light: true
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
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

  - block: portfolio
    content:
      title: Research Projects
      subtitle:
      text:
      filters:
        folders:
         - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Fluorination
          tag: Fluorination
        - name: Catalysis
          tag: Catalysis
        - name: Synthesis
          tag: Synthesis
      design:
        columns: '2'
        view: card
        flip_alt_rows: true
  
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#          brightness: 1
#         parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen

  - block: collection
    content:
      title: Recent Publications
      text: 
      count: 5
      filters:
        folders:
          - publication
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: citation
      columns: '1'

  - block: people
    content: 
      title: The Group
      subtitle:
      text:
      user_groups:
        - Principal Investigators
        - Postdoctoral Investigators
        - PhD Students
        - MSc Students
        - Undergraduate Students
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: contact
    content:
      title: Contact
      subtitle: 
      contact_links:
        - icon: envelope
          icon_pack: fas
          name: Marcelo Siqueira Valle
          link: 'mailto:marcelovalle@gmail.com'
        - icon: envelope
          icon_pack: fas
          name: Lucas Raposo Carvalho
          link: 'mailto:lraposo@ufsj.edu.br'
      address:
        street: Campus Dom Bosco - Praça Dom Helvécio, 74 - Fábricas
        city: São João del-Rei
        region: MG
        postcode: '36301-160'
        country: Brazil
        country_code: BR
      autolink: true
    design:
      columns: '2'

#  - block: markdown
#    content:
#      title:
#      subtitle:
#      text: |
#        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
#    design:
#      columns: '1'
---
