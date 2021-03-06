---
layout:     single
title:      "超级丑数"
date:       2016-11-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Math, Dynamic Programming, Heap (Priority Queue)]
permalink:  /problems/super-ugly-number/
---

## 313. 超级丑数 (Medium)

{% raw %}

<p>编写一段程序来查找第 <code><em>n</em></code> 个超级丑数。</p>

<p>超级丑数是指其所有质因数都是长度为&nbsp;<code>k</code>&nbsp;的质数列表&nbsp;<code>primes</code>&nbsp;中的正整数。</p>

<p><strong>示例:</strong></p>

<pre><strong>输入:</strong> n = 12, <code>primes</code> = <code>[2,7,13,19]</code>
<strong>输出:</strong> 32 
<strong>解释: </strong>给定长度为 4 的质数列表 primes = [2,7,13,19]，前 12 个超级丑数序列为：[1,2,4,7,8,13,14,16,19,26,28,32] 。</pre>

<p><strong>说明:</strong></p>

<ul>
	<li><code>1</code>&nbsp;是任何给定&nbsp;<code>primes</code>&nbsp;的超级丑数。</li>
	<li>&nbsp;给定&nbsp;<code>primes</code>&nbsp;中的数字以升序排列。</li>
	<li>0 &lt; <code>k</code> &le; 100, 0 &lt; <code>n</code> &le; 10<sup>6</sup>, 0 &lt; <code>primes[i]</code> &lt; 1000 。</li>
	<li>第&nbsp;<code>n</code>&nbsp;个超级丑数确保在 32 位有符整数范围内。</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[堆（优先队列）](https://github.com/openset/leetcode/tree/master/tag/heap-priority-queue/README.md)]

### 相似题目
  1. [丑数 II](/problems/ugly-number-ii) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/super-ugly-number)
