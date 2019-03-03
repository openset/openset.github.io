---
layout:     single
title:      "猜数字大小"
date:       2017-01-09 21:30:00 +0800
categories: [leetcode]
tags:       [Binary Search]
permalink:  /guess-number-higher-or-lower/
---

## 374. 猜数字大小 (Easy)

<p>我们正在玩一个猜数字游戏。 游戏规则如下：<br>
我从&nbsp;<strong>1</strong>&nbsp;到&nbsp;<em><strong>n</strong></em>&nbsp;选择一个数字。 你需要猜我选择了哪个数字。<br>
每次你猜错了，我会告诉你这个数字是大了还是小了。<br>
你调用一个预先定义好的接口&nbsp;<code>guess(int num)</code>，它会返回 3 个可能的结果（<code>-1</code>，<code>1</code>&nbsp;或 <code>0</code>）：</p>

<pre>-1 : 我的数字比较小
 1 : 我的数字比较大
 0 : 恭喜！你猜对了！
</pre>

<p><strong>示例 :</strong></p>

<pre><strong>输入: </strong>n = 10, pick = 6
<strong>输出: </strong>6</pre>

### 相关话题
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

### 相似题目
  1. [第一个错误的版本](/first-bad-version) (Easy)
  1. [猜数字大小 II](/guess-number-higher-or-lower-ii) (Medium)
  1. [找到 K 个最接近的元素](/find-k-closest-elements) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/guess-number-higher-or-lower)