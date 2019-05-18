---
layout:     single
title:      "从二叉搜索树到更大和树"
date:       2018-11-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Binary Search Tree]
permalink:  /binary-search-tree-to-greater-sum-tree/
---

## 1038. 从二叉搜索树到更大和树 (Medium)

<p>给出二叉<strong>搜索</strong>树的根节点，该二叉树的节点值各不相同，修改二叉树，使每个节点 <code>node</code>&nbsp;的新值等于原树中大于或等于&nbsp;<code>node.val</code>&nbsp;的值之和。</p>

<p>提醒一下，二叉搜索树满足下列约束条件：</p>

<ul>
	<li>节点的左子树仅包含键<strong>小于</strong>节点键的节点。</li>
	<li>节点的右子树仅包含键<strong>大于</strong>节点键的节点。</li>
	<li>左右子树也必须是二叉搜索树。</li>
</ul>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/05/03/tree.png" style="height: 191px; width: 280px;"></strong></p>

<pre><strong>输入：</strong>[4,1,6,0,2,5,7,null,null,null,3,null,null,null,8]
<strong>输出：</strong>[30,36,21,36,35,26,15,null,null,null,33,null,null,null,8]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li>树中的节点数介于 <code>1</code> 和 <code>100</code> 之间。</li>
	<li>每个节点的值介于&nbsp;<code>0</code> 和&nbsp;<code>100</code>&nbsp;之间。</li>
	<li>给定的树为二叉搜索树。</li>
</ol>

<p>&nbsp;</p>

### 相关话题
  [[二叉搜索树](https://github.com/openset/leetcode/tree/master/tag/binary-search-tree/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/binary-search-tree-to-greater-sum-tree)