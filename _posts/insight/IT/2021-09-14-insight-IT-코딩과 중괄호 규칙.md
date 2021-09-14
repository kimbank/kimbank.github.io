---
layout: post
title: "코딩과 중괄호"
subtitle: ""
date: 2021-09-14 00:17:00 +0900
categories: insight
tags: programming
comments: false
related_posts: false
---

# 목차
 - [Allman](#allman)
 - [K&R](#k-r)
 - [GNU](#gnu)
 - [Haskell](#haskell)

 출처는 [위키 피디아](https://en.wikipedia.org/wiki/Indentation_style)임을 밝힙니다.

<br/><br/><br/>

# Allman
```c
while (x == y)
{
    something();
    somethingelse();
}
```
위와 같은 방법이 `Allman`방식의 중괄호 위치 배치 이다.
내가 사용하는 방법으로 구분이 한눈에 가능하다.

<br/><br/><br/>

# K&R
```c
while (x == y) {
    something();
    somethingelse();
}
```
위와 같은 방법은 `K&R`방식으로 첫번째 중괄호가 위에 붙어 있는 것이 특징이다. 
1학년 1학기때 수강한 수업에서 교수님이 위와 같은 방식을 사용하셨다. 
C/C++에서 흔히 사용된다고 하는데, 나는 이 방식이 잘 적응이 안된다.
C언어를 만든 [Brian Kernighan](https://en.wikipedia.org/wiki/Brian_Kernighan)과 [Dennis Ritchie](https://en.wikipedia.org/wiki/Dennis_Ritchie)의 스타일이라고도 한다.
한국에서 가장 흔하다고 한다.
지금도 그런지는 잘 모르겠다.
<!-- C언어를 만든 [Brian Kernighan](https://en.wikipedia.org/wiki/Brian_Kernighan)과 [Dennis Ritchie](https://en.wikipedia.org/wiki/Dennis_Ritchie)이 쓴 과거의 수학의 정석급 위치를 가지고 있던 C언어 안내서 [The Elements of Programming Style](https://en.wikipedia.org/wiki/The_Elements_of_Programming_Style) -->

<br/><br/><br/>

# GNU
```c
while (x == y)
  {
    something ();
    somethingelse ();
  }
```
GNU를 설립한 것으로 유명한 [Richard Stallman](https://en.wikipedia.org/wiki/Richard_Stallman)에 의해 알려졌다고 한다.


<br/><br/><br/>

# Haskell
```c
while (x == y)
  { something()
  ; somethingelse()
  ;
  }
```
신기한 중괄호 배치 방식을 발견했다.
의외로 아이디어가 좋은 것 같다.
세미콜론을 이용하여 `IDE`의 도움 없이 중괄호 블럭의 범위를 파악할 수 있다는 것은 흥미로운 것 같다.
하지만 블록이 많이 겹쳐지게 된다면 빵꾸(?)가 생겨 오히려 역효과가 일어날 것 같기는 하다.

<br/><br/><br/>
<sup><sub> [목차](#목차) </sub></sup>
 
  <!-- <sub><sup>[]</sup></sub> -->