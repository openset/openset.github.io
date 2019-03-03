---
layout:     single
title:      "连接词"
date:       2017-04-17 21:30:00 +0800
categories: [leetcode]
tags:       [Depth-first Search, Trie, Dynamic Programming]
permalink:  /concatenated-words/
---

## 472. 连接词 (Hard)

<p>给定一个<strong>不含重复</strong>单词的列表，编写一个程序，返回给定单词列表中所有的连接词。</p>

<p>连接词的定义为：一个字符串完全是由至少两个给定数组中的单词组成的。</p>

<p><strong>示例:</strong></p>

<pre>
<strong>输入:</strong> [&quot;cat&quot;,&quot;cats&quot;,&quot;catsdogcats&quot;,&quot;dog&quot;,&quot;dogcatsdog&quot;,&quot;hippopotamuses&quot;,&quot;rat&quot;,&quot;ratcatdogcat&quot;]

<strong>输出:</strong> [&quot;catsdogcats&quot;,&quot;dogcatsdog&quot;,&quot;ratcatdogcat&quot;]

<strong>解释:</strong> &quot;catsdogcats&quot;由&quot;cats&quot;, &quot;dog&quot; 和 &quot;cats&quot;组成; 
     &quot;dogcatsdog&quot;由&quot;dog&quot;, &quot;cats&quot;和&quot;dog&quot;组成; 
     &quot;ratcatdogcat&quot;由&quot;rat&quot;, &quot;cat&quot;, &quot;dog&quot;和&quot;cat&quot;组成。
</pre>

<p><strong>说明:</strong></p>

<ol>
	<li>给定数组的元素总数不超过 <code>10000</code>。</li>
	<li>给定数组中元素的长度总和不超过 <code>600000</code>。</li>
	<li>所有输入字符串只包含小写字母。</li>
	<li>不需要考虑答案输出的顺序。</li>
</ol>

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[字典树](https://github.com/openset/leetcode/tree/master/tag/trie/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [单词拆分 II](/word-break-ii) (Hard)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/concatenated-words)