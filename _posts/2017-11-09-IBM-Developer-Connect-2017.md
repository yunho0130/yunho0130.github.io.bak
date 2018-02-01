---
layout: post
title:  "IBM Developer Connect 2017"
date:   2017-11-09 18:01:13
categories: Conference
permalink: /archivers/IBM_Developer_Connect_2017
---

# IBM Developer Connect 2017

![](media/15102006901706.jpg)
 
## 서버리스, 클라우드 컴퓨팅 진화의 다음 단계
Open Whisk에 대한 소개
<openwhisk.org>

## 리테일과 인공지능 로봇 이상과 현실 사이의 괴리에 대하여 - 이마트, 박창현

* Software Architecture
    - Embedded Linux: Gentoo기반으로 작동함
    - NAOqi Framework가 지원되고 Python과 C++ API를 지원한다. 
    - 약간 안드로이드 같은 구조를 가지고 있음. 
* 도입 후기
    - 내장형 음성 인식, 자연어 처리, 음성 합성의 한계 (네트워크를 거치지 않음) 
    - Rule Base 기반이 아니라 머신러닝 기반의 자연어 인식이 필요했음. 여기에 Watson을 도입하기로 함. 
    - 아래와 같은 아키텍처로 로봇에 심기 시작했음. 
     ![KakaoTalk_2017-11-09-13-17-01_Photo_74](media/KakaoTalk_2017-11-09-13-17-01_Photo_74.jpeg)
    - Watson은 이해를 못하는 부분이 나오면 나중에 재학습을 시킬 수 있음. 
    - 음성대화는 휘발성이 강함. 2 Depth 이상의 대화가 어렵다. 
    - 아마존도 에코에서 새로운 세대의 제품을 내놓았을 때, 터치스크린을 달기 시작했음. 시각정보를 같이 줘야 깊은 대화가 가능함. 
    - 로봇과 AI 스피커는 다름. 모션이 필요함. 말만하고 있으면 이상해. 
* 매장 배치 후기
    - 로봇을 낯설어한다. 
        - 사람들이 로봇에게 먼저 말을 걸지 않아서... 
        - 터치 스크린 추가
    - 매장이 너무 시끄럽다
        - 추가 스피커
        - 넥밴드 블루투스 이어폰                     
            ![KakaoTalk_2017-11-09-13-30-52_Photo_92](media/KakaoTalk_2017-11-09-13-30-52_Photo_92-2.jpeg)

## 왓슨 컨버세이션 서비스를 이용한 챗봇 개발 방안 소개 - 고대민
![KakaoTalk_2017-11-09-13-51-48_Photo_26](media/KakaoTalk_2017-11-09-13-51-48_Photo_26.jpeg)

* WCS (Watson Conversation Service) 
    - Intent: 질문의 의도
    - Entity: 중요한 명사
    - Dialog: Flow를 처리하는 것
    - 팁
        - 입력하지 않은 질문도 머신러닝을 통해 인텐트를 추측하기 때문에 인텐트를 개념적으로 잘 구분해서 정의하는 게 중요함. 인텐트는 불확정성에 기반으로 머신러닝을 함. 
        - 다이얼로그는 놓치지 않아야 하는 것이기 때문에 정확하게 유도하는 기능을 함. 
* 용어 
    - Watson 
    - Controller = application = Orchestration
    - Legacy : 기존 기업의 시스템

![KakaoTalk_2017-11-09-14-00-24_Photo_48](media/KakaoTalk_2017-11-09-14-00-24_Photo_48.jpeg)
![KakaoTalk_2017-11-09-14-25-07_Photo_24](media/KakaoTalk_2017-11-09-14-25-07_Photo_24.jpeg)
![KakaoTalk_2017-11-09-14-24-54_Photo_63](media/KakaoTalk_2017-11-09-14-24-54_Photo_63.jpeg)
![KakaoTalk_2017-11-09-14-24-53_Photo_56](media/KakaoTalk_2017-11-09-14-24-53_Photo_56.jpeg)
Building Cognitive Applications with IBM Watson Services: Volume 4 Natural Language Classifier
<https://www.redbooks.ibm.com/Redbooks.nsf/RedbookAbstracts/sg248391.html?Open>

## 맨땅에 헤딩하지 않는 머신러닝 - 유성훈
* 머신러닝 기본 개념 설명

## 컨테이너를 활용하는 GPU 딥러닝 환경 소개 - 이보란, 코그너티브 시스템즈, 기술 영업
* HPC/HPDA Platform
    - GPGPU를 위한 기업용 서버를 구축했을 때, 다수의 개발자를 대상으로 효율적인 GPU자원을 할당하기 위한 플랫폼
    - 이를 위해 LSF 하드웨어나 Nvidia-docker이미지 등을 활용하여 작업을 할당
    - 개인이 하나의 서버에 하나의 GPU를 할당하는 경우와 아키텍처가 많이 달라짐.
 
## Watson 한국어 서비스 개발 과정 소개 - 김대용 과장
* 한국어 서비스 개발에 어려운 점, 어떻게 해결했는지 등에 대한 개괄적인 설명
    


