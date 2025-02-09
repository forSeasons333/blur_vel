---
title: 基于Asrto搭建一个属于自己的博客
description: 使用Astro框架进行博客搭建并推送
pubDate: 2025-02-08
---

------

# 前言

本文旨在一次性帮助读者完成基于Astro的博客搭建

什么是Astro？了解[Astro](https://docs.astro.build/zh-cn/concepts/why-astro/)

## ***一.挑选主题并clone到本地***

​	不同于Hexo，Astro框架并不能做到在配置文件里更改主题即可实现换主题的效果，而是需要将整个博客文件更换：即主题文件为博客文件本身。故事先选定好主题便是重中之重，以下列出部分个人比较喜欢的主题，以便读者参考

​	[fuwari](https://github.com/saicaca/fuwari)

​	[Koibumi](https://github.com/koibumi-design/astro-blog)

​	[astro-blur](https://github.com/Jazee6/astro-blur)（本博客所用主题）

### 		1.建立github账号

### 		2.以主题仓库为模板fork到自己的仓库内

### 		3.clone项目到本地（以fuwari为例）

```cmd
git clone git@github.com:saicaca/fuwari.git
```

## ***二.对博客进行配置***

### 	1.安装依赖

​	安装依赖项，控制台键入代码：

```cmd
npm i
```

​	此时你的Blog应该就可以跑起来了

​	键入：

```cmd
npm run dev
```

​	查看控制台输出，复制

### 	2.修改配置文件

​	*此处推荐使用[Vscode](https://code.visualstudio.com/)进行编辑*

​	在Blog文件夹根目录下右键空白处选择在Vscode中打开找到config.ts

​	
