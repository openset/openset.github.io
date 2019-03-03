---
layout:     single
title:      "猜数字大小 II"
date:       2017-01-10 21:30:00 +0800
categories: [leetcode]
tags:       [Minimax, Dynamic Programming]
permalink:  /guess-number-higher-or-lower-ii/
---

## 375. 猜数字大小 II (Medium)

<p>我们正在玩一个猜数游戏，游戏规则如下：</p>

<p>我从&nbsp;<strong>1&nbsp;</strong>到 <strong>n</strong> 之间选择一个数字，你来猜我选了哪个数字。</p>

<p>每次你猜错了，我都会告诉你，我选的数字比你的大了或者小了。</p>

<p>然而，当你猜了数字 x 并且猜错了的时候，你需要支付金额为 x 的现金。直到你猜到我选的数字，你才算赢得了这个游戏。</p>

<p><strong>示例:</strong></p>

<pre>n = 10, 我选择了8.

第一轮: 你猜我选择的数字是5，我会告诉你，我的数字更大一些，然后你需要支付5块。
第二轮: 你猜是7，我告诉你，我的数字更大一些，你支付7块。
第三轮: 你猜是9，我告诉你，我的数字更小一些，你支付9块。

游戏结束。8 就是我选的数字。

你最终要支付 5 + 7 + 9 = 21 块钱。
</pre>

<p>给定&nbsp;<strong>n &ge; 1，</strong>计算你至少需要拥有多少现金才能确保你能赢得这个游戏。</p>

### 相关话题
  [[极小化极大](https://github.com/openset/leetcode/tree/master/tag/minimax/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [Flip Game II](/flip-game-ii) (Medium)
  1. [猜数字大小](/guess-number-higher-or-lower) (Easy)
  1. [我能赢吗](/can-i-win) (Medium)
  1. [找到 K 个最接近的元素](/find-k-closest-elements) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/guess-number-higher-or-lower-ii)