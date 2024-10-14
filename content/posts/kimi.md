+++
title = "借助 kimi 和 python 制作作品集"
date = "2024-10-13"
updated = "2024-10-14"

[taxonomies]
tags=["kimi", "python"]
+++


在制作作品集过程中，发现不太方便将 Figma 演示内容导出

向 kimi 提问，“使用 python 将 mov 文件转换为 gif 格式”

生成的反馈：

![kimi 1](xxx.png)


对应的 python 代码：

```python
import imageio

# 指定输入和输出文件名
input_file = 'input.mov'
output_file = 'output.gif'

# 读取视频
reader = imageio.get_reader(input_file)

# 写入 GIF 文件
with imageio.get_writer(output_file, mode='I') as writer:
    for frame in reader:
        writer.append_data(frame)

print(f"转换完成，输出文件：{output_file}")
```
