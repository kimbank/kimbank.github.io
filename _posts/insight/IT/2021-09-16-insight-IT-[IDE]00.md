---
layout: post
title: "[IDE 탐구] #00 IDE와 소프트웨어 개발"
description: >
  IDE #00
subtitle: ""
date: 2021-09-16 14:51:00 +0900
categories: insight
tags: IT
comments: false
related_posts: false
---
# 목차
  - [IDE (Integrated Development Environment)](#ide-integrated-development-environment)
  - [SDK (Software Development Kit)](#sdk-software-development-kit)
  - [API (Application Programming Interface)](#api-application-programming-interface)


소프트웨어 개발을 하기 위한 구성 요소들을 알 필요가 있어서 `IDE`, `SDK`, `API`로 구분해 놓았다.


# IDE (Integrated Development Environment)

> [![](https://miro.medium.com/max/4000/0*b4bgL-NR2GorAQw2)](https://medium.com/developerinsider/whats-new-in-xcode-10-fddeab035d05)
> *> Mac OS에서만 이용가능한 IDE인 Xcode이다.*

`Integrated Development Environment`의 약자로 직역하면 `통합 개발 환경` 정도가 된다.
`IDE`는 대체적으로 하나의 서비스 또는 프로그램을 개발하기 위한 도구인 코드편집기, 컴파일러, 디버거 등을 제공한다.
사진속에서 `IOS`의 어플리케이션을 제작하고 테스트하는 것이 보인다.
위와 같이, 프로그램을 만들고, 테스트를 하는 등 하나의 소프트웨어 제작을 위한 기능을 제공하는 것이 특징이다.


<br/><br/><br/>

# SDK (Software Development Kit)

> [![](https://www.wikihow.com/images/thumb/c/cb/Install-the-Java-Software-Development-Kit-Step-20-Version-4.jpg/aid123595-v4-728px-Install-the-Java-Software-Development-Kit-Step-20-Version-4.jpg.webp)](https://www.wikihow.com/Install-the-Java-Software-Development-Kit)
> *> `JDK`의 설치를 확인하는 장면이다.*

`Software Development kit`의 약자로 직역하면 `소프트웨어 개발 도구` 정도가 된다.
일반적으로 운영체제를 개발한 개발사가 해당 운영체제의 시장 장악을 위해 배포한다.
예시로는 `Oracle`에서 `JAVA`라는 프로그래밍 언어를 이용한 소프트웨어 개발을 돕기 위해 배포한 [`JDK(Java Development Kit)`](https://www.oracle.com/java/technologies/downloads/#java16)가 있다.

`SDK`는 위의 사진과 같이 `UI(User Interface)`를 제공하지 않기도 한다.
반면 `IDE`는 위의 [Xcode사진](#ide-integrated-development-environment)와 같이 개발의 생산성을 높여주는 `UI`를 제공한다.

<br/><br/><br/>

# API (Application Programming Interface)
> ![](/assets/posts_image/insight_IT/kiwoomKOA.jpg)
> *> 키움증권에서 `OpenAPI`사용자를 위해 제작한 문서의 일부분이다.*

`Application Programming Interface`의 약자로 직역하면 `응용 프로그래밍 인터페이스` 정도가 된다.
요즘은 다양한 서비스들이 서로 상호작용하는 경우가 많다.
`API`는 이미 존재하는 서비스의 데이터를 나의 소프트웨어로 불러오는데 도움을 준다.

예시로는, 키움증권에서 제공하는 [`OpenAPI`](https://www.kiwoom.com/h/customer/download/VOpenApiInfoView?dummyVal=0)를 통해 키움증권의 거래 데이터를 불러 오는 것이 있다.
만약 주식거래 인공지능 소프트웨어를 개발중인 상황이라면, 인공지능의 학습을 위한 주식거래 데이터가 필요할 것이다.
주식거래의 데이터를 `OpenAPI`로 불러와서 인공지능을 학습시키는 데에 사용하면 된다.

단적이 예일 뿐, `API`는 제공하는 주체에 따라 기능이 매우 다양하고 그만큼 활용할 수 있는 방법의 수도 다양하다.




<br/><br/><br/>
<sup><sub> [목차](#목차) </sub></sup>
 
  <!-- <sub><sup>[]</sup></sub> -->