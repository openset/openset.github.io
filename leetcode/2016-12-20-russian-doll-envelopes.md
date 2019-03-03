---
layout:     single
title:      "俄罗斯套娃信封问题"
date:       2016-12-20 21:30:00 +0800
categories: [leetcode]
tags:       [Binary Search, Dynamic Programming]
permalink:  /russian-doll-envelopes/
---

## 354. 俄罗斯套娃信封问题 (Hard)

<p>给定一些标记了宽度和高度的信封，宽度和高度以整数对形式&nbsp;<code>(w, h)</code>&nbsp;出现。当另一个信封的宽度和高度都比这个信封大的时候，这个信封就可以放进另一个信封里，如同俄罗斯套娃一样。</p>

<p>请计算最多能有多少个信封能组成一组&ldquo;俄罗斯套娃&rdquo;信封（即可以把一个信封放到另一个信封里面）。</p>

<p><strong>说明:</strong><br>
不允许旋转信封。</p>

<p><strong>示例:</strong></p>

<pre><strong>输入:</strong> envelopes = <code>[[5,4],[6,4],[6,7],[2,3]]</code>
<strong>输出:</strong> 3 
<strong>解释:</strong> 最多信封的个数为 <code>3, 组合为: </code>[2,3] =&gt; [5,4] =&gt; [6,7]。
</pre>

### 相关话题
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [最长上升子序列](/longest-increasing-subsequence) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/russian-doll-envelopes)