---
layout: post
title: "this is test page"
description: >
  test page
subtitle: ""
date: 2020-01-01 00:00:01 +0900
categories: insight
tags: IT
comments: false
related_posts: false
---



<div>이 컴퓨터의 IP 주소: <span id="client-ip"></span></div>

<script>
  const se = document.createElement('script');
  se.src = 'https://ipinfo.io?callback=callback';
  document.body.appendChild(se);
  document.body.removeChild(se);
  function callback(data) {
    document.getElementById('client-ip').textContent = data.ip;
  }
</script>