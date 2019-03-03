---
layout:     single
title:      "课程表"
date:       2016-07-26 21:30:00 +0800
categories: [leetcode]
tags:       [Depth-first Search, Breadth-first Search, Graph, Topological Sort]
permalink:  /course-schedule/
---

## 207. 课程表 (Medium)

<p>现在你总共有 <em>n</em> 门课需要选，记为&nbsp;<code>0</code>&nbsp;到&nbsp;<code>n-1</code>。</p>

<p>在选修某些课程之前需要一些先修课程。&nbsp;例如，想要学习课程 0 ，你需要先完成课程 1 ，我们用一个匹配来表示他们: <code>[0,1]</code></p>

<p>给定课程总量以及它们的先决条件，判断是否可能完成所有课程的学习？</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入:</strong> 2, [[1,0]] 
<strong>输出: </strong>true
<strong>解释:</strong>&nbsp;总共有 2 门课程。学习课程 1 之前，你需要完成课程 0。所以这是可能的。</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入:</strong> 2, [[1,0],[0,1]]
<strong>输出: </strong>false
<strong>解释:</strong>&nbsp;总共有 2 门课程。学习课程 1 之前，你需要先完成​课程 0；并且学习课程 0 之前，你还应先完成课程 1。这是不可能的。</pre>

<p><strong>说明:</strong></p>

<ol>
	<li>输入的先决条件是由<strong>边缘列表</strong>表示的图形，而不是邻接矩阵。详情请参见<a href="http://blog.csdn.net/woaidapaopao/article/details/51732947" target="_blank">图的表示法</a>。</li>
	<li>你可以假定输入的先决条件中没有重复的边。</li>
</ol>

<p><strong>提示:</strong></p>

<ol>
	<li>这个问题相当于查找一个循环是否存在于有向图中。如果存在循环，则不存在拓扑排序，因此不可能选取所有课程进行学习。</li>
	<li><a href="https://www.coursera.org/specializations/algorithms" target="_blank">通过 DFS 进行拓扑排序</a> - 一个关于Coursera的精彩视频教程（21分钟），介绍拓扑排序的基本概念。</li>
	<li>
	<p>拓扑排序也可以通过&nbsp;<a href="https://baike.baidu.com/item/%E5%AE%BD%E5%BA%A6%E4%BC%98%E5%85%88%E6%90%9C%E7%B4%A2/5224802?fr=aladdin&amp;fromid=2148012&amp;fromtitle=%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E6%90%9C%E7%B4%A2" target="_blank">BFS</a>&nbsp;完成。</p>
	</li>
</ol>

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[图](https://github.com/openset/leetcode/tree/master/tag/graph/README.md)]
  [[拓扑排序](https://github.com/openset/leetcode/tree/master/tag/topological-sort/README.md)]

### 相似题目
  1. [课程表 II](/course-schedule-ii) (Medium)
  1. [Graph Valid Tree](/graph-valid-tree) (Medium)
  1. [最小高度树](/minimum-height-trees) (Medium)
  1. [课程表 III](/course-schedule-iii) (Hard)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/course-schedule)