---
layout:     single
title:      "检查二进制字符串字段"
date:       2020-11-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy]
permalink:  /problems/check-if-binary-string-has-at-most-one-segment-of-ones/
---

## 1784. 检查二进制字符串字段 (Easy)

{% raw %}

<p>给你一个二进制字符串 <code>s</code> ，该字符串 <strong>不含前导零</strong> 。</p>

<p>如果 <code>s</code> 最多包含 <strong>一个由连续的 <code>'1'</code> 组成的字段</strong> ，返回 <code>true</code>​​​ 。否则，返回 <code>false</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "1001"
<strong>输出：</strong>false
<strong>解释：</strong>字符串中的 1 没有形成一个连续字段。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = "110"
<strong>输出：</strong>true</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= s.length <= 100</code></li>
	<li><code>s[i]</code>​​​​ 为 <code>'0'</code> 或 <code>'1'</code></li>
	<li><code>s[0]</code> 为 <code>'1'</code></li>
</ul>

{% endraw %}

### 相关话题
  [[贪心算法](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/check-if-binary-string-has-at-most-one-segment-of-ones)