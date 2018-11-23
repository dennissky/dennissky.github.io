---
layout:     post
title:      "Docker Mirror"
subtitle:   " \"Docker Mirror\""
date:       2018-11-08 21:37:00
author:     "Dennis"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - docker
---

## docker 配置阿里云镜像

1. centos
    ```
        vim /etc/docker/daemon.json
        {"registry-mirrors": ["https://xc08p2g4.mirror.aliyuncs.com"]} 
        //该地址由阿里云镜像仓库提供

        systemctl daemon-reload
        systemctl restart docker
    ```