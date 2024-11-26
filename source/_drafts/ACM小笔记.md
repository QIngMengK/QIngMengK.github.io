---
abbrlink: ''
categories: []
date: '2024-11-26T19:09:02.689821+08:00'
tags: []
title: ACM小笔记
updated: '2024-11-26T19:09:11.656+08:00'
---
# 图论

## 链式向前星存图

```
void add(int a,int b,int c)
{
	e[idx] = b,w[idx] = c,ne[idx] = h[a],h[a] = idx++;
}
```

分析 : 用 $h[a]$ 表示a这个节点的链，将与 $a$ 相邻的节点按照输入的顺序头插到 $a$ 这个链表中。用 $ne$ 数组指向 $a$ 形成双向链表

