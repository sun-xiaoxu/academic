---
subtitle: "" # 不知道干啥用的
diagram: true #是否支持图表
date: {{ .Date }}
authors: [admin]	# 作者不用改
title: "{{ replace .Name "-" " " | title }}"
lastmod: {{ .Date }}
draft: false
featured: false
type:	book  # 只有book带目录
toc:	true # 是否带目录

#######################################修改下面的就行#######################################
summary: ""  #所有博客页面中,文章的简述
tags: [标签]
categories: [分类]

image:
  caption: ""
  focal_point: ""
  preview_only: false
---

