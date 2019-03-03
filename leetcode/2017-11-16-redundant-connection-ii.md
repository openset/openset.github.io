---
layout:     single
title:      "冗余连接 II"
date:       2017-11-16 21:30:00 +0800
categories: [leetcode]
tags:       [Tree, Depth-first Search, Union Find, Graph]
permalink:  /redundant-connection-ii/
---

## 685. 冗余连接 II (Hard)

<p>在本问题中，有根树指满足以下条件的<strong>有向</strong>图。该树只有一个根节点，所有其他节点都是该根节点的后继。每一个节点只有一个父节点，除了根节点没有父节点。</p>

<p>输入一个有向图，该图由一个有着N个节点 (节点值不重复1, 2, ..., N) 的树及一条附加的边构成。附加的边的两个顶点包含在1到N中间，这条附加的边不属于树中已存在的边。</p>

<p>结果图是一个以<code>边</code>组成的二维数组。 每一个<code>边</code> 的元素是一对 <code>[u, v]</code>，用以表示<strong>有向</strong>图中连接顶点 <code>u</code> and <code>v</code>和顶点的边，其中父节点<code>u</code>是子节点<code>v</code>的一个父节点。</p>

<p>返回一条能删除的边，使得剩下的图是有N个节点的有根树。若有多个答案，返回最后出现在给定二维数组的答案。</p>

<p><strong>示例&nbsp;1:</strong></p>

<pre>
<strong>输入:</strong> [[1,2], [1,3], [2,3]]
<strong>输出:</strong> [2,3]
<strong>解释:</strong> 给定的有向图如下:
  1
 / \
v   v
2--&gt;3
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> [[1,2], [2,3], [3,4], [4,1], [1,5]]
<strong>输出:</strong> [4,1]
<strong>解释:</strong> 给定的有向图如下:
5 &lt;- 1 -&gt; 2
     ^    |
     |    v
     4 &lt;- 3
</pre>

<p><strong>注意:</strong></p>

<ul>
	<li>二维数组大小的在3到1000范围内。</li>
	<li>二维数组中的每个整数在1到N之间，其中 N 是二维数组的大小。</li>
</ul>

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[并查集](https://github.com/openset/leetcode/tree/master/tag/union-find/README.md)]
  [[图](https://github.com/openset/leetcode/tree/master/tag/graph/README.md)]

### 相似题目
  1. [冗余连接](/redundant-connection) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/redundant-connection-ii)