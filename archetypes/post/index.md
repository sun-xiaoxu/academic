---
title: "{{ replace .Name "-" " " | title }}"
subtitle: ""
summary: ""  #所有博客页面中,文章的简述
authors: [admin]	# 作者不用改
tags: [标签]
categories: [分类]
date: {{ .Date }}
lastmod: {{ .Date }}
featured: false
draft: false
type:	book  # 只有book带目录
toc:	true # 是否带目录
diagram: true #是否支持图表
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
