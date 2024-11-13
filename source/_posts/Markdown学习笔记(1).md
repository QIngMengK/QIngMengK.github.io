---
abbrlink: ''
categories:
- - Markdown
date: '2024-11-13T19:12:22.945245+08:00'
tags:
- Markdown
title: Markdown学习笔记(1)
updated: '2024-11-13T19:12:26.042+08:00'
---
# Markdown 基本语法

Markdown是一种轻量级标记语言，排版语法简洁，让人们更多地关注内容本身而非排版。它使用易读易写的纯文本格式编写文档，可与HTML混编，可导出 HTML、PDF 以及本身的 .md 格式的文件。因简洁、高效、易读、易写，Markdown被大量使用，如Github、Wikipedia、简书等。

在线体验一下 [Markdown在线编辑器 **(opens new window)**](https://markdown.com.cn/editor/)。

千万不要被「标记」、「语言」吓到，Markdown的语法十分简单，常用的标记符号不超过十个，用于日常写作记录绰绰有余，不到半小时就能完全掌握。

就是这十个不到的标记符号，却能让人**优雅地沉浸式记录，专注内容而不是纠结排版**，达到「心中无尘，码字入神」的境界。

让我们从 [Markdown 标题语法 **(opens new window)**](https://markdown.com.cn/basic-syntax/headings.html)开始学习吧。


# Markdown 标题语法

要创建标题，请在单词或短语前面添加井号 (`#`) 。`#` 的数量代表了标题的级别。例如，添加三个 `#` 表示创建一个三级标题 (`<h3>`) (例如：`### My Header`)。


| Markdown语法             | HTML                       | 预览效果               |
| ------------------------ | -------------------------- | ---------------------- |
| `# Heading level 1`      | `<h1>Heading level 1</h1>` | # Heading level 1      |
| `## Heading level 2`     | `<h2>Heading level 2</h2>` | ## Heading level 2     |
| `### Heading level 3`    | `<h3>Heading level 3</h3>` | ### Heading level 3    |
| `#### Heading level 4`   | `<h4>Heading level 4</h4>` | #### Heading level 4   |
| `##### Heading level 5`  | `<h5>Heading level 5</h5>` | ##### Heading level 5  |
| `###### Heading level 6` | `<h6>Heading level 6</h6>` | ###### Heading level 6 |

## [#](https://markdown.com.cn/basic-syntax/headings.html#%E5%8F%AF%E9%80%89%E8%AF%AD%E6%B3%95)可选语法

还可以在文本下方添加任意数量的 == 号来标识一级标题，或者 -- 号来标识二级标题。


| Markdown语法                     | HTML                       | 预览效果           |
| -------------------------------- | -------------------------- | ------------------ |
| `Heading level 1===============` | `<h1>Heading level 1</h1>` | # Heading level 1  |
| `Heading level 2---------------` | `<h2>Heading level 2</h2>` | ## Heading level 2 |

## [#](https://markdown.com.cn/basic-syntax/headings.html#%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5)最佳实践

不同的 Markdown 应用程序处理 `#` 和标题之间的空格方式并不一致。为了兼容考虑，请用一个空格在 `#` 和标题之间进行分隔。


| ✅  Do this          | ❌  Don't do this   |
| -------------------- | ------------------- |
| `# Here's a Heading` | `#Here's a Heading` |
