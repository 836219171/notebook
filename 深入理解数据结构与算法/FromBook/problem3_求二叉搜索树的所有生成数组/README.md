
# 求二叉搜索树的所有生成数组

### 题意
```
从左向右遍历一个数组，通过不断将其中的元素插入树中可以逐步地生成一棵二叉搜索树。给定一个由不同节点组成的二叉搜索树，输出所有可能生成此树的数组
```

### 条件范围
```
未知，但N估计很小，N为节点总数
```

### 样例输入
```
[]
[1]
[2,1,3]
[3,1,2,4,5]
```

### 样例输出
```
[[]]
[[1]]
[[2,1,3],[2,3,1]]
[[3,1,2,4,5],[3,1,2,5,4],[3,1,4,5,2],[3,1,4,2,5],[3,1,5,2,4],[3,1,5,4,2],[3,2,1,4,5],[3,2,1,5,4]]
```

### 关联链接

原题：https://leetcode-cn.com/problems/bst-sequences-lcci/

来自《程序员面试金典（第6版）》

