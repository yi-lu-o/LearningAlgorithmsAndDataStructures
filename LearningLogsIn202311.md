# 2023年11月算法和数据结构学习日志

## 11月1日 周三

1. `[2127. 参加会议的最多员工数](https://leetcode.cn/problems/maximum-employees-to-be-invited-to-a-meeting/)`,力扣每日一题，一道**拓扑排序的应用题**，同时对于应用题要具体问题具体分析，在看完题解，照着别人的代码敲了一遍后大致**理解了解题思路**（虽然自己独立完成这题还是有些困难），对于这道题，目前先了解大概思路就可以了。

## 11月2日 周四

日常力扣每日一题，详情略。。。。。。

## 11月3日 周五

1. `[117. 填充每个节点的下一个右侧节点指针 II](https://leetcode.cn/problems/populating-next-right-pointers-in-each-node-ii/)`力扣每日一题，用`BFS`层序遍历的方式解决了这道题

## 11月4日 周六

1. `[421. 数组中两个数的最大异或值](https://leetcode.cn/problems/maximum-xor-of-two-numbers-in-an-array/)`,力扣每日一题，思路：`位运算+思维`，大致理解了这道题的思路，但是对于某些代码细节没有理解，对着题解的代码敲了一遍，可以先放下这道题了（**tips:**`Integer.numberOfLeadingZeros(i)`方法:返回无符号整数i的最高非0位前面的0的个数，包括符号位在内；如果i为负数，这个方法将会返回0，符号位为1。**egs:**比如说，10的二进制表示为 0000 0000 0000 0000 0000 0000 0000 1010
     java的整型长度为32位。那么这个方法返回的就是28)

## 11月5日 周日

参加力扣第370场周赛

1. `[100116. 找到冠军 II](https://leetcode.cn/problems/find-champion-ii/)`周赛t2,一道看似复杂实则简单的题，但是有些Muggle就是往复杂方向想，没错，就是俺
2. `[100118. 在树上执行操作以后得到的最大分数](https://leetcode.cn/problems/maximum-score-after-applying-operations-on-a-tree/)`周赛t3,思路：`树形DP`，自己没有解决这道题，决定先暂时放下
3. `[187. 重复的DNA序列](https://leetcode.cn/problems/repeated-dna-sequences/)`力扣每日一题，结合样例弄懂题意后发现思路并不困难，通过`集合`去重就可以解决这道题

## 11月6日 周一

1. `[318. 最大单词长度乘积](https://leetcode.cn/problems/maximum-product-of-word-lengths/)`力扣每日一题，思路：`位运算`，很巧妙的思路，要多学习大佬的思路！！！

## 11月7日 周二

1. `[2925. 在树上执行操作以后得到的最大分数](https://leetcode.cn/problems/maximum-score-after-applying-operations-on-a-tree/)`力扣第370场周赛t3,对于自己具有一定启发意义的题，看了题解后解决了这道题，要慢慢的体会`分解子问题`的思维方式
2. `[面试题 08.07. 无重复字符串的排列组合](https://leetcode.cn/problems/permutation-i-lcci/)`思路：`排列型枚举`，要培养自己的抽象能力，能否从具体问题看出排列枚举的本质呢
3. `[面试题 02.02. 返回倒数第 k 个节点](https://leetcode.cn/problems/kth-node-from-end-of-list-lcci/)`学会用文字描述自己的思路，学会用文字表达自己，这是一项值得培养的能力
4. `[面试题 05.02. 二进制数转字符串](https://leetcode.cn/problems/binary-number-to-string-lcci/)`一道数学编程题，对于证明部分没有理解思路，决定先暂时放下这道题

## 11月8日 周三

1. `[2915. 和为目标值的最长子序列的长度](https://leetcode.cn/problems/length-of-the-longest-subsequence-that-sums-to-target/)`力扣第116场双周赛，自己的思路是：`dfs+记忆化优化`，自己认为这是一条可行的思路，但是却wa了，把代码发到群里求DeBug后决定暂时放下这道题
2. `[2609. 最长平衡子字符串](https://leetcode.cn/problems/find-the-longest-balanced-substring-of-a-binary-string/)`，力扣每日一题，之前做过的一道题目，刷题的目的是提高自己的分析能力和解决问题的能力，不要刻意回忆自己之前的解法，当做一道新题来思考

## 11月9日 周四

1. `104. 二叉树的最大深度 https://leetcode.cn/problems/maximum-depth-of-binary-tree/` `111. 二叉树的最小深度 https://leetcode.cn/problems/minimum-depth-of-binary-tree/`重新写了这两道之前写过的题，温故而知新，自己对于递归的理解加深了
2. `[112. 路径总和](https://leetcode.cn/problems/path-sum/)`二刷此题，发现自己的思路更加简洁了
3. `[113. 路径总和 II - 力扣（LeetCode）](https://leetcode.cn/problems/path-sum-ii/description/)`之前暂时放下的一道题，发现理解加深后，原来觉得没有思路无从下手的题，可以很轻松的解决，学习算法重要的是理解原理，学习思想
4. `[1448. 统计二叉树中好节点的数目](https://leetcode.cn/problems/count-good-nodes-in-binary-tree/)`自我感觉此题的思路非常简单，但是却wa了，找了半天没有发现Bug，可能是眼睛没有吃油，决定先放下！！！下班！！！**后续：**晚上，再次看这道题，没有修改任何代码，AC了，说明**力扣官方编译器也有出错的时候**
5. `100. 相同的树 https://leetcode.cn/problems/same-tree/` `101. 对称二叉树 https://leetcode.cn/problems/symmetric-tree/`再次思考这两道去年写过的题，发现自己分析问题的能力有了一定的提升
6. `[110. 平衡二叉树](https://leetcode.cn/problems/balanced-binary-tree/)`再次写这道题，发现自己又又又写屎山啦！！！但是没有被之前做过这道题的印象所束缚！！！看了题解后，发现题解区的思路与代码更加简洁，要多向世界，多向他人学习！！！