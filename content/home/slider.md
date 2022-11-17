---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '300px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Welcome to our group
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: tour.jpg
    - title: Learn
      content: 'Abstract from a lab member (To change every X months) '
      align: right
      background:
        position: right
        color: '#555'
        brightness: 0.7
        media: learn.jpg
    - title: News IUS 2022
      content: 'Take a look at our latest group news'
      align: right
      background:
        position: right
        color: '#333'
        brightness: 0.7
        max-width: 50%;
        media: news.jpg
      link:
        icon:
        icon_pack: fas
        text: News
        url: ../post/  
    - title: New position available!
      content: 'Description ........'
      align: left
      background:
        position: center
        color: '#333'
        max-width: 50%;
        brightness: 0.5
        media: hiring.jpg    
      link:
        icon: 👉
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
