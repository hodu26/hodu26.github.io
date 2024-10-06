---
widget: slider  # Use the Slider widget as this page section
weight: 1000  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '250px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 5000

content:
  slides:
    - title: Project 1 | 나의 해방 일기
      content: 'Closed SNS using Kobert and LLM, Emotional Diary Application/Web'
      align: center
      background:
        position: right
        color: '#ffffff'
        brightness: 0.7
        media: project/capstone.png
        fit: cover
    - title: Project 2 | 호남人
      content: 'A Dart Improvisational Travel Platform for the Revival of the Tourism Industry in Honam Region'
      align: left
      background:
        position: center
        color: '#ffffff'
        brightness: 0.7
        media: project/oasis.png
        fit: cover
    - title: Project 3 | Secret Of Ghost
      content: 'A horror game played against the backdrop of Jeonbuk National University'
      align: right
      background:
        position: center
        color: '#ffffff'
        brightness: 0.7
        media: project/java-game.png
        fit: cover
      link:
        icon: circle-plus
        icon_pack: fas
        text: More
        url: ../project/
---