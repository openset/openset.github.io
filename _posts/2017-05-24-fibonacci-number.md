---
layout:     single
title:      "斐波那契数"
date:       2017-05-24 21:30:00 +0800
categories: [Leetcode]
tags:       [Array]
permalink:  /problems/fibonacci-number/
---

## 509. 斐波那契数 (Easy)

{% raw %}

<p><strong>斐波那契数</strong>，通常用&nbsp;<code>F(n)</code> 表示，形成的序列称为<strong>斐波那契数列</strong>。该数列由&nbsp;<code>0</code> 和 <code>1</code> 开始，后面的每一项数字都是前面两项数字的和。也就是：</p>

<pre>F(0) = 0,&nbsp; &nbsp;F(1)&nbsp;= 1
F(N) = F(N - 1) + F(N - 2), 其中 N &gt; 1.
</pre>

<p>给定&nbsp;<code>N</code>，计算&nbsp;<code>F(N)</code>。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>2
<strong>输出：</strong>1
<strong>解释：</strong>F(2) = F(1) + F(0) = 1 + 0 = 1.
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>3
<strong>输出：</strong>2
<strong>解释：</strong>F(3) = F(2) + F(1) = 1 + 1 = 2.
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>4
<strong>输出：</strong>3
<strong>解释：</strong>F(4) = F(3) + F(2) = 2 + 1 = 3.
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>0 &le; <code>N</code> &le; 30</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### 相似题目
  1. [爬楼梯](/problems/climbing-stairs) (Easy)
  1. [将数组拆分成斐波那契序列](/problems/split-array-into-fibonacci-sequence) (Medium)
  1. [最长的斐波那契子序列的长度](/problems/length-of-longest-fibonacci-subsequence) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/fibonacci-number)