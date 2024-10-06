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
    - title: 프로젝트 1 | 나의 해방 일기
      content: 'Kobert와 LLM을 활용한 폐쇄형 SNS, 감정일기 애플리케이션/웹'
      align: center
      background:
        position: right
        color: '#ffffff'
        brightness: 0.7
        media: project/capstone.png
        fit: cover
    - title: 프로젝트 2 | 호남人
      content: '호남지역의 관광 산업 부흥을 위한 다트 즉흥 여행 플랫폼'
      align: left
      background:
        position: center
        color: '#ffffff'
        brightness: 0.7
        media: project/oasis.png
        fit: cover
    - title: 프로젝트 3 | Secret Of Ghost
      content: '전북대를 배경으로 진행되는 공포게임'
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