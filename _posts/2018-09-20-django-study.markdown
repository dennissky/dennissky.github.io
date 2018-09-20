---
layout:     post
title:      "Django Learn"
subtitle:   " \"Django Learn\""
date:       2018-09-20 10:37:00
author:     "Dennis"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - django
---

# django learn

1.Django 安装  
    
    brew install python3
    curl https://bootstrap.pypa.io/get-pip.py | python3
    pip install Django==2.1.1

2.Django start  
    
    django-admin startproject myblog

3.启动django  
    
    python3 manage.py runserver

4.创建应用  
    
    python3 manage.py startapp blog

5.models  
    
    python3 manage.py makemigrations app名
    python3 manage.py migrate
    python3 manage.py sqlmigrate blog 0001

6.admin  
    
    python3 manage.py createsuperuser
