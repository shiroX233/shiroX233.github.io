---
layout:     post
title:      "2024年3月的跳伞之旅"
subtitle:   "日本-福冈县"
date:       2024-03-17 14:21:00
author:     "M"
header-img: "img/parachute.jpg"
catalog: true
tags:
  - 旅行
  - 日本
---


> 马上起飞了

## 第一段视频
真的很爽，自由落体就是不一样

<!-- 选择视频源 -->
<label for="video-source-1">选择视频源：</label>
<select id="video-source-1" onchange="changeVideoSource_1('video-container-1')">
  <option value="youtube">YouTube</option>
  <option value="bilibili">Bilibili</option>
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
    videoContainer.innerHTML = '<iframe width="560" height="315" src="https://www.youtube.com/embed/S5B9NmdEhDc?si=KJPmX2rgrDzOsaii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>';
  } else if (videoSource === "bilibili") {
    // 添加Bilibili视频
    videoContainer.innerHTML = '<iframe width="560" height="315" src="https://player.bilibili.com/player.html?isOutside=true&aid=231292325&bvid=BV1v8411m7Xr&cid=1209294663&p=1&high_quality=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>';
  }
}

// 默认显示YouTube视频
changeVideoSource_1();
</script>


## 第二段视频
就在天上飞的的那种，手脚都放开，然后急速下降

<!-- 选择视频源 -->
<label for="video-source-2">选择视频源：</label>
<select id="video-source-2" onchange="changeVideoSource_2('video-container-2')">
  <option value="youtube">YouTube</option>
  <option value="bilibili">Bilibili</option>
</select>

<!-- 显示视频 -->
<div id="video-container-2"></div>

<script>
function changeVideoSource_2() {
  var videoSource = document.getElementById("video-source-2").value;
  var videoContainer = document.getElementById("video-container-2");

  // 清空视频容器
  videoContainer.innerHTML = "";

  if (videoSource === "youtube") {
    // 添加YouTube视频
    videoContainer.innerHTML = '<iframe width="560" height="315" src="https://www.youtube.com/embed/I1sSwYIz4rg?si=qkFVi9tnvQXrXkHw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>';
  } else if (videoSource === "bilibili") {
    // 添加Bilibili视频
    videoContainer.innerHTML = '<iframe width="560" height="315" src="//player.bilibili.com/player.html?aid=1234&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>';
  }
}

// 默认显示YouTube视频
changeVideoSource_2();
</script>



## 第三段视频
从头到尾都没有害怕的感觉，这边的人也挺专业的

<!-- 选择视频源 -->
<label for="video-source-3">选择视频源：</label>
<select id="video-source-3" onchange="changeVideoSource_3()">
  <option value="youtube">YouTube</option>
  <option value="bilibili">Bilibili</option>
</select>

<!-- 显示视频 -->
<div id="video-container-3"></div>

<script>
function changeVideoSource_3() {
  var videoSource = document.getElementById("video-source-3").value;
  var videoContainer = document.getElementById("video-container-3");

  // 清空视频容器
  videoContainer.innerHTML = "";

  if (videoSource === "youtube") {
    // 添加YouTube视频
    videoContainer.innerHTML = '<iframe width="560" height="315" src="https://www.youtube.com/embed/SNKjn-9Qw2E?si=bOjYYUmycsBnUQoF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>';
  } else if (videoSource === "bilibili") {
    // 添加Bilibili视频
    videoContainer.innerHTML = '<iframe src="//player.bilibili.com/player.html?aid=1234&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>';
  }
}

// 默认显示YouTube视频
changeVideoSource_3();
</script>
