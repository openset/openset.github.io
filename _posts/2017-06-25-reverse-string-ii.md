---
layout:     single
title:      "反转字符串 II"
date:       2017-06-25 21:30:00 +0800
categories: [Leetcode]
tags:       [Two Pointers, String]
permalink:  /problems/reverse-string-ii/
---

## 541. 反转字符串 II (Easy)

{% raw %}

<p>给定一个字符串 <code>s</code> 和一个整数 <code>k</code>，你需要对从字符串开头算起的每隔&nbsp;<code>2k</code> 个字符的前 <code>k</code> 个字符进行反转。</p>

<ul>
	<li>如果剩余字符少于 <code>k</code> 个，则将剩余字符全部反转。</li>
	<li>如果剩余字符小于 <code>2k</code> 但大于或等于 <code>k</code> 个，则反转前 <code>k</code> 个字符，其余字符保持原样。</li>
</ul>

<p>&nbsp;</p>

<p><strong>示例:</strong></p>

<pre><strong>输入:</strong> s = &quot;abcdefg&quot;, k = 2
<strong>输出:</strong> &quot;bacdfeg&quot;
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li>该字符串只包含小写英文字母。</li>
	<li>给定字符串的长度和 <code>k</code> 在 <code>[1, 10000]</code> 范围内。</li>
</ol>

{% endraw %}

### 相关话题
  [[双指针](https://github.com/openset/leetcode/tree/master/tag/two-pointers/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### 相似题目
  1. [反转字符串](/problems/reverse-string) (Easy)
  1. [反转字符串中的单词 III](/problems/reverse-words-in-a-string-iii) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/reverse-string-ii)
