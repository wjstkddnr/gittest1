# SKN02-4th-3Team

[<img width="200px" src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"/>](https://modern-carver-7cd.notion.site/RAG-LLM-9c67867d336f4047ac8a26aa9ab9dd83)

#  팀 소개
## :apple: TEAM APPLE (GIVE ME AN APPLE) 
| 구선아 | 김진유 | 전상욱 | 이재원 | 
|:--------------------:|:--------------------:|:--------------------:|:--------------------:|
| <img width="120px" src="https://github.com/user-attachments/assets/c95175c7-22cb-4c1d-b254-eb500b123ec6" /> | <img width="150px" src="https://github.com/user-attachments/assets/4ae67d2a-4394-4481-98d4-266966a517a8" /> | <img width="160px" src="https://github.com/user-attachments/assets/dff45d59-7454-4c0a-9158-b42e0bcde3b3"/> | <img width="150px" src="https://github.com/user-attachments/assets/87680063-4964-411d-94ba-469dbbb4b7e0" /> 
|  [@CAP_KOO](https://github.com/developer0826) | [@ACCUSE_KIM](https://github.com/Sesame-Oil)  | [@SUP_WOOK](https://github.com/wjstkddnr) | [@JAMMANBO_LEE](https://github.com/promethevs11) |


#  프로젝트

## 👨‍🏫 프로젝트 개요
  #### 네이버페이 증권 사이트와 네이버증권 뉴스기사를 10분마다 크롤링하여 저장하고 이를 불러와 GPT4o-mini 모델에 RAG하여 실시간 증권 정보를 제공하는 챗봇
  ## :alarm_clock: 문제인식

  #### 우리나라의 주식투자자 수는 계속 증가해오고 있습니다. 끊임없이 변하는 시장에 잘 대처하기 위해서는 정보를 효과적으로 습득하는 것이 중요합니다. 
  #### 하지만 국내 개인투자자 대부분은 바쁜 일상에 치여 제대로된 증권 정보를 얻기가 쉽지 않은 실정이고, 이러한 정보의 부재로 손실을 보는 투자자들 또한 늘어나고 있습니다. 
  #### 그래서 우리는 이를 해결하기 위해 실시간 증권 시황과 뉴스 정보를 효과적으로 제공하는 챗봇을 구현하려 합니다. 


## 👩‍🏫 서비스 목표
  #### 바쁘디 바쁜 현대 사회를 살아가는 가운데 편리하고 빠르게 주식에 대한 정보를 손쉽게 알게 되는 것이 목표입니다.
  #### 서비스는 10분마다 업데이트를 하여 최신의 증권 정보를 사용자에게 제공해 주려고 합니다.
  #### 우리는 사용자의 질문을 통해 원하는 정보를 제공할 수 있는 RAG를 사용한 LLM 방식을 선택하였습니다.
  
## 🔨 기술 스택

#### 개발환경
<div align=left>
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white">
<img src="https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<br>
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<br>

#### DB
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/amazonrds-527FFF?style=for-the-badge&logo=amazonaws&logoColor=black">
<br>

#### 버전 관리
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
<br>

## :wrench: 시스템 아키텍쳐(네이버 말고 유명한 증권 분야의 사이트를.
  <img width="650px" src="https://github.com/user-attachments/assets/1d271544-fdff-4ed0-a412-d5d4b40abc25"> 



## ✅ 요구사항 명세서
  ####  :ok: 실제로 주식하는 사람들의 자주 하는 질문에 대해 제대로 답할 것.
  ####  :ok: 이전 대화 목록을 다시 불러와 사용할 수 있게 하는 것.
  ####  :ok: Django를 사용하여 웹 환경에서 이용할 수 있도록 구현할 것.
  ####  :ok: 네이버 증권과 증권 뉴스에서 데이터를 크롤링하는 서버를 따로 구현.
  ####  :ok: 크롤링한 데이터를 DB에 저장하고 실시간으로 데이터를 축적할 것.
  ####  :ok: RAG를 이용해 크롤링 해 온 데이터에서 정보를 찾을 것.
  ####  :ok: 질문을 했을 때 정보에서 좋은 답변을 도출시킬 것.

## 💻 DB 테이블 - ERD 및 DDL
  <img width="650px" src="https://github.com/user-attachments/assets/c7edd824-582c-4988-9a7b-22eedead99b6">


📚 주요 프로시저


## :eyes: 수행결과
  <img width="650px" src="https://github.com/user-attachments/assets/f32bbe34-0e62-4661-845d-f75f0a64f468">
  <img width="650px" src="https://github.com/user-attachments/assets/d0eeb5cb-c841-4e6d-9390-2bf0daa4f41c">
  <img width="650px" src="https://github.com/user-attachments/assets/0d9c1deb-eac5-432e-b8a4-f9e72608817f">
  <img width="650px" src="https://github.com/user-attachments/assets/ddf9e579-c9d5-41fa-99d6-aaed06e6f18d">

## ✈️ 향후 계획 및 개선점 (서비스 측면, 기술 측면)
 ### 서비스 측면
 #### 회원가입을 구현하여 고객별 질문에 대한 관리를 통해 서비스를 고도화합니다. 
 #### 질문에 대한 답변을 할 때 관련 링크가 알맞게 걸리지 않는 문제가 발생하는 부분을 해결합니다. 
 #### AI 음성비서 시스템에 이식하여 보다 사용자의 편의성을 증대합니다.
 #### 오픈된 정보로는 최근에 증가하고 있는 AI 뉴스 쪽으로 이 모델을 확장할 예정입니다.
 #### Private한 정보로는 이 모델을 조금 더 고도화 시킴으로 인해서 레포트(타입별로) 작성 하는 부분으로 확장할 예정입니다.
 ### 기술적 측면
 #### 해외 금융 사이트, Dart 등 재무제표 열람 사이트도 크롤링 할 수 있도록 합니다.
 #### STT와 TTS를 사용한 음성 채팅 기능을 추가해 편의성을 높일 수 있습니다.
 #### 주식 정보가 주로 띄고 있는 수치적 데이터를 시각화 할 수 있게 합니다.
  
## 🤔 한줄 회고
##### 🎩 Cap_KOO : 낯선 장고 프레임워크를 사용하여 웹 구축해보는 것이 어려웠지만 재미있었습니다. 시간의 제약이 더 아쉽게 느껴질 정도였어요!🥹 서로를 보완해주고 채워주는 팀워크도 너무 좋았습니다🤗✨️
##### 🎩 ACCUSE_KIM : Django에 비해 FAST-API가 개발 속도가 빠르다는 것을 알았습니다. DJango보다 FAST-API를 먼저 공부해서 Django도 쉬울 줄 알았지만 생각보다 어렵다는 걸 알게되었습니다.
##### 🎩 SUP_WOOK : DB를 활용하여 실시간 모델이 답할 수 있는 데이터 업데이트부분이 제일 재밌었습니다. 다음번에는 API를 통해 좀 더 안정적으로 데이터를 업데이트 하는 방안으로 갈 것 같습니다.
##### 🎩 JAMMANBO_LEE : 선택한 모델에 정보를 넣지 않았을 때 답변이 제대로 나오지 않았지만 RAG를 통해서 답변에 대한 정확도를 높일 수 있었습니다.
