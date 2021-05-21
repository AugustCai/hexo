---
title: Hexo Common Command
date: 2021-05-19 00:37:49
tags:
    - IT技术
    - Hexo
comments: false
categories:
	- 随手记
meta:
	- name="robots";content="noindex, follow"
	- name="another-meta";value="hello world";enabled=false
description: hexo common command record
---

## Hexo Common Command

### Common Command

```
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo generate #生成静态页面至public目录
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy #部署到GitHub
hexo help  # 查看帮助
hexo version  #查看Hexo的版本
```

### Command Abbreviations

```
hexo n == hexo new
hexo g == hexo generate
hexo s == hexo server
hexo d == hexo deploy
```

### Combined Command

```
hexo s -g #生成并本地预览
hexo d -g #生成并上传
```

