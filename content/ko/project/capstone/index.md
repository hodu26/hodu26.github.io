---
title: 캡스톤 프로젝트 [가온 - 나의 해방 일기]
summary: Kobert와 LLM을 활용한 폐쇄형 SNS, 감정일기 애플리케이션
tags:
  - app
  - JBNU
  - container
  - React
  - Nest.js
  - Typescript
  - LLM
  - Kobert
date: 2024-09-10

image:
  placement: 1
  caption: "Capstone banner image by gaon"
  focal_point: "Center"
  preview_only: true
  alt_text: Capstone banner image
  filename: project/capstone.png  # Uncomment to load an image from `assets/media/` instead.

banner: 
  image: project/capstone.png
  caption: "Capstone banner image by gaon"

links:
  - icon: github
    icon_pack: fab
    name: github
    url: http://github.com/capstone-gaon
  - icon: book-bookmark
    icon_pack: fas
    name: Notion
    url: https://www.notion.so/66072a3361bf44c5a2351b7f428f9874
  - icon: figma
    icon_pack: fab
    name: Figma
    url: https://www.figma.com/files/team/1416687740278102546/project/277608999/Capstone?fuid=1398959164732687467
  - icon: 
---


## 1. 소개
SNS의 확산으로 인해 타인과 비교하는 문화가 확산되어 우을증이 심화됨에 따라,    
SNS의 부작용을 줄이고자 폐쇄형 SNS인 감정일기 플랫폼을 개발

## 2. 목차
- [프로젝트 개요](#프로젝트-개요)
- [기술 스택](#기술-스택)
- [주요 기능](#주요-기능)
- [문제 해결](#문제-해결)
- [향후 계획](#향후-계획)
- [참고 자료](#참고-자료)

## 3. 프로젝트 개요
이 프로젝트는 **애플리케이션**을 통해 우을증 위헝이 있는 사람들에게    
**폐쇄형 SNS**를 제공한다.

## 4. 기술 스택
프로젝트에 사용된 주요 기술 스택을 나열합니다.
- **프론트엔드**: React (TypeScript), Expo
- **백엔드**: Nest.js
- **데이터베이스**: PostgreSQL
- **기타**: Docker, Jenkins ...

## 5. 주요 기능
- **회원 가입 및 로그인**
- **일기 작성 및 분석**
- **Kobert와 LLM을 사용한 감정 분석 및 조언 제공**

## 6. 문제 해결
- LLM 응답 속도가 매우 느려 GPU 서버 확보 및 **모델 양자화**를 통하여 해결

## 7. 향후 계획
지속적인 Kobert 및 LLM 파인튜닝 및 UI/UX 개선 ... 

## 8. 참고 자료
- [ERD](https://www.erdcloud.com/d/D32QknBQnHz4nqA3X)
