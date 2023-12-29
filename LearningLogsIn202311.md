# 2023年11月算法和数据结构学习日志

## 11月1日 周三

1. [2127. 参加会议的最多员工数](https://leetcode.cn/problems/maximum-employees-to-be-invited-to-a-meeting/),力扣每日一题，一道**拓扑排序的应用题**，同时对于应用题要具体问题具体分析，在看完题解，照着别人的代码敲了一遍后大致**理解了解题思路**（虽然自己独立完成这题还是有些困难），对于这道题，目前先了解大概思路就可以了。

## 11月2日 周四

日常力扣每日一题，详情略。。。。。。

## 11月3日 周五

1. [117. 填充每个节点的下一个右侧节点指针 II](https://leetcode.cn/problems/populating-next-right-pointers-in-each-node-ii/)力扣每日一题，用`BFS`层序遍历的方式解决了这道题

## 11月4日 周六

1. [421. 数组中两个数的最大异或值](https://leetcode.cn/problems/maximum-xor-of-two-numbers-in-an-array/),力扣每日一题，思路：`位运算+思维`，大致理解了这道题的思路，但是对于某些代码细节没有理解，对着题解的代码敲了一遍，可以先放下这道题了（**tips:**`Integer.numberOfLeadingZeros(i)`方法:返回无符号整数i的最高非0位前面的0的个数，包括符号位在内；如果i为负数，这个方法将会返回0，符号位为1。**egs:**比如说，10的二进制表示为 0000 0000 0000 0000 0000 0000 0000 1010
     java的整型长度为32位。那么这个方法返回的就是28)

## 11月5日 周日

参加力扣第370场周赛

1. [100116. 找到冠军 II](https://leetcode.cn/problems/find-champion-ii/)周赛t2,一道看似复杂实则简单的题，但是有些Muggle就是往复杂方向想，没错，就是俺
2. [100118. 在树上执行操作以后得到的最大分数](https://leetcode.cn/problems/maximum-score-after-applying-operations-on-a-tree/)周赛t3,思路：`树形DP`，自己没有解决这道题，决定先暂时放下
3. [187. 重复的DNA序列](https://leetcode.cn/problems/repeated-dna-sequences/)力扣每日一题，结合样例弄懂题意后发现思路并不困难，通过`集合`去重就可以解决这道题

## 11月6日 周一

1. [318. 最大单词长度乘积](https://leetcode.cn/problems/maximum-product-of-word-lengths/)力扣每日一题，思路：`位运算`，很巧妙的思路，要多学习大佬的思路！！！

## 11月7日 周二

1. [2925. 在树上执行操作以后得到的最大分数](https://leetcode.cn/problems/maximum-score-after-applying-operations-on-a-tree/)力扣第370场周赛t3,对于自己具有一定启发意义的题，看了题解后解决了这道题，要慢慢的体会`分解子问题`的思维方式
2. [面试题 08.07. 无重复字符串的排列组合](https://leetcode.cn/problems/permutation-i-lcci/)思路：`排列型枚举`，要培养自己的抽象能力，能否从具体问题看出排列枚举的本质呢
3. [面试题 02.02. 返回倒数第 k 个节点](https://leetcode.cn/problems/kth-node-from-end-of-list-lcci/)学会用文字描述自己的思路，学会用文字表达自己，这是一项值得培养的能力
4. [面试题 05.02. 二进制数转字符串](https://leetcode.cn/problems/binary-number-to-string-lcci/)一道数学编程题，对于证明部分没有理解思路，决定先暂时放下这道题

## 11月8日 周三

1. [2915. 和为目标值的最长子序列的长度](https://leetcode.cn/problems/length-of-the-longest-subsequence-that-sums-to-target/)力扣第116场双周赛，自己的思路是：`dfs+记忆化优化`，自己认为这是一条可行的思路，但是却wa了，把代码发到群里求DeBug后决定暂时放下这道题
2. [2609. 最长平衡子字符串](https://leetcode.cn/problems/find-the-longest-balanced-substring-of-a-binary-string/)，力扣每日一题，之前做过的一道题目，刷题的目的是提高自己的分析能力和解决问题的能力，不要刻意回忆自己之前的解法，当做一道新题来思考

## 11月9日 周四

1. 104. 二叉树的最大深度 https://leetcode.cn/problems/maximum-depth-of-binary-tree/ 111. 二叉树的最小深度 https://leetcode.cn/problems/minimum-depth-of-binary-tree/重新写了这两道之前写过的题，温故而知新，自己对于递归的理解加深了
2. [112. 路径总和](https://leetcode.cn/problems/path-sum/)二刷此题，发现自己的思路更加简洁了
3. [113. 路径总和 II - 力扣（LeetCode）](https://leetcode.cn/problems/path-sum-ii/description/)之前暂时放下的一道题，发现理解加深后，原来觉得没有思路无从下手的题，可以很轻松的解决，学习算法重要的是理解原理，学习思想
4. [1448. 统计二叉树中好节点的数目](https://leetcode.cn/problems/count-good-nodes-in-binary-tree/)自我感觉此题的思路非常简单，但是却wa了，找了半天没有发现Bug，可能是眼睛没有吃油，决定先放下！！！下班！！！**后续：**晚上，再次看这道题，没有修改任何代码，AC了，说明**力扣官方编译器也有出错的时候**
5. 100. 相同的树 https://leetcode.cn/problems/same-tree/ 101. 对称二叉树 https://leetcode.cn/problems/symmetric-tree/再次思考这两道去年写过的题，发现自己分析问题的能力有了一定的提升
6. [110. 平衡二叉树](https://leetcode.cn/problems/balanced-binary-tree/)再次写这道题，发现自己又又又写屎山啦！！！但是没有被之前做过这道题的印象所束缚！！！看了题解后，发现题解区的思路与代码更加简洁，要多向世界，多向他人学习！！！

## 11月10日 周五

1. [2300. 咒语和药水的成功对数](https://leetcode.cn/problems/successful-pairs-of-spells-and-potions/)力扣每日一题，思路：`二分`，独立解决了这道题！！！
2. 226. 翻转二叉树 https://leetcode.cn/problems/invert-binary-tree/ 1026. 节点与其祖先之间的最大差值 https://leetcode.cn/problems/maximum-difference-between-node-and-ancestor/对于这两道题，自己采用的都是`遍历二叉树`的思路
3. [1080. 根到叶路径上的不足节点](https://leetcode.cn/problems/insufficient-nodes-in-root-to-leaf-paths/)一道结合了`思维+二叉树遍历`的好题，又被大佬的思路秀翻啦！！！
4. [1110. 删点成林](https://leetcode.cn/problems/delete-nodes-and-return-forest/)思路：`二叉树遍历+模拟`，要学会根据具体问题具体分析呀！！！
4. [98. 验证二叉搜索树](https://leetcode.cn/problems/validate-binary-search-tree/)三刷此题，思路变得简洁了！！！
4. [1373. 二叉搜索子树的最大键值和](https://leetcode.cn/problems/maximum-sum-bst-in-binary-tree/)此道题，自己认为的思路是：`平衡二叉树的性质+二叉树的遍历`,但是自己越改越乱，同时，图书馆快要关门了，决定明天再想！！！下班！！！

## 11月11日 周六

1. [765. 情侣牵手](https://leetcode.cn/problems/couples-holding-hands/)，力扣每日一题，思路：`并查集或贪心`，这并不是目前自己学习的重点，所以大概了解思路后，决定先放下这道题
2. [1373. 二叉搜索子树的最大键值和](https://leetcode.cn/problems/maximum-sum-bst-in-binary-tree/),再次思考昨天遗留的问题，依然没有思路，决定先放下这道题


## 11月12日 周日

参加力扣第371场周赛

### 周赛复盘：

对于周赛t3自己不够自信，一直在纠结是`动态规划`还是`贪心`,在比赛中的很长一段时间，认为正确思路应该是`动态规划`，只是自己不会动态规划罢了，由于纠结自己会不会动态规划，而没有考虑用贪心的思路解决问题，实际上，自己对于动态规划已经具备了一定的理解和运用能力，赛后看题解，发现是 `贪心`

不必纠结于自己会不会`DP`、会不会`二分`、会不会`回溯`、会不会`二分`之类的自我怀疑，目前自己的情况是对于经典的算法已经有了一定的理解和运用能力，还欠缺的是分析问题的能力，同时思维水平还有待提升

面对力扣周赛，应该专注于解决问题，而不是陷入对于自己学习成果的自我怀疑，对于自己的学习成果要有客观认知：了解or掌握or运用or创新，目前自己对于经典算法已经基本掌握，但还需要进一步提高自己的运用能力

### 日常

1. [715. Range 模块](https://leetcode.cn/problems/range-module/)，力扣每日一题，思路：`线段树`,目前并没有线段树的学习计划，决定先放下这道题

## 11月13日 周一

1. [307. 区域和检索 - 数组可修改](https://leetcode.cn/problems/range-sum-query-mutable/),思路：`树状数组`,初看以为是前缀和与差分，但是没有过于纠结于自己会不会前缀和与差分，并没有将自己思路卡壳的原因归咎于自己没有学会前缀和与差分，而是此题不适合用前缀和与差分，看题解后发现是`树状数组`，由于并不在自己最近的学习计划内，所以决定先放下这道题


## 11月14日 周二

1. [1334. 阈值距离内邻居最少的城市](https://leetcode.cn/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/),力扣每日一题，思路：`Floyd 最短路`,由于不在最近的学习计划中,所以决定先放下这道题

## 11月15日 周三

1. 日常力扣每日一题，具体内容略

## 11月16日 周四

1. 日常力扣每日一题，具体内容略

## 11月17日 周五

1. [2736. 最大和查询](https://leetcode.cn/problems/maximum-sum-queries/)题解区思路：`排序+单调栈+二分` 或者`树状数组`,由于不在自己最近的学习计划内~~其实是因为自己菜~~决定先放下这道每日一题~~C/V大法！！！该白嫖的每日打卡积分还是要嫖滴！！！~~

## 11月18日 周六

1. 日常力扣每日一题，具体内容略

## 11月19日 周日

参加力扣第372场周赛

### 周赛复盘

1. t1没有认真读题，浪费了不少时间
2. t2表现较好，没有简单问题复杂化
3. 对于t4，个人认为自己在本次周赛的亮点之一是在t3没有思路的情况下挑战t4,虽然最后还是没有AC t4,但还是拓展了思路，个人认为t4的思路应该是：`某种树的数据结构+二分`

### 日常

1. [689. 三个无重叠子数组的最大和](https://leetcode.cn/problems/maximum-sum-of-3-non-overlapping-subarrays/),力扣每日一题，猜测的思路是：`DP`，题解区的思路是：`前缀和+序列DP`,由于笔记本电脑没电啦！！！~~其实是菜鸡的畏难心理~~决定先放下这道题

## 11月20日 周一

日常力扣每日一题，详情略。

## 11月21日 周二

1. [2216. 美化数组的最少删除数](https://leetcode.cn/problems/minimum-deletions-to-make-array-beautiful/),力扣每日一题，思路：`思维+模拟`，但是有些人因为有熟人在旁边而紧张得一匹！！！太菜啦！！！太菜啦！！！

## 11月22日 周三

1. [2304. 网格中的最小路径代价](https://leetcode.cn/problems/minimum-path-cost-in-a-grid/),力扣每日一题，跟室友吹牛逼说`有手就行`,结果一吹完牛逼就感到紧张和压力山大，导致思路弯弯绕绕,又觉得是DFS，又觉得是BFS,不过最后想到了较好的解法：`动态规划`，菜菜菜！！！

## 11月23日 周四

1. [1410. HTML 实体解析器](https://leetcode.cn/problems/html-entity-parser/),力扣每日一题，思路：`大模拟+遍历`,wa了两发，菜菜菜！！！
2. [1123. 最深叶节点的最近公共祖先](https://leetcode.cn/problems/lowest-common-ancestor-of-deepest-leaves/),在修修改改写屎山，弯弯绕绕改代码！！！啊啊啊！！！目前并没有一个简洁的思路，决定先放下这道题。
3. [103. 二叉树的锯齿形层序遍历](https://leetcode.cn/problems/binary-tree-zigzag-level-order-traversal/),思路：`二叉树的层序遍历`，噜啦啦！！！有手就行！！！


## 11月24日 周五

1. [2824. 统计和小于目标的下标对数目](https://leetcode.cn/problems/count-pairs-whose-sum-is-less-than-target/),力扣每日一题，怎么有的人只会暴力呀！！！思路：`排序+双指针`
2. [17. 电话号码的字母组合](https://leetcode.cn/problems/letter-combinations-of-a-phone-number/) [78. 子集](https://leetcode.cn/problems/subsets/) [131. 分割回文串](https://leetcode.cn/problems/palindrome-partitioning/)重新思考这几道题，发现自己的思路更加简洁了
3. [77. 组合](https://leetcode.cn/problems/combinations/)` `[216. 组合总和 III](https://leetcode.cn/problems/combination-sum-iii/)` `[22. 括号生成](https://leetcode.cn/problems/generate-parentheses/)`重新思考这几道题，思路更简洁了，同时发现可以进行`剪枝优化`
3. [198. 打家劫舍](https://leetcode.cn/problems/house-robber/) [70. 爬楼梯](https://leetcode.cn/problems/climbing-stairs/) [746. 使用最小花费爬楼梯](https://leetcode.cn/problems/min-cost-climbing-stairs/)重新思考这些基础的动态规划问题，状态定义与状态转移并没有那么困难，要能够找到问题的本质
3. [2466. 统计构造好字符串的方案数](https://leetcode.cn/problems/count-ways-to-build-good-strings/) 自己对于这道题有一定思路，但是代码wa了，发现是自己对于问题没有考虑完整，决定先暂时放下这道题

 ## 11月25日 周六

1. [1457. 二叉树中的伪回文路径](https://leetcode.cn/problems/pseudo-palindromic-paths-in-a-binary-tree/),力扣每日一题，自己的解法是：`二叉树的遍历`，题解的优雅思路是：`递归+位运算`，又又又被秀翻啦！！！又感受到了**位运算震撼**和**递归震撼**！！！
2. [2466. 统计构造好字符串的方案数](https://leetcode.cn/problems/count-ways-to-build-good-strings/),虽然最后通过修修改改解决了这道题，但是又又又写**屎山**啦！！！
3. [213. 打家劫舍 II](https://leetcode.cn/problems/house-robber-ii/),重新思考这道题，发现自己的思路变得简洁了
4. [494. 目标和](https://leetcode.cn/problems/target-sum/),在胡思乱想，无法集中注意力，决定先放下这道题~~其实就是菜~~
4. [494. 目标和](https://leetcode.cn/problems/target-sum/),干完饭后，整理思路，解决了这道题，是关于`选与不选的背包问题`,自己对于动态规划的理解加深了
4. [322. 零钱兑换](https://leetcode.cn/problems/coin-change/),重新思考这道题，发现自己的思路变得简洁了
4. [2915. 和为目标值的最长子序列的长度](https://leetcode.cn/problems/length-of-the-longest-subsequence-that-sums-to-target/),耐心，仔细分析问题后解决了这道题，思路：`动态规划-01背包`
4. [1143. 最长公共子序列](https://leetcode.cn/problems/longest-common-subsequence/),重新思考这道题，这道题的难点是：`状态定义`，想到状态定义之后，就可以一马平川了
4. [72. 编辑距离](https://leetcode.cn/problems/edit-distance/)，重新思考这道题，这道题的难点是`状态定义和状态转移`，其中状态转移需要用到`等价转换`
4. [122. 买卖股票的最佳时机 II](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/)，重新思考这道题，这道题的难点是`状态定义`，理解`状态机`的思想
4. [516. 最长回文子序列](https://leetcode.cn/problems/longest-palindromic-subsequence/),重新思考这道题,此题的难点是`状态定义`，借鉴`区间DP的状态定义思想`

## 11月26日 周日

1. [828. 统计子串中的唯一字符](https://leetcode.cn/problems/count-unique-characters-of-all-substrings-of-a-given-string/),力扣每日一题，由于某人被力扣周赛打破防啦！！！于是选择了Control C/V！！！

### 第118场力扣双周赛复盘

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

不复盘啦！！！

### 第373场力扣周赛复盘

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

靠靠靠！！！靠靠靠！！！

不复盘啦！！！

## 11月27日-11月29日

1. 日常力扣每日一题，详情略
2. 两个子序列的最大点积 https://leetcode.cn/problems/max-dot-product-of-two-subsequences/此题暂时没有解题思路，**因为菜**，但是值得花时间解决
3. [673. 最长递增子序列的个数](https://leetcode.cn/problems/number-of-longest-increasing-subsequence/)此题暂时没有解题思路，**因为菜**，但是值得花时间解决

### 为什么这三天没有详细记录呢？

1. 心态崩了，破大防
2. 临近期末，疲于奔命
2. 各种杂七杂八的琐碎事务

## 11月30日 周四

1. [1657. 确定两个字符串是否接近](https://leetcode.cn/problems/determine-if-two-strings-are-close/),力扣每日一题，Control C/V解决了这道题，~~关于菜鸡想白嫖10积分那些事~~
2. [673. 最长递增子序列的个数](https://leetcode.cn/problems/number-of-longest-increasing-subsequence/)看了这道题之前交的代码，发现还得是**思维**
3. 两个子序列的最大点积 https://leetcode.cn/problems/max-dot-product-of-two-subsequences/参考题解解决了这道题
4. [1911. 最大子序列交替和](https://leetcode.cn/problems/maximum-alternating-subsequence-sum/)此题暂时没有思路，**因为菜**，但这也是一道非常简洁，非常值得花时间思考的题。
4. [2305. 公平分发饼干](https://leetcode.cn/problems/fair-distribution-of-cookies/),解决了这道之前暂时放下的题，虽然是用暴力解法

