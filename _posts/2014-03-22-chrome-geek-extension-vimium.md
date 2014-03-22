---
layout: post
title : chrome 极客插件 vimium
---

*像极客一样用Chrome*  
Vimium 是一个 chrome 的扩展插件，提供基于键盘的 *导航* 和 *控制* 。      
#  安装
####稳定版    
*   通过 Chrome Extensions Gallery 搜索 ‘vimium’   

####开发版 
*  安装 Coffeescript
*  下载 Vimium 源代码
*  生成 Javascript
*  在 chrome 中输入 chrome://extensions
*  选择开发者模式
*  加载正在开发的扩展程序
*  选择 Vimium 目录

# 使用  
####页面内操作
*   ?------Vimium 帮助  
*   h------scroll left
*   j------scroll down
*   k------scroll up
*   l------scroll right
*   gg-----scroll to top of the page
*   G------scroll to bottom of the page
*   d------scroll down half a page
*   u------scroll up half a page
*   f------open a link in the current tab
*   F------open a link in a new tab
*   r------reload
*   gs------view source
*   i------enter insert mode -- all commands will be ignored until you hit esc to exit
*   yy------copy the current url to the clipboard
*   yf------copy a link url to the clipboard
*   gf------cycle forward to the next frame

####新开页面
*   o------Open URL, bookmark, or history entry
*   O------Open URL, bookmark, history entry in a new tab
*   b------Open bookmark
*   B------Open bookmark in a new tab

####查找
*   n------cycle forward to the next find match
*   N------cycle backward to the previous find match

####浏览历史
*   H------go back in history
*   L------go forward in history

####多标签操作
*   J, gT      go one tab left
*   K, gt      go one tab right
*   g0------  go to the first tab
*   g$------  go to the last tab
*   t------   create tab
*   yt------  duplicate current tab
*   x------   close current tab
*   X------   restore closed tab (i.e. unwind the 'x' command)
*   T------   search through your open tabs

[官网](http://vimium.github.io/)
