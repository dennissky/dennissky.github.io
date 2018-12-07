---
layout:     post
title:      "VsCode"
subtitle:   " \"Vscode Sync\""
date:       2018-12-07 22:37:00
author:     "Dennis"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - 前端
---

# Settings Sync

## 插件介绍
该插件是用来将本地vscode同步是github的,这样来回电脑更换,就可以保存个性化的vscode配置啦!是不是好嗨哦！
![plugin][1]
1. 重启后```alt+shift+u```
2. 他会弹出一个窗口对应的是github创v建个人gist的页面,如果未登录请登录,然后选择下面的gist
保存后会生成一个key
3. 切回到vscode,他会有个输入区,输入刚才的key
4. 接下来我们到另一台电脑上了下载配置,同样先安装Settings Sync,然后```alt+shift+d```,就会弹出一个输入框,
请在这里输入之前保存下来的key(Gist ID),回车后将会自动下载之前上传的配置

[1]: /img/in-post/2018-12-07-vscode-sync/plugin.png