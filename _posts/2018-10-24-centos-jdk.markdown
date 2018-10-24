---
layout:     post
title:      "Centos Jdk"
subtitle:   " \"Centos Jdk\""
date:       2018-09-20 10:37:00
author:     "Dennis"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - django
---

# Centos Jdk

1.下载 

    wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" 加上 
    具体到某一个的路径,例如:
    http://download.oracle.com/otn-pub/java/jdk/8u191-b12/2787e4a523244c269598db4e85c51e0c/jdk-8u191-linux-x64.tar.gz?AuthParam=1540391150_62ff8244726

[jdk下载地址][1]

2.配置环境变量
    
    1.解压 tar -zxvf  jdk-8u191-linux-x64.tar.gz
    2.编辑 vim  /etc/profile

    添加如下内容：JAVA_HOME根据实际目录来
    export JAVA_HOME=/home/soft/jdk1.8.0_111 
    export JRE_HOME=${JAVA_HOME}/jre
    export CLASSPATH=.:${JAVA_HOME}/lib:${JRE_HOME}/lib
    export PATH=${JAVA_HOME}/bin:$PATH

    3.刷新 profile source /etc/profile 
    4.验证 java -version

[1]:http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html