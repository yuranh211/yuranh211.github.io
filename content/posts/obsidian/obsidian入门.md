---
title: 'Obsidian入门：从第一个文件开始'
date: 2021-06-23
tags: [Obsidian]
draft: false
hideInList: false
feature: https://cdn.sspai.com/2021/06/29/c491327477539e789fc67a9b2bc10055.png?imageMogr2/auto-orient/quality/95/thumbnail/!1420x708r/gravity/Center/crop/1420x708/interlace/1
isTop: true
toc: true
---

写一个普通人也能看得懂的，照着操作就可以完成一篇笔记的使用指引。

<!--more-->


这是一篇Obsidian基础使用教程。对，我知道官方写的有手册。

这篇不讲什么快捷键，也不讲命令面板。写一个普通人也能看得懂的，照着操作就可以完成一篇笔记的使用指引。

## **导读**

### **大纲：**

* 打开库，创建第一个文件
* markdown的编辑与预览
* 打开分栏
* 引用（内部链接）
* 标签
* 检索
* 关系图谱

### **写作目标**

小学生也能看得懂得Obsidian使用教程。

下面开始。

👉准备工作：到官网下载并安装Obsidian.

## 第一个文件

👉1. 在电脑上选择任意一个地方，甚至桌面也可以，新建一个文件夹，给文件夹起一个名字，比如“日常记录”。

👉2. 打开obsidian，这时会看到下面的界面：

![](https://cdn.sspai.com/2021/06/29/article/c5ac330f0b75b137e9b6236ec64c29c4?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

👉3. 点击“打开库文件夹”后面的按钮【打开】，在弹出的文件选择器中找到刚刚创建的文件夹，选中，单击下方的【打开文件夹】。

![](https://cdn.sspai.com/2021/06/29/article/0164c2c82d700588b63584eacf7e2dde?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

👉4. 这时候，你就打开了日常记录库。接下来，你会看到以下界面：

![](https://cdn.sspai.com/2021/06/29/article/979e8bf36d6daefdf695cdbe0a752ddb?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

👉5. 有3种方式可以新建一个文件：

![](https://cdn.sspai.com/2021/06/29/article/c64f062f8e5279703c133d9be4a9f9bb?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

①、点击左侧导航栏上的新建文件图标；

②、点击界面中间的“创建新文件”；

③、快捷键(Ctrl+N)

👉6. 新建一个文件，你会得到一个未命名文件。接下来，将鼠标移动到文件中间，就可以开始书写啦。

![](https://cdn.sspai.com/2021/06/29/article/433e1fde5bad068b09d7f4fcaae5ceb4?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

## markdown的编辑与预览

👉1. 点击右上角的“预览”图标，切换到markdown预览模式。

![](https://cdn.sspai.com/2021/06/29/article/2b870a4493c6599a871ae171f485c259?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

👉2. 效果如下图。在预览模式下，待办列表可以点击打勾。

![待办列表|400](https://cdn.sspai.com/2021/06/29/article/39651808f4251532422bc44db9d4d786?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

👉3. 发现预览图标变成了✏图标，再次点击就会回到编辑模式。

![编辑模式|300](https://cdn.sspai.com/2021/06/29/article/32bf76211761add64e11fd2ce1999c9f?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

## 分栏

### 1. 拆分窗口

👉点击右上角的三个点图标，点击“左右拆分”或者上下拆分，你会得到一个一分为二的窗口。

![分栏|300](https://cdn.sspai.com/2021/06/29/article/63422700ff68bd9f5507a7e3705ab1d7?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

这两个窗口你可以分别操作。

比如说，左边用编辑模式来写作，右边用预览模式实时的看效果。

![](https://cdn.sspai.com/2021/06/29/article/106d8134defcf95cccf9ef7184bb7695?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

当你有多个文件时，还可以用分栏打开不同的文件，像这样：

![](https://cdn.sspai.com/2021/06/29/article/5c2d556861ca519d000233bb22e847e5?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

这个功能方便你参考以前的文章来写作。比如我在之前的文档中写的文章提案和头脑风暴，现在就在左栏打开着作为参考。

这个拆分窗口可以多次操作，你可以自由组合自己的窗口。当你选中某个窗口，再点击左侧的文件列表里的文件时，这个文件会在你选中的窗口中展示。

![](https://cdn.sspai.com/2021/06/29/article/d112c5559be3245fc58ef30aef130bdd?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

### 2.调整分栏窗口比例

👉拖动中间的分割线，可以来回拖动调整分栏窗口的比例。

## 引用（内部链接）

### 1.链接到文件

当我想要再“演示文件三”引用“演示文件”的时候，使用`[[`，会弹出一个文件列表，在里面选择想要链接的文件即可。

![link1|400](uhttps://cdn.sspai.com/2021/06/29/article/bedad38bcc52579737650c7ce2a67c45?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

### 2.链接到某个标题下面

![](https://cdn.sspai.com/2021/06/29/article/d0d7a8b08e76dd5032056a5bd88429c5?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

### 3.改变链接的显示文字

![](https://cdn.sspai.com/2021/06/29/article/8ad6c2a09677d0ca7f5bd418561bff7e?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

## 标签

### 1.给文件加标签

来了，所有云笔记都有的元素——标签。

这个东西展开讲简直是一门科学。

但我们不讲，哈哈哈哈......

标签的作用，在我看来是方便给笔记做二次分类。举个例子，你有一个读书笔记文件夹，里面放着多个读书笔记文件，这时候可以按照你自己给书分类的方式，给笔记打标签，比如“时间管理”、“心理学”、“科普”、“小说”。

语法是在标签名前面加井号，如`#标签名`。

标签还可以嵌套，相当于子标签。

### 2.打开标签面板

打开设置，找到选项中的【核心插件】，打开标签面板的开关。

![](https://cdn.sspai.com/2021/06/29/article/f5c340d8496c4be71cef5230e8c13a61?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

这时可以在右侧边栏看到标签面板中显示的标签啦。

![](https://cdn.sspai.com/2021/06/29/article/4f52b30be483edfafc3ecb9e9f751dc8?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

点击某个标签，会看到左侧边栏自动打开了搜索面板，能看到有这个标签的文件列表。

![](https://cdn.sspai.com/2021/06/29/article/e3e1187f4053047c2192912a5c47abb5?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

## 检索

当我们想要搜索某个内容，但是不记得放在哪个文件了，就需要搜索功能。

点击左侧边栏上方的放大镜图标，就可以打开搜索面板，我们输入一个关键词，回车。就能看到下方的搜索结果列表已经出现了所有包含这个关键词的文件和内容。

![search1|200](https://cdn.sspai.com/2021/06/29/article/91b6da1099664cc4ee152b0fa80ce156?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

## 关系图谱

因为刚才我们在“演示文件三”中链接了“演示文件”，所以现在可以来看看关系图谱。

关系图谱很炫酷，当然那是在你文件多了以后，现在我们还是先打开看看这个“简陋的”关系图谱吧。

### 1.打开整个库的关系图谱

在左侧边栏最左边的操作栏，点击下图中图标。

P.S. 所有的图标鼠标悬浮都能看到中文释义。

![map1|500](https://cdn.sspai.com/2021/06/29/article/d647ea150bb6d934b377d8a4f0b600b1?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

### 2.打开当前文件的关系图谱

在当前文件的窗口右上角，点击三个点（选项按钮），在弹出的选项中，点击【打开局部关系图】。

![map2|350](https://cdn.sspai.com/2021/06/29/article/50a0e150d039b34f791dce12a91c420d?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

能看到当前文件和其他文件的关系连接图：

![map3|300](https://cdn.sspai.com/2021/06/29/article/d101b05c536a9530b496f574f23c8db9?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

## **查看大纲**

### 打开大纲模式

同样打开“设置>核心插件”，在插件列表找到“大纲”，打开右侧的开关。然后关闭设置弹窗。

![](https://cdn.sspai.com/2021/06/29/article/4e597be1cc78d85da66ce264e48b5cb2?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

这时，你会看到右侧边栏多出一栏，点击，就能看到当前文件的大纲啦~

![](https://cdn.sspai.com/2021/06/29/article/1f287df2d6a9ce61a7add68801b131f6?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

## 结语

这个文档类似于编程里面的hello world，如果你对Obsidian感兴趣，又不知道从何开始，这这篇文章可以给你点参考。

Obsidian官方也有中文文档，写的很专业。点击左下角的帮助图标，你会得到一整个Obsidian中文帮助文档。

![](https://cdn.sspai.com/2021/06/29/article/974179b66ff14afcc64550542cb1e693?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

如果你觉得官方文档太专业了，也可以来看看我这篇不专业的。

其实我觉得这个文档写的多此一举，但我也有过刚用obsidian有些设置找不到，很懵的情况。

这篇操作教程，除了Obsidian这个软件名，我尽量不用任何英文，并且大量配图，希望能给刚接触Obsidian的用户提供一个参考。