---
layout:     single
title:      "另一个树的子树"
date:       2017-07-26 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Binary Tree, String Matching, Hash Function]
permalink:  /problems/subtree-of-another-tree/
---

## 572. 另一个树的子树 (Easy)

{% raw %}

<p>给定两个非空二叉树 <strong>s</strong> 和 <strong>t</strong>，检验&nbsp;<strong>s</strong> 中是否包含和 <strong>t</strong> 具有相同结构和节点值的子树。<strong>s</strong> 的一个子树包括 <strong>s</strong> 的一个节点和这个节点的所有子孙。<strong>s</strong> 也可以看做它自身的一棵子树。</p>

<p><strong>示例 1:</strong><br />
给定的树 s:</p>

<pre>
     3
    / \
   4   5
  / \
 1   2
</pre>

<p>给定的树 t：</p>

<pre>
   4 
  / \
 1   2
</pre>

<p>返回 <strong>true</strong>，因为 t 与 s 的一个子树拥有相同的结构和节点值。</p>

<p><strong>示例 2:</strong><br />
给定的树 s：</p>

<pre>
     3
    / \
   4   5
  / \
 1   2
    /
   0
</pre>

<p>给定的树 t：</p>

<pre>
   4
  / \
 1   2
</pre>

<p>返回 <strong>false</strong>。</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[二叉树](https://github.com/openset/leetcode/tree/master/tag/binary-tree/README.md)]
  [[字符串匹配](https://github.com/openset/leetcode/tree/master/tag/string-matching/README.md)]
  [[哈希函数](https://github.com/openset/leetcode/tree/master/tag/hash-function/README.md)]

### 相似题目
  1. [统计同值子树](/problems/count-univalue-subtrees) (Medium)
  1. [出现次数最多的子树元素和](/problems/most-frequent-subtree-sum) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/subtree-of-another-tree)
