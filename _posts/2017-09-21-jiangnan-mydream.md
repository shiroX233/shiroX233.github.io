---
layout:     post
title:      "2017年9月21日思修课上谈我的理想"
subtitle:   "无锡-江南大学"
date:       2017-09-21 12:00:00
author:     "M"
header-img: "img/my_dream.jpg"
catalog: true
tags:
  - 江南大学
  - 无锡
---


> 2017年9月21日思修课上，张瑶瑶老师让全班同学逐一走上讲台畅谈自己的理想

## 视频

<!-- 选择视频源 -->
<label for="video-source-1">选择视频源：</label>
<select id="video-source-1" onchange="changeVideoSource_1('video-container-1')">
  <option value="youtube">YouTube</option>
  <option value="bilibili">国内源</option>
</select>

<!-- 显示视频 -->
<div id="video-container-1"></div>

<script>
function changeVideoSource_1() {
  var videoSource = document.getElementById("video-source-1").value;
  var videoContainer = document.getElementById("video-container-1");

  // 清空视频容器
  videoContainer.innerHTML = "";

  if (videoSource === "youtube") {
    // 添加YouTube视频
    videoContainer.innerHTML = '<iframe width="560" height="315" src="https://www.youtube.com/embed/Uit5w7bHB3w?si=KoRzC5xdmZklck08" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>';
  } else if (videoSource === "bilibili") {
    // 添加Bilibili视频
    videoContainer.innerHTML = '<iframe width="560" height="315" src="https://47.93.29.116/videos/34%20%E9%A9%AC%E6%A8%8A%E5%9F%8E.mp4" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>';
  }
}

// 默认显示YouTube视频
changeVideoSource_1();
</script>

## 文本
大家好，我叫马樊城，来自计科1704，然后我来自青海。  

我首先短期的理想就是把计算机学好，把英语四级考上，然后把线代先学好。  

然后我那个，以后目标是帮全世界的宅男找到女朋友。  
