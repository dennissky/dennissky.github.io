---
layout:     post
title:      "Centos Free"
subtitle:   " \"Centos Free\""
date:       2018-10-25 10:37:00
author:     "Dennis"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - centos
---

# Centos Free

1.内存释放

    echo 1 > /proc/sys/vm/drop_caches #表示清除pagecache。
    echo 2 > /proc/sys/vm/drop_caches #表示清除回收slab分配器中的对象（包括目录项缓存和inode缓存）。slab分配器是内核中管理内存的一种机制，其中很多缓存数据实现都是用的pagecache。
    echo 3 > /proc/sys/vm/drop_caches #表示清除pagecache和slab分配器中的缓存对象。
