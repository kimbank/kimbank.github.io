---
layout: post
title: "코딩과 이름짓기"
description: >
  Naming
subtitle: ""
date: 2021-10-03 19:19:00 +0900
categories: insight
tags: IT
comments: false
related_posts: false
---


# 목차
 - [Underscore](#underscore)
 - [Upper Camel Case](#upper-camel-case)
 - [Lower Camel Case](#lower-camel-case)
 - [Google Style Guide](#google-style-guide)

<br/>

![](https://media.vlpt.us/images/ggob_2/post/d08477db-9827-4e13-8a9b-a2b5a7d07954/%EA%B0%9C%EB%B0%9C%EC%9E%90%EC%9D%98%20%EA%B3%A0%EC%B6%A9.jpg)

위의 이미지에서 알 수 있듯이 코딩하는 과정에서 이름짓는 것은 힘든 일이다.
새로운 게임을 시작할 때에 닉네임을 짓는 것도 많은 고민이 필요하듯이 변수와 함수 등의 이름을 짓는 일은 많은 고민을 필요로 한다.
협업을 하게 된다면 동료들에게 피해를 주지 않기 위해 이름짓는 규칙을 정하는 것이 중요할 것이다.

<br/><br/>
<!--------------------------------- # 목차 ----------------------------->






# Underscore

```c
int sample_num1 = 100;
int sample_num2 = 200;
```

단어의 구분을 언더바 `_` 를 통해서 하는 것이 특징이다.
모두 소문자로 작성한다.

<br/><br/>
<!---------------------------- # Underscore ----------------------------->





# Upper Camel Case

```c
int SampleNum1 = 100;
int SampleNum2 = 200;
```

위와 같은 형식으로 쓰는 것을 `Upper Camel Case`라고 한다.
쌍봉 낙타의 혹과 비슷한 모양으로 대문자로 단어를 구분하는 것이다.

<br/><br/>
<!--------------------------- # Upper Camel Case ------------------------>





# Lower Camel Case

```c
int sampleNum1 = 100;
int sampleNum2 = 200;
```

[Upper Camel Case](#upper-camel-case)와의 차이점은 맨 앞 단어의 첫 스펠링을 소문자로 작성한다는 것이다.


<br/><br/>
<!-------------------------- # Lower Camel Case -------------------------->





# Google Style Guide
구글은 이름짓기`(Naming)`에 대한 가이드 라인을 가지고 있다.
[https://google.github.io/styleguide/cppguide.html#Naming](https://google.github.io/styleguide/cppguide.html#Naming)

위의 링크는 구글의 가이드라인 페이지이다. 
유도리 있게 어느정도 팀마다 다른 스타일을 허용하는 듯하다.
이렇게 하는 것을 권장한다 정도로 생각하면 될 것 같다.

파일 이름, 디렉토리 이름, 클래스 이름 등 모든 이름짓기에 대한 가이드 라인을 제시한다.
앞서 소개한 방식들을 혼용하여 사용하는 것으로 보인다.


<br/><br/><br/>

<sup><sub> [목차](#목차) </sub></sup>