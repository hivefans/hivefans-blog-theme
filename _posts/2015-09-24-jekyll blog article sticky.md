---
layout: post
title:  "在jekyll博客中如何实现置顶文章功能"
keywords: "jekyll top 置顶"
description: "在jekyll博客中如何实现置顶文章功能"
category: [devops]
tags: [jekyll,top]
---

最近刚开始用jekyll搭建博客，模板用的[javachen的博客](http://blog.javachen.com)模板
这个模板中实现了大多数博客中的功能

- 文章评论功能
- 标签云tag cloud
- 文章read more功能

可是没有实现首页文章置顶功能，网上搜索了一下，找到一个实现方法

在想要置顶文章post中添加一个置顶类

 修改index.html模板代码
<script src="https://gist.github.com/tamouse/a160be1cb467f611c9ba.js"></script>