+++
date = '2025-07-31T16:24:01+08:00'
draft = false
title = '1panel can not create SSL certificate , and shows error 400:invalid authorization.'
author = "alma"
categories=["blog setup","how-to"]
tags=["hugo", "github", "1panel","vps","beginner"]
+++
## Error 400:Invalid authorization
### 1. create certificate for my site via 1panel
As a complete beginner, I am eager to build my own personal blog. Following a tutorial on YouTube, I have already registered a domain and a server, installed 1Panel on the server, and am now ready to apply for an SSL certificate for my website. But, i failed. Here is the screenshot
![1panel can not create certificate and shows error400](/images/1panelssl2.png)
### 2. try to disable the firewall of your machine, and create it again
The Youtube Vlogger is always successfully create their web-site. But i'm always running into some issue. Anyway, i fixed this issue via disable the firewall. I disabled the firewall of VPS, and click 'create' button again. Finally, i created certificate for my site.