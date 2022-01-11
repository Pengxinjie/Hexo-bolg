---
title: 个人博客网站的搭建
date: 2022-01-11 14:17:48
author: lengxuan
password: bf52014e1afdad9f64f83cc367aba55a4512f901dcdcf1d2ce781536633c74ac
summary: 使用Hexo框架+云服务器搭建属于自己的个人网站。
categories: Hexo
tags:
  - Hexo
  - 个人博客
  - 建站
---

Hexo+云服务器建站

## 一、系统环境准备

1. Git
2. Node.js

## 二、安装Hexo

1. 使用npm全局安装Hexo命令：

```bash
npm install -g hexo-cli
```

1. 局部安装Hexo

```bash
npm install hexo
```

## 三、建站

1. 在指定文件夹中新建所需要的文件

``` bash
hexo init myblog
cd myblog
npm install
```

2. 启动Hexo

```bash
hexo server
```
## 四、更换主题

> 以matery主题为例

1. 下载

```bash
cd themes
git clone https://github.com/blinkfox/hexo-theme-matery.git
```

2. 主题切换

```bash
修改 Hexo 根目录下的 _config.yml 的 theme 的值：theme: hexo-theme-matery
```
3. 运行

```bash
hexo server
```

4. 详细配置见官方文档:smile:

