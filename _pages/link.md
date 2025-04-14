---
layout: archive
title: "Link"
permalink: /link/
author_profile: true
redirect_from:
  - /resume
---

<!-- 固定Bing搜索栏 -->
<div align="center" style="margin: 20px 0;">
  <form action="https://www.bing.com/search" method="get" target="_blank" style="display: flex; align-items: center;">
    <span style="font-size: 28px; font-weight: bold; color: #000000; margin-right: 15px;">Microsoft Bing</span>
    <input type="text" name="q" placeholder="输入关键词搜索..." style="width: 500px; padding: 8px; border: 1px solid #ddd; border-radius: 4px;">
    <input type="submit" value="Search" style="padding: 8px 15px; margin-left: 10px; background-color: #4285F4; color: white; border: none; border-radius: 4px; cursor: pointer;">
  </form>
</div>

<!-- 固定Google搜索栏 -->
<div align="center" style="margin: 20px 0;">
  <form action="https://www.google.com/search" method="get" target="_blank" style="display: flex; align-items: center;">
    <span style="font-size: 28px; font-weight: bold; color: #000000; margin-right: 15px;">Google</span>
    <input type="text" name="q" placeholder="输入关键词搜索..." style="width: 500px; padding: 8px; border: 1px solid #ddd; border-radius: 4px;">
    <input type="submit" value="Search" style="padding: 8px 15px; margin-left: 10px; background-color: #4285F4; color: white; border: none; border-radius: 4px; cursor: pointer;">
  </form>
</div>

<!-- 链接跳转栏 -->
<div align="center" style="margin: 20px 0;">
  <form id="linkForm" style="display: flex; align-items: center;">
    <span style="font-size: 28px; font-weight: bold; color: #0078D4; margin-right: 15px;">快速跳转</span>
    <input type="text" id="linkInput" placeholder="输入完整链接..." 
           style="width: 500px; padding: 8px; border: 1px solid #ddd; border-radius: 4px; margin-right: 10px;">
    <input type="submit" value="Go" 
           style="padding: 8px 20px; background-color: #0078D4; color: white; border: none; border-radius: 4px; cursor: pointer;">
  </form>
</div>

<script>
  document.getElementById('linkForm').onsubmit = function(e) {
    e.preventDefault();
    const url = document.getElementById('linkInput').value.trim();
    if (url) {
      // 自动补全协议头
      const fullUrl = url.startsWith('http') ? url : 'http://' + url;
      window.open(fullUrl, '_blank');
    }
    return false;
  };
</script>


**<a href="https://epi.iis.u-tokyo.ac.jp/" target="_blank" rel="noopener noreferrer" style="font-size:26px;">Aziz Laboratory</a>**

## <span style="font-size:28px;">東京大学</span>
<div style="display:flex; gap:28px; font-size:28px; margin:24px 0;">
  <a href="https://www.ime.t.u-tokyo.ac.jp/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">IME</a>
  <a href="https://www2.mech.t.u-tokyo.ac.jp/?lang=ja" target="_blank" rel="noopener noreferrer" style="font-size:24px;">大学院工学系研究科機械工学専攻</a>
</div>

## <span style="font-size:28px;">学术</span>
<div style="display:flex; gap:28px; font-size:28px; margin:24px 0;">
  <a href="https://chat.qwen.ai/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">Qwen AI</a>
  <a href="https://chatgpt.com/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">ChatGPT</a>
  <a href="https://libdb.zju.edu.cn/s/lib/libtb/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">浙江大学图书馆数据库</a>
  <a href="https://scholar.google.com/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">Google Scholar</a>
  <a href="https://ieeexplore.ieee.org/Xplore/home.jsp" target="_blank" rel="noopener noreferrer" style="font-size:24px;">IEEE Xplore</a>
</div>

## <span style="font-size:28px;">娱乐</span>
<div style="display:flex; gap:28px; font-size:28px; margin:24px 0;">
  <a href="https://www.bilibili.com/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">Bilibili</a>
  <a href="https://skr.cc/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">Sakura Animation</a>
</div>

## <span style="font-size:28px;">Tool</span>
<div style="display:flex; gap:28px; font-size:28px; margin:24px 0;">
  <a href="https://www.scribbr.com/citation/generator/#user" target="_blank" rel="noopener noreferrer" style="font-size:24px;">Citation Generator</a>
  <a href="https://www.ilovepdf.com/zh-cn" target="_blank" rel="noopener noreferrer" style="font-size:24px;">PDF Toolbox</a>
  <a href="https://kingfast.info/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">KingFast VPN</a>
</div>

## <span style="font-size:28px;">Email</span>
<div style="display:flex; gap:28px; font-size:28px; margin:24px 0;">
  <a href="https://mail.google.com/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">Inbox Gmail</a>
  <a href="https://outlook.live.com/mail/0/" target="_blank" rel="noopener noreferrer" style="font-size:24px;">Inbox Outlook</a>
</div>






