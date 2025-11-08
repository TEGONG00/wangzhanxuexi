---  
title: Markdown 扩展功能  
published: 2024-05-01  
updated: 2024-11-29  
description: '了解更多关于 Fuwari 中的 Markdown 功能'  
image: ''  
tags: [演示, 示例, Markdown, Fuwari]  
category: '示例'  
draft: false  
---

## GitHub 仓库卡片
您可以添加动态卡片链接到 GitHub 仓库，页面加载时，仓库信息将从 GitHub API 拉取。

::github{repo="Fabrizz/MMM-OnSpotify"}

使用代码 `::github{repo="<所有者>/<仓库名>"}` 创建 GitHub 仓库卡片。

```markdown
::github{repo="saicaca/fuwari"}
```

## 提示框

支持以下类型的提示框：`note` `tip` `important` `warning` `caution`

:::note
突出显示用户应该考虑的信息，即使在快速浏览时也是如此。
:::

:::tip
帮助用户更成功的可选信息。
:::

:::important
用户成功所需的关键信息。
:::

:::warning
由于潜在风险而需要用户立即关注的关键内容。
:::

:::caution
操作可能带来的负面后果。
:::

### 基本语法

```markdown
:::note
突出显示用户应该考虑的信息，即使在快速浏览时也是如此。
:::

:::tip
帮助用户更成功的可选信息。
:::
```

### 自定义标题

提示框的标题可以自定义。

:::note[我的自定义标题]
这是一个带有自定义标题的笔记。
:::

```markdown
:::note[我的自定义标题]
这是一个带有自定义标题的笔记。
:::
```

### GitHub 语法

> [!TIP]
> [GitHub 语法](https://github.com/orgs/community/discussions/16925) 同样受支持。

```
> [!NOTE]
> GitHub 语法同样受支持。

> [!TIP]
> GitHub 语法同样受支持。
```

### 隐藏文本

您可以为文本添加隐藏效果。该文本也支持 **Markdown** 语法。

这个内容 :spoiler[是隐藏的 **哈哈**]！

```markdown
这个内容 :spoiler[是隐藏的 **哈哈**]！

```
