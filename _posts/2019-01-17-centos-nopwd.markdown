---
layout:     post
title:      "Vim Action"
subtitle:   " \"Centos免密码登录\""
date:       2019-01-17 02:37:00
author:     "Dennis"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - centos 
---

## Centos 免密码登录

1. 在主机A执行命令 
    `ssh-keygen -t rsa`
   然后一路回车

2. 将id_rsa.pub 公钥传输给服务器 并添加到服务器/root/.ssh/authorized_keys下
  `cat id_rsa.pub >> authorized_keys` 