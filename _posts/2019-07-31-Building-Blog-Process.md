---
layout: post
title:  "Building Blog Process"
date:   2019-07-31 
author: Alan Lemon
categories: Blog
tags: learn,jekyll,github page
---

#### 第一篇

分享下编写学习搭建博客的过程：

github page +jekyll:

> *引用自官网*：
> Jekyll 是一个简单的博客形态的静态站点生产机器。它有一个模版目录，其中包含原始文本格式的文档，通过一个转换器（如 [Markdown](https://link.jianshu.com?t=http%3A%2F%2Fdaringfireball.net%2Fprojects%2Fmarkdown%2F)）和我们的 [Liquid](https://link.jianshu.com?t=https%3A%2F%2Fgithub.com%2FShopify%2Fliquid%2Fwiki) 渲染器转化成一个完整的可发布的静态网站，你可以发布在任何你喜爱的服务器上。Jekyll 也可以运行在 [GitHub Page](https://link.jianshu.com?t=http%3A%2F%2Fpages.github.com%2F) 上，也就是说，你可以使用 GitHub 的服务来搭建你的项目页面、博客或者网站，而且是**完全免费**的。

> 1. 配置ruby环境
>
> https://rubyinstaller.org/downloads/
>
> 2. 安装bundler
>
> ```ruby
> gem install jekyll bundler
> ```
>
> 3. 创建博客或者下载主题
>
> ```ruby
> jekyll new blog
> bundle exec jekyll serve //本地启动 localhost:4000
> ```
>
>    或者下载主题http://jekyllthemes.org/
>
> ```ruby
> bundle install
> bundle exec jekyll serve //本地启动 localhost:4000
> ```
>
>    4.如不需要安装bundler，可直接运行以下命令
>
> ```ruby
> jekyll server //也可以启动项目。
> ```
>
> jekyll文档路径：https://jekyllrb.com/docs

   

