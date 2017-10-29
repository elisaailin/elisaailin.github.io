---
layout: post
title: Blog教程
description: 这是一篇教程
image: assets/images/02.jpg
---

# Blog使用说明
## 前期准备
首先点击[这里](https://github.com/git-for-windows/git/releases/download/v2.14.3.windows.1/Git-2.14.3-64-bit.exe)下载git
双击运行安装程序

撰写博客需要使用markdown语法，详情看在线的Markdown编辑器，点[这里](https://www.zybuluo.com/mdeditor)
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
1.将写完的博客放入_post文件夹下
2.在博客的根目录下邮件，选择open git bash here
3.输入./push.sh,并根据提示输入github的用户名和密码
