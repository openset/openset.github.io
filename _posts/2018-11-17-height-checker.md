---
layout:     single
title:      "高度检查器"
date:       2018-11-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Counting Sort, Sorting]
permalink:  /problems/height-checker/
---

## 1051. 高度检查器 (Easy)

{% raw %}

<p>学校在拍年度纪念照时，一般要求学生按照 <strong>非递减</strong> 的高度顺序排列。</p>

<p>请你返回能让所有学生以 <strong>非递减</strong> 高度排列的最小必要移动人数。</p>

<p>注意，当一组学生被选中时，他们之间可以以任何可能的方式重新排序，而未被选中的学生应该保持不动。</p>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入：</strong>heights = [1,1,4,2,1,3]
<strong>输出：</strong>3 
<strong>解释：</strong>
当前数组：[1,1,4,2,1,3]
目标数组：[1,1,1,2,3,4]
在下标 2 处（从 0 开始计数）出现 4 vs 1 ，所以我们必须移动这名学生。
在下标 4 处（从 0 开始计数）出现 1 vs 3 ，所以我们必须移动这名学生。
在下标 5 处（从 0 开始计数）出现 3 vs 4 ，所以我们必须移动这名学生。</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>heights = [5,1,2,3,4]
<strong>输出：</strong>5
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>heights = [1,2,3,4,5]
<strong>输出：</strong>0
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= heights.length <= 100</code></li>
	<li><code>1 <= heights[i] <= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[计数排序](https://github.com/openset/leetcode/tree/master/tag/counting-sort/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sorting/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/height-checker)
