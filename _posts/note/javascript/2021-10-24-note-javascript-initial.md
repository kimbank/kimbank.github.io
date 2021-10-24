---
layout: post
title: javascript quiz
description: >
   javascript
subtitle: ""
date: 2021-10-24 19:19:00 +0900
categories: note
tags: javascript
comments: false
related_posts: false
---


<div id="quiz"> </div>
   <button id="submit" style="border:1px solid tomato; margin:2px; border-radius:5px; color:tomato;"> Submit </button>
<div id="result"> </div>

<script>
  const quizData = [
  {
      question : '웹개발에 주로 사용되는 프론트언어는?',
      answers : {
         a : "일본어",
         b : "다랑어",
         c : "자바스크립트",
         d : "sample"
      },
     correct : 'c'
  },
  {
      question : '웹 디자인에 사용되는 언어는?',
      answers : {
          a : '미싱',
          b : 'css',
          c : '돈까s'
      },
     correct : 'b'
  },
  {
        question : '블로그 형태로 웹사이트를 쉽게 개발할 수 있는 방식을 무엇이라고 하는가?',
        answers : {
              a : 'CMS',
              b : 'WAX',
              c : 'KISWISS'
        },
     correct : 'a'
  }
  ]
</script>

{% include scripts/quiz.html %}