﻿---
layout: post
title: Blog教程
description: 这是一篇教程
image: assets/images/02.jpg
---

# Blog使用说明
## 前期准备
首先点击[这里](https://git-scm.com/download/win)下载git

双击运行安装程序

主页配置在根目录下的index.md

个人信息配置在根目录下的_config.yml

撰写博客需要使用markdown语法，详情看在线的Markdown编辑器，点[这里](https://www.zybuluo.com/mdeditor)

新建一个文件夹存放博客，在文件夹内点击右键，选择git bash here，在黑框内输入git clone https://github.com/elisaailin/elisaailin.github.io.git

## 撰写博客
每一篇博客开头需要添加
```
---
layout: post
title: 博客名称
description: 博客描述
image: 博客背景图的路径，把图片放入assert文件夹下的images文件夹里，并起好名字，具体写法见本片博客开头
---
```
每一篇博客的文件名格式为2017-10-29-name.md

## 提交博客
1.将写完的博客放入_post文件夹下（删除博客的话删除_post文件夹下的对应文件，再提交一下就好了）

2.在博客的根目录下邮件，选择git bash here

本台计算机第一次提交时：
```
 git config --global user.email "you@example.com"
 git config --global user.name "Your Name"

```

3.输入./push.sh,并根据提示输入github的用户名和密码
