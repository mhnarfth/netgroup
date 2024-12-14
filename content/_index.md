---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        
      image:
        filename: welcome.png
        
      text: |
        <br>
        
        The **Netgroup** at the School of Computing at University of Nebraska-Lincoln, works on broad areas of Networking research with focus on creating and building efficient, scalable, reliable, secure and cost-effective architectures and systems. Netgroup is working on a wide range of projects in the areas Networking and Security, with application to Optical Networks and Grids, Peer-to-Peer Networks, Software-Defined Networks, Wireless and Sensor Networks, Satellite Networks Network Security, and Secure Group Communication.
        
  
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
      page_type: news
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: ''
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
        publication_types: 'article'
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
