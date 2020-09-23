---
title : chrome install the proxy swtichomega
layout: post  
---

chrome不能手动安装proxy switchomega 的解决办法
> 先准备好Socks 代理  

步骤：
1. 关闭所有chrome
2. 打开cmd，并定位到 chrome.exe目录  *一般安装在C:\Program Files(x86)\Google\Chrome\Application下*
2. 执行命令：`chrome.exe   --show-app-list  --proxy-server="SOCKS5://{IP}:{PORT}"`
3. 安装并配置proxy switchyomega


