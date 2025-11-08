---  
title: Fuwari 简明指南  
published: 2024-04-01  
description: "如何使用此博客模板。"  
image: "./cover.jpeg"  
tags: ["Fuwari", "博客", "自定义"]  
category: 指南  
draft: false  
---

> 封面图来源：[Source](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/208fc754-890d-4adb-9753-2c963332675d/width=2048/01651-1456859105-(colour_1.5),girl,_Blue,yellow,green,cyan,purple,red,pink,_best,8k,UHD,masterpiece,male%20focus,%201boy,gloves,%20ponytail,%20long%20hair,.jpeg)

此博客模板基于 [Astro](https://astro.build/) 构建。本指南未涉及的内容，您可以在 [Astro 文档](https://docs.astro.build/) 中找到答案。

## 文章 Front-matter 设置

```yaml
---
title: 我的第一篇博客文章
published: 2023-09-09
description: 这是我的新 Astro 博客的第一篇文章。
image: ./cover.jpg
tags: [示例标签1, 示例标签2]
category: 前端
draft: false
---
```

| 属性          | 描述                                                                                                                                                             |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `title`       | 文章的标题。                                                                                                                                                    |
| `published`   | 文章的发布日期。                                                                                                                                                |
| `description` | 文章的简短描述。会在首页显示。                                                                                                                                  |
| `image`       | 文章的封面图路径。<br/>1. 以 `http://` 或 `https://` 开头：使用网络图片<br/>2. 以 `/` 开头：指向 `public` 目录中的图片<br/>3. 无上述前缀：相对于 markdown 文件的路径 |
| `tags`        | 文章的标签。                                                                                                                                                    |
| `category`    | 文章的分类。                                                                                                                                                    |
| `draft`       | 是否为草稿（草稿不会显示）。                                                                                                                                    |

## 文章文件的存放位置

您的文章文件应放置在 `src/content/posts/` 目录下。您也可以创建子目录来更好地组织文章和资源文件。

```
src/content/posts/
├── 文章-1.md
└── 文章-2/
    ├── cover.png
    └── index.md
```
