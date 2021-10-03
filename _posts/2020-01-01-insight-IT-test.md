---
layout: post
title: "this is test page"
description: >
  test page
subtitle: ""
date: 2020-01-01 00:00:00 +0900
categories: insight
tags: IT
comments: false
related_posts: false
---





<div>이 컴퓨터의 IP 주소: <span id="client-ip"></span></div>

<script>
  // HTML의 <script> 요소를 생성한다
  const se = document.createElement('script');
  // <script> 요소의 src 속성을 설정한다
  se.src = 'https://ipinfo.io?callback=callback';
  // <body> 요소의 하위 끝에 붙인다
  // 그리고 콜백 함수를 호출한다
  document.body.appendChild(se);
  // 앞서 생성한 <script> 요소를 제거한다
  document.body.removeChild(se);

  // 콜백 함수가 호출된다
  function callback(data) {
    document.getElementById('client-ip').textContent = data.ip;
  }
</script>