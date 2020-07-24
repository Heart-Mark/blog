---
layout: tec
title: 技术 · 编程
avatar: /images/author.gif
comments: true
author: Hesperus｜Venus
categories: 技术
cover: 'http://wx3.sinaimg.cn/large/0069lHOigy1g2g628veuqj30b40b4dfn.jpg'
photos: 'http://wx3.sinaimg.cn/large/0069lHOigy1g2g628veuqj30b40b4dfn.jpg'
date: 2020-07-20 15:29:01
authorLink: hehuadong.cn
authorAbout: 钻研vue的人
authorDesc: 钻研vue的人
tags:
  - 技术
keywords: 技术 · 编程
description: 安装Vue教程
---

安装VUE之前需要先安装NODE.JS
按照下面的顺序执行即可初始化启动一个基本VUE项目

```shell
// 安装node.js，内含npm，Node.js官网：https://nodejs.org/en/ 。
 
// 设置npm镜像cnpm命令行工具
npm install -g cnpm --registry=https://registry.npm.taobao.org 
 
// 全局安装 vue-cli
cnpm install -g vue-cli
 
// 先创建并进入vue项目目录
cd W:\Workspaces\git_repositories\javalsj-blog-vue
 
// 创建一个基于 webpack 模板的新项目
vue init webpack javalsj-blog-vue
 
// 先进入vue项目目录下再安装该项目的依赖
cd W:\Workspaces\git_repositories\javalsj-blog-vue\javalsj-blog-vue
 
// 初始化安装项目
cnpm install
 
// 运行项目
npm run dev
```
