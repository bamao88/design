+++
title = "示例 App"
description = "建议拷贝后使用"
weight = 10

[extra]
local_image = "/projects/project-1.jpg"
#link_to = "https://github.com/not-matthias/apollo"
+++

# 起源（一级标题）

## 我们喜爱旅行（二级标题）

### 以及更多


注释掉一段内容（回头再使用）

<!-- 注释内容在这里，不会显示,blabla -->
<!-- 注释内容在这里，不会显示,blabla -->

Here can


## 插入视频

（推荐将视频放在对应文件夹下面）

-{-{ video(src="demors/hand.mp4") }}


## 插入图片

### 使用相对路径（推荐方式）

<!-- -{-{ img(src="./demors/qulvxing.png", text="The default fit for images is fit to screen") }} -->

单独文件夹（不可用，很奇怪）

{{ img(src="demors/qulvxing.png") }}

--not working--
-{-{ gallery() }}

### 其他方式，需要添加 /content/ 之后的路径，如

HTML 格式写法：

单独文件夹：

<img src="/projects/demors/qulvxing.png" />

Markdown 格式写法：

单独文件夹：

![Markdown 格式写法 2](/projects/demors/project-1.jpg)


Insert Figma:

Figma 链接，请点击右上角全屏查看

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="100%" height="1000" src="https://embed.figma.com/proto/FwhW362CHL0BVo1G8iCqii/%E5%8E%BB%E6%97%85%E8%A1%8C%E4%BD%9C%E5%93%81%E9%9B%86%E6%8E%92%E7%89%881013-(%E5%85%AC%E5%BC%80)?page-id=0%3A1&node-id=4322-10943&node-type=canvas&viewport=5650%2C355%2C0.26&scaling=min-zoom&content-scaling=fixed&embed-host=share" allowfullscreen></iframe>


Done
