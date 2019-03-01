---
layout:     single
title:      "滑动窗口最大值"
date:       2016-08-27 21:30:00 +0800
categories: [leetcode]
tags:       [heap]
permalink:  /sliding-window-maximum/
---

## 239. 滑动窗口最大值 (Hard)

<p>给定一个数组 <em>nums</em>，有一个大小为&nbsp;<em>k&nbsp;</em>的滑动窗口从数组的最左侧移动到数组的最右侧。你只可以看到在滑动窗口 <em>k</em> 内的数字。滑动窗口每次只向右移动一位。</p>

<p>返回滑动窗口最大值。</p>

<p><strong>示例:</strong></p>

<pre><strong>输入:</strong> <em>nums</em> = <code>[1,3,-1,-3,5,3,6,7]</code>, 和 <em>k</em> = 3
<strong>输出: </strong><code>[3,3,5,5,6,7] 
<strong>解释: 
</strong></code>
  滑动窗口的位置                最大值
---------------               -----
[1  3  -1] -3  5  3  6  7       3
 1 [3  -1  -3] 5  3  6  7       3
 1  3 [-1  -3  5] 3  6  7       5
 1  3  -1 [-3  5  3] 6  7       5
 1  3  -1  -3 [5  3  6] 7       6
 1  3  -1  -3  5 [3  6  7]      7</pre>

<p><strong>注意：</strong></p>

<p>你可以假设 <em>k </em>总是有效的，1 &le; k &le;&nbsp;输入数组的大小，且输入数组不为空。</p>

<p><strong>进阶：</strong></p>

<p>你能在线性时间复杂度内解决此题吗？</p>

### 相关话题
  [[堆](https://github.com/openset/leetcode/tree/master/tag/heap/README.md)]

### 相似题目
  1. [最小覆盖子串](/minimum-window-substring) (Hard)
  1. [最小栈](/min-stack) (Easy)
  1. [Longest Substring with At Most Two Distinct Characters](/longest-substring-with-at-most-two-distinct-characters) (Hard)
  1. [Paint House II](/paint-house-ii) (Hard)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/sliding-window-maximum)