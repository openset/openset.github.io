---
layout:     single
title:      "给表达式添加运算符"
date:       2016-10-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, String, Backtracking]
permalink:  /problems/expression-add-operators/
---

## 282. 给表达式添加运算符 (Hard)

{% raw %}

<p>给定一个仅包含数字 <code>0-9</code> 的字符串和一个目标值，在数字之间添加 <strong>二元 </strong>运算符（不是一元）<code>+</code>、<code>-</code> 或 <code>*</code> ，返回所有能够得到目标值的表达式。</p>

<p> </p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> <code><em>num</em> = </code>"123", <em>target</em> = 6
<strong>输出: </strong>["1+2+3", "1*2*3"] 
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> <code><em>num</em> = </code>"232", <em>target</em> = 8
<strong>输出: </strong>["2*3+2", "2+3*2"]</pre>

<p><strong>示例 3:</strong></p>

<pre>
<strong>输入:</strong> <code><em>num</em> = </code>"105", <em>target</em> = 5
<strong>输出: </strong>["1*0+5","10-5"]</pre>

<p><strong>示例 4:</strong></p>

<pre>
<strong>输入:</strong> <code><em>num</em> = </code>"00", <em>target</em> = 0
<strong>输出: </strong>["0+0", "0-0", "0*0"]
</pre>

<p><strong>示例 5:</strong></p>

<pre>
<strong>输入:</strong> <code><em>num</em> = </code>"3456237490", <em>target</em> = 9191
<strong>输出: </strong>[]</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= num.length <= 10</code></li>
	<li><code>num</code> 仅含数字</li>
</ul>

{% endraw %}

### 相关话题
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[回溯](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]

### 相似题目
  1. [逆波兰表达式求值](/problems/evaluate-reverse-polish-notation) (Medium)
  1. [基本计算器](/problems/basic-calculator) (Hard)
  1. [基本计算器 II](/problems/basic-calculator-ii) (Medium)
  1. [为运算表达式设计优先级](/problems/different-ways-to-add-parentheses) (Medium)
  1. [目标和](/problems/target-sum) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/expression-add-operators)
