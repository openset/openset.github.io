---
layout:     single
title:      "计数二进制子串"
date:       2017-11-27 21:30:00 +0800
categories: [leetcode]
tags:       [String]
permalink:  /count-binary-substrings/
---

## 696. 计数二进制子串 (Easy)

<p>给定一个字符串&nbsp;<code>s</code>，计算具有相同数量0和1的非空(连续)子字符串的数量，并且这些子字符串中的所有0和所有1都是组合在一起的。</p>

<p>重复出现的子串要计算它们出现的次数。</p>

<p><strong>示例 1 :</strong></p>

<pre>
<strong>输入:</strong> &quot;00110011&quot;
<strong>输出:</strong> 6
<strong>解释:</strong> 有6个子串具有相同数量的连续1和0：&ldquo;0011&rdquo;，&ldquo;01&rdquo;，&ldquo;1100&rdquo;，&ldquo;10&rdquo;，&ldquo;0011&rdquo; 和 &ldquo;01&rdquo;。

请注意，一些重复出现的子串要计算它们出现的次数。

另外，&ldquo;00110011&rdquo;不是有效的子串，因为所有的0（和1）没有组合在一起。
</pre>

<p><strong>示例 2 :</strong></p>

<pre>
<strong>输入:</strong> &quot;10101&quot;
<strong>输出:</strong> 4
<strong>解释:</strong> 有4个子串：&ldquo;10&rdquo;，&ldquo;01&rdquo;，&ldquo;10&rdquo;，&ldquo;01&rdquo;，它们具有相同数量的连续1和0。
</pre>

<p><strong>注意：</strong></p>

<ul>
	<li><code>s.length</code>&nbsp;在1到50,000之间。</li>
	<li><code>s</code>&nbsp;只包含&ldquo;0&rdquo;或&ldquo;1&rdquo;字符。</li>
</ul>

### 相关话题
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### 相似题目
  1. [Encode and Decode Strings](/encode-and-decode-strings) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/count-binary-substrings)