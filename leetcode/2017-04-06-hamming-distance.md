---
layout:     single
title:      "汉明距离"
date:       2017-04-06 21:30:00 +0800
categories: [leetcode]
tags:       [Bit Manipulation]
permalink:  /hamming-distance/
---

## 461. 汉明距离 (Easy)

<p>两个整数之间的<a href="https://baike.baidu.com/item/%E6%B1%89%E6%98%8E%E8%B7%9D%E7%A6%BB">汉明距离</a>指的是这两个数字对应二进制位不同的位置的数目。</p>

<p>给出两个整数 <code>x</code> 和 <code>y</code>，计算它们之间的汉明距离。</p>

<p><strong>注意：</strong><br />
0 &le; <code>x</code>, <code>y</code> &lt; 2<sup>31</sup>.</p>

<p><strong>示例:</strong></p>

<pre>
<strong>输入:</strong> x = 1, y = 4

<strong>输出:</strong> 2

<strong>解释:</strong>
1   (0 0 0 1)
4   (0 1 0 0)
       &uarr;   &uarr;

上面的箭头指出了对应二进制位不同的位置。
</pre>

### 相关话题
  [[位运算](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]

### 相似题目
  1. [位1的个数](/number-of-1-bits) (Easy)
  1. [汉明距离总和](/total-hamming-distance) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/hamming-distance)