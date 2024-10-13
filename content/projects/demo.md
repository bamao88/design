+++
title = "示例 App"
description = "建议拷贝后使用"
weight = 1

[extra]
local_image = "/projects/project-1.jpg"
#link_to = "https://github.com/not-matthias/apollo"
+++

# 起源（一级标题）

## 我们喜爱旅行（二级标题）

### 以及更多


注释掉一段内容（回头再使用）

<!-- 注释内容在这里，不会显示 -->


## 插入视频

（推荐将视频放在对应文件夹下面）

{{ video(src="demo/hand.mp4") }}


## 插入图片

### 使用相对路径（推荐方式）

<!-- -{-{ img(src="./demo/qulvxing.png", text="The default fit for images is fit to screen") }} -->

当前文件夹（可用）

{{ img(src="demo/qulvxing.png") }}


单独文件夹（不可用，很奇怪）

{{ img(src="project-1.jpg") }}


{{ img(src="project-1.jpg") }}


--not working--
-{-{ gallery() }}

### 其他方式，需要添加 /content/ 之后的路径，如


HTML 格式写法：

当前文件夹：

<img src="/projects/project-1.jpg" />


单独文件夹：

<img src="/projects/demo/qulvxing.png" />

Markdown 格式写法：

当前文件夹：

![Markdown 格式写法 1](/projects/project-1.jpg)


单独文件夹：

![Markdown 格式写法 2](/projects/demo/project-1.jpg)


