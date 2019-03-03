---
layout:     single
title:      "统计重复个数"
date:       2017-04-11 21:30:00 +0800
categories: [leetcode]
tags:       [Dynamic Programming]
permalink:  /count-the-repetitions/
---

## 466. 统计重复个数 (Hard)

<p>定义由 n 个连接的字符串 s 组成字符串 S，即&nbsp;<code>S = [s,n]</code>。例如，<code>[&quot;abc&quot;, 3]</code>=&ldquo;abcabcabc&rdquo;。</p>

<p>另一方面，如果我们可以从 s<sub>2&nbsp;</sub>中删除某些字符使其变为 s<sub>1</sub>，我们称字符串 s<sub>1&nbsp;</sub>可以从字符串 s<sub>2&nbsp;</sub>获得。例如，&ldquo;abc&rdquo; 可以根据我们的定义从 &ldquo;abdbec&rdquo; 获得，但不能从 &ldquo;acbbe&rdquo; 获得。</p>

<p>现在给出两个非空字符串 S<sub>1&nbsp;</sub>和 S<sub>2</sub>（每个最多 100 个字符长）和两个整数 0 &le; N<sub>1&nbsp;</sub>&le; 10<sup>6&nbsp;</sup>和 1 &le; N<sub>2&nbsp;</sub>&le; 10<sup>6</sup>。现在考虑字符串 S<sub>1&nbsp;</sub>和 S<sub>2</sub>，其中<code>S1=[s1,n1]</code>和<code>S2=[s2,n2]</code>。找出可以使<code>[S2,M]</code>从&nbsp;<code>S1</code>&nbsp;获得的最大整数 M。</p>

<p><strong>示例：</strong></p>

<pre>输入：
s1 =&quot;acb&quot;,n1 = 4
s2 =&quot;ab&quot;,n2 = 2

返回：
2
</pre>

### 相关话题
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/count-the-repetitions)