---
layout:     post
title:      "Idea Plugins"
subtitle:   " \"Idea Plugins\""
date:       2018-05-28 09:44:00
author:     "Dennis"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - idea
---

# IntelliJ IDEA 插件推荐

1. [ignore][1] 
生成各种ignore文件，一键创建git ignore文件的模板，免得自己去写  
![ignore][2]

2. [lombok][3]  
lombok是一个可以通过简单的注解形式来帮助我们简化消除一些必须有但显得很臃肿的Java代码的工具，通过使用对应的注解，可以在编译源码的时候生成对应的方法
![lombok][4]  

3. [GenerateAllSetter][5]  
一键生成java类所有set方法并赋予默认值
![GenerateAllSetter][6]  

4. [GsonFormat][7]
一键根据json文本生成java类  非常方便
![GsonFormat][8]  

5. [Translation][9]  
翻译插件 mac 下的快捷键是control+command+u  
![translation][10]

6. [SequenceDiagram][11]
这个工具是能根据代码生成时序图的.我们直接看效果
![SequenceDiagram][12]

7. [RestfulToolkit][13]
平时Controller方法太多,找起来太费劲?这个插件来帮你
![RestfulToolkit][14]
只要输入url路径,立刻跳转到指定方法,节省效率不止一点点

8. [Maven Helper][15]
这个是我在公司要求必装的一个插件,另外我在评审代码评审的第一步就是检查项目的依赖冲突,如果我们用idea自带的依赖分析工具,那么出现如下情况
![Maven Helper][16]
坦白说,你让我在这么庞大的一幅图中,分析依赖,找出依赖冲突,坦白说,我认为不够直观.那么用上这个插件之后呢?
![Maven Helper][17]
红色的就是出现依赖冲突,例如图中的commons-logging,点击进入我画框框的地方,他就会从依赖路径上给你分析依赖冲突的路径.其实这个的原因也很简单,就是利用Maven的依赖树命令

9. [Key PromoterX][18]
Key Promoter X 是一个提示插件，当你在IDEA里面使用鼠标的时候，如果这个鼠标操作是能够用快捷键替代的，那么Key Promoter X会弹出一个提示框，告知你这个鼠标操作可以用什么快捷键替代。对于想完全使用快捷键在IDEA的，这个插件就很有用。

10. [PlantUML][19]
该工具是用来绘制uml图,简洁高效。
具体语法见[PlantUML][20]
![PlantUML][21]















[1]: https://plugins.jetbrains.com/plugin/7495--ignore
[2]: /img/in-post/2018-05-28-idea-plugins/gitignore.gif
[3]: https://plugins.jetbrains.com/plugin/6317-lombok-plugin
[4]: /img/in-post/2018-05-28-idea-plugins/lombok.gif
[5]: https://plugins.jetbrains.com/plugin/9360-generateallsetter
[6]: /img/in-post/2018-05-28-idea-plugins/allsetter.gif
[7]: https://plugins.jetbrains.com/plugin/7654-gsonformat
[8]: /img/in-post/2018-05-28-idea-plugins/gson.gif
[9]: https://plugins.jetbrains.com/plugin/8579-translation
[10]:/img/in-post/2018-05-28-idea-plugins/translate.gif
[11]:http://plugins.jetbrains.com/plugin/8286-sequencediagram
[12]:/img/in-post/2018-05-28-idea-plugins/seq.jpg
[13]:http://plugins.jetbrains.com/plugin/10292-restfultoolkit
[14]:/img/in-post/2018-05-28-idea-plugins/restful.jpg 
[15]:http://plugins.jetbrains.com/plugin/7179-maven-helper
[16]:/img/in-post/2018-05-28-idea-plugins/mvn-helper-1.jpg
[17]:/img/in-post/2018-05-28-idea-plugins/mvn-helper-2.jpg
[18]:http://plugins.jetbrains.com/plugin/9792-key-promoter-x
[19]:https://plugins.jetbrains.com/plugin/7017-plantuml-integration
[20]:http://plantuml.com/zh/
[21]:/img/in-post/2018-05-28-idea-plugins/uml.jpg