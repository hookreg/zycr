---
id: "DEV-001"
title: "我的第一篇 Markdown 技术日志"
date: 2026-08-25
draft: false

entry_type: "tutorial"

tags:
  - Hugo
  - Blog

description: "测试新的 Markdown 自动博客系统。"
---

这是我的第一篇 Markdown 技术日志。

如果这里能正常显示，说明 Markdown 博客已经成功。

## 1. 一级正文标题

这里是普通正文。

正文应该明显比标题更低调、更适合长时间阅读。

### 1.1 二级正文标题

继续写正文。

#### 1.1.1 三级正文标题

更细一级的内容。

## 2. 代码

```python
import torch

x = torch.randn(32, 512)

print(x.shape)
```

## 3. 数学公式

行内公式：

\(
x \in \mathbb{R}^{d}
\)

独立公式：

$$
\mathcal{L}
=
\frac{1}{N}
\sum_{i=1}^{N}
(y_i-\hat y_i)^2
$$

## 4. 表格

| 参数 | 数值 |
|---|---:|
| batch size | 32 |
| epochs | 100 |

## 5. 引用

> 如果这里正常显示，说明文章模板工作正常。

## 6. 总结

以后我只需要创建 Markdown 文件。
