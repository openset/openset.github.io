---
layout:     single
title:      "为高尔夫比赛砍树"
date:       2017-11-06 21:30:00 +0800
categories: [leetcode]
tags:       [Breadth-first Search]
permalink:  /cut-off-trees-for-golf-event/
---

## 675. 为高尔夫比赛砍树 (Hard)

<p>你被请来给一个要举办高尔夫比赛的树林砍树. 树林由一个非负的二维数组表示， 在这个数组中：</p>

<ol>
	<li><code>0</code> 表示障碍，无法触碰到.</li>
	<li><code>1</code>&nbsp;表示可以行走的地面.</li>
	<li><code>比1大的数</code>&nbsp;表示一颗允许走过的树的高度.</li>
</ol>

<p>你被要求按照树的高度从低向高砍掉所有的树，每砍过一颗树，树的高度变为1。</p>

<p>你将从（0，0）点开始工作，你应该返回你砍完所有树需要走的最小步数。 如果你无法砍完所有的树，返回 -1 。</p>

<p>可以保证的是，没有两棵树的高度是相同的，并且至少有一颗树需要你砍。</p>

<p><strong>示例&nbsp;1:</strong></p>

<pre>
<strong>输入:</strong> 
[
 [1,2,3],
 [0,0,4],
 [7,6,5]
]
<strong>输出:</strong> 6
</pre>

<p>&nbsp;</p>

<p><strong>示例&nbsp;2:</strong></p>

<pre>
<strong>输入:</strong> 
[
 [1,2,3],
 [0,0,0],
 [7,6,5]
]
<strong>输出:</strong> -1
</pre>

<p>&nbsp;</p>

<p><strong>示例&nbsp;3:</strong></p>

<pre>
<strong>输入:</strong> 
[
 [2,3,4],
 [0,0,5],
 [8,7,6]
]
<strong>输出:</strong> 6

<strong>解释:</strong> (0,0) 位置的树，你可以直接砍去，不用算步数
</pre>

<p>&nbsp;</p>

<p><strong>提示</strong>: 矩阵大小不会超过 50x50 。</p>

### 相关话题
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/cut-off-trees-for-golf-event)