---
layout:     single
title:      "汉明距离总和"
date:       2017-04-22 21:30:00 +0800
categories: [leetcode]
tags:       [bit-manipulation]
permalink:  /total-hamming-distance/
---

## 477. 汉明距离总和 (Medium)

<p>两个整数的&nbsp;<a href="https://baike.baidu.com/item/%E6%B1%89%E6%98%8E%E8%B7%9D%E7%A6%BB/475174?fr=aladdin">汉明距离</a> 指的是这两个数字的二进制数对应位不同的数量。</p>

<p>计算一个数组中，任意两个数之间汉明距离的总和。</p>

<p><strong>示例:</strong></p>

<pre>
<strong>输入:</strong> 4, 14, 2

<strong>输出:</strong> 6

<strong>解释:</strong> 在二进制表示中，4表示为0100，14表示为1110，2表示为0010。（这样表示是为了体现后四位之间关系）
所以答案为：
HammingDistance(4, 14) + HammingDistance(4, 2) + HammingDistance(14, 2) = 2 + 2 + 2 = 6.
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li>数组中元素的范围为从&nbsp;<code>0</code>到&nbsp;<code>10^9</code>。</li>
	<li>数组的长度不超过&nbsp;<code>10^4</code>。</li>
</ol>

### 相关话题
  [[位运算](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]

### 相似题目
  1. [汉明距离](/hamming-distance) (Easy)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/total-hamming-distance)