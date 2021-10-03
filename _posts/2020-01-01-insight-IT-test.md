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

<script type="text/javascript" src="https://jsonip.com"></script>

<script type="text/javascript">

	function getIP(json) {

		document.write(json.ip);

	}

</script>



<script type="text/javascript" src="https://api.ipify.org?format=jsonp&callback=getIP"></script>



<style>
  #client-ip {
    color: #ff80ab;
  }
</style>

<div>이 컴퓨터의 IP 주소: <span id="client-ip"></span></div>

