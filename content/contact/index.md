---
title: Contact
date: 2024-07-23

type: landing

sections:
  - block: contact
    content:
      title: Get in Touch with Netgroup
      text: |-
        At the Netgroup, part of the School of Computing at the University of Nebraska-Lincoln, we are dedicated to advancing the field of networking through innovative research. Our team focuses on designing efficient, scalable, reliable, and secure network architectures and systems. Whether you’re interested in Optical Networks, Peer-to-Peer Networks, Software-Defined Networks, or Network Security, we welcome collaborations and inquiries. Contact us today to explore opportunities in networking research and innovation. 
        
        Feel free to adjust any details to better match the tone or specific details you’d like to emphasize!

      email: byrav@cse.unl.edu
      phone: 888 888 88 88
      address:
        street: 114A Schorr Center, 1100 T St
        city: Lincoln
        region: NE
        postcode: '68588'
        country: United States
        country_code: US
      coordinates:
        latitude: '40.8198'
        longitude: '-96.7056'
      directions: Enter the Building and turn right to the hallway. Office 114A on Floor 1.
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      #appointment_url: ''
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
