---
layout:     single
title:      "等差数列划分 II - 子序列"
date:       2017-03-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Dynamic Programming]
permalink:  /problems/arithmetic-slices-ii-subsequence/
---

## 446. 等差数列划分 II - 子序列 (Hard)

{% raw %}

<p>如果一个数列至少有三个元素，并且任意两个相邻元素之差相同，则称该数列为等差数列。</p>

<p>例如，以下数列为等差数列:</p>

<pre>
1, 3, 5, 7, 9
7, 7, 7, 7
3, -1, -5, -9</pre>

<p>以下数列不是等差数列。</p>

<pre>
1, 1, 2, 5, 7</pre>

<p> </p>

<p>数组 A 包含 N 个数，且索引从 0 开始。该数组<strong>子序列</strong>将划分为整数序列 (P<sub>0</sub>, P<sub>1</sub>, ..., P<sub>k</sub>)，满足 0 ≤ P<sub>0</sub> < P<sub>1</sub> < ... < P<sub>k</sub> < N。</p>

<p> </p>

<p>如果序列 A[P<sub>0</sub>]，A[P<sub>1</sub>]，...，A[P<sub>k-1</sub>]，A[P<sub>k</sub>] 是等差的，那么数组 A 的<strong>子序列</strong> (P0，P1，…，PK) 称为等差序列。值得注意的是，这意味着 k ≥ 2。</p>

<p>函数要返回数组 A 中所有等差子序列的个数。</p>

<p>输入包含 N 个整数。每个整数都在 -2<sup>31</sup> 和 2<sup>31</sup>-1 之间，另外 0 ≤ N ≤ 1000。保证输出小于 2<sup>31</sup>-1。</p>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入：</strong>[2, 4, 6, 8, 10]

<strong>输出：</strong>7

<strong>解释：</strong>
所有的等差子序列为：
[2,4,6]
[4,6,8]
[6,8,10]
[2,4,6,8]
[4,6,8,10]
[2,4,6,8,10]
[2,6,10]
</pre>

<p> </p>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [等差数列划分](/problems/arithmetic-slices) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/arithmetic-slices-ii-subsequence)
