---
# 含义|值类型|默认值
layout: # 布局模版|String|-
title: {{ title }} # 页面标题|String|-
seo_title: # 网页标题|String|page.title
short_title: # 页面标题（在group列表中显示）|String|page.title
date: {{ date }} # 创建时间|Date|文件创建时间
updated: # 更新日期|Date|文件修改时间
link: # 外部文章网址|String|-
music: # 内部音乐控件|[Object]|-
  # - server: # netease, tencent, kugou, xiami, baidu
  # - type: # song, playlist, album, search, artist
  # - id: # song id / playlist id / album id / search keyword
robots: #robots|String|-
keywords: # 页面关键词|String|-
description: # 页面描述、摘要|String|-
cover: # 是否显示封面	|Bool|true
top_meta: #	是否显示文章或页面顶部的meta信息|Bool|true
bottom_meta: # 是否显示文章或页面底部的meta信息|Bool|true
sidebar:[] # 页面侧边栏|Bool, Array|theme.layout.*.sidebar
body: #	页面主体元素|Array|theme.layout.on_page.body
mathjax: # 是否渲染公式|Bool, String|false
thumbnail: # 缩略图|String|false
icons: # 图标|Array|[]
pin: # 是否置顶|Bool|false
headimg: #文章头图|url|-
comments: # false 默认开启
mathjax: # false: 不渲染, true: 渲染|默认不渲染
---
