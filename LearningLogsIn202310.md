# 2023年10月算法和数据结构学习日志

## 10月1日 周日

### 周赛

参加力扣第365场周赛，被打爆啦！！！菜菜菜！！！

## 10月3日 周二

### 下午，学习思考记录

14：40开始思考第365场周赛的编程题

1. `[2875. 无限数组的最短子数组](https://leetcode.cn/problems/minimum-size-subarray-in-infinite-array/)`,第365场周赛的t3，很具有思维灵性的一道题，尽管看了题解和视频但还是没弄懂，决定先暂时放下

## 10月5日 周四

### 早上，思考记录

1. `[2730. 找到最长的半重复子字符串](https://leetcode.cn/problems/find-the-longest-semi-repetitive-substring/)`，**双指针**，解决了这道题
2. `[2698. 求一个整数的惩罚数](https://leetcode.cn/problems/find-the-punishment-number-of-an-integer/)`**回溯型枚举**，解决了这道题
3. `[207. 课程表](https://leetcode.cn/problems/course-schedule/)`,认为自己的逻辑没有错误，代码没有错误，反复检查还是没有发现错误，但是运行结果却是错的，于是认定是力扣平台的编译器错误（当然，非常有可能过几天发现错的还是自己）

## 下班

11：30下班！！！干饭！！！

## 中午，下午，学习思考记录

12：30开始学习与思考

1. 读labuladong算法学习网站的文章`环检测及拓扑排序算法`,这篇文章**未读懂**，未能get到作者的思路
2. 读csdn博客`拓扑排序(http://t.csdnimg.cn/RrZk5)`,通过这篇博客理解了**什么是拓扑排序**
3. 读csdn博客`拓扑排序（Topological Sorting）(http://t.csdnimg.cn/Cu31q)`
4. 拓扑排序（Topological Sorting）是一个**有向无环图**（DAG, Directed Acyclic Graph）的所有**顶点的线性序列**。且该序列必须满足下面两个条件：

- 每个顶点出现且只出现一次。
- 若存在一条从顶点 A 到顶点 B 的路径，那么在序列中顶点 A 出现在顶点 B 的前面。
- 有向无环图（DAG）才有拓扑排序，非DAG图没有拓扑排序一说。

## 下班

13：30下班！！！回寝室学习围棋！！！

## 10月6日 周五

### 早上学习记录

1. `[207. 课程表](https://leetcode.cn/problems/course-schedule/)`、`[210. 课程表 II](https://leetcode.cn/problems/course-schedule-ii/)`知道了如何**用BFS实现拓扑排序**，但是不知道Bug出现在哪里，就是有用例过不了，也许是眼睛没吃油，也许是大脑宕机了，总之先放下吧，当**眼睛没吃油or大脑宕机**的时候，重点领悟算法的总体思想！！！在干饭前，把代码发到了刷题群里，群友帮助找到了Bug！！！`Arrays.fill(map,new HashSet<Integer>());`会装入同一个Set对象！！！
2. `[851. 喧闹和富有](https://leetcode.cn/problems/loud-and-rich/)`,如何将具体问题抽象为**拓扑排序**，思考**节点**和**有向边的方向**，又又又**不知道Bug在哪**，菜菜菜！！！

### 中午，下午，学习记录

1. 根据群友的提醒，找到了自己遇到的Bug，解决了早上遗留的问题
2. `[913. 猫和老鼠](https://leetcode.cn/problems/cat-and-mouse/)`,近20min没思路，决定看题解，看题解是DP，这不是今天的学习主线，于是决定先跳过~~菜菜菜~~
3. `[LCR 114. 火星词典](https://leetcode.cn/problems/Jf1JuT/)`题目意思未弄懂，先跳过
4. 决定读知识星球的文章

### 下班

15：00下班

## 10月7日-10月20日

由于一时手贱用shift+delete永久删除了这段时间的日志记录。所以。。。。。。~~绝对不是俺想销毁我是蒟蒻的证据~~

## 10月21日

15：00左右开始思考编程题

1. `[2316. 统计无向图中无法互相到达点对数](https://leetcode.cn/problems/count-unreachable-pairs-of-nodes-in-an-undirected-graph/)`，思路并不复杂，只是有些蒟蒻一看到图的题就慌得一匹，俺不说是谁，谁心里清楚，菜菜菜！！！
2. `[2606. 找到最大开销的子字符串](https://leetcode.cn/problems/find-the-substring-with-maximum-cost/)`一道基础动态规划题，独立解决了这道题，欸嘿，欸嘿！！！
3. `[2707. 字符串中的额外字符](https://leetcode.cn/problems/extra-characters-in-a-string/)`，一道基础动态规划题，但是自己不知道如何简洁的状态定义。看题解后完成了这道题！！！

## 10月22日 周日

参加**力扣第368场周赛**，记录下t3(`[100097. 合法分组的最少组数](https://leetcode.cn/problems/minimum-number-of-groups-to-create-a-valid-assignment/)`)**弯弯绕绕**的过程：

1. 初看觉得是贪心，但是不知道如何贪心
2. 再看觉得可以二分，但是最后发现应该不可以二分，在这条思路上花费了大量的时间
3. 最后尝试转二分为暴力，发现自己的二分思路有很多逻辑上的BUG
4. 菜菜菜！！！菜菜菜！！！

## 10月23日 周一

1. `[2910. 合法分组的最少组数](https://leetcode.cn/problems/minimum-number-of-groups-to-create-a-valid-assignment/)`力扣第368场周赛t3,思路：`贪心`，唉，唉，唉，😔，😔，😔，生活不易，菜鸡叹气！！！
2. `[2911. 得到 K 个半回文串的最少修改次数](https://leetcode.cn/problems/minimum-changes-to-make-k-semi-palindromes/)`力扣第368场周赛t4,思路：`DP`，未能理解此题的状态转移和状态定义，决定先放下这道题！！！菜菜菜！！！

## 10月24日 周二

1. `[1155. 掷骰子等于目标和的方法数](https://leetcode.cn/problems/number-of-dice-rolls-with-target-sum/)`,力扣每日一题，记录下此题弯弯绕绕的过程：先尝试**暴力DFS超时**了，再尝试**记忆化搜索还是超时**，决定看题解，看了题解之后发现自己写的记忆化搜索只需要修改一行代码就可以了，通过阅读题解对于递归的理解加深了
2. `[1155. 掷骰子等于目标和的方法数](https://leetcode.cn/problems/number-of-dice-rolls-with-target-sum/)`,读完题解之后，按照题解的思路重构了代码，体会到了**递归到记忆化搜索到递推(DP)**的过程

## 10月25日 周三

1. `[2698. 求一个整数的惩罚数](https://leetcode.cn/problems/find-the-punishment-number-of-an-integer/)`力扣每日一题 思路：对于每一个以s[i]开头的子字符串，枚举这个子字符串的结束位置j(1<=j<=n),计算substring(i,j)的值即可(要学会清晰的表达自己的枚举方案)

## 10月26日 周四

日常思考力扣每日一题

## 10月27日 周五

1. `[2585. 获得分数的方法数](https://leetcode.cn/problems/number-of-ways-to-earn-points/)`,通过：`暴搜+记忆化优化`AC了这道题，记忆化的精是**避免大量重复计算**，剪枝的精髓是**提前去掉不可行方案**
2. `[1465. 切割后面积最大的蛋糕](https://leetcode.cn/problems/maximum-area-of-a-piece-of-cake-after-horizontal-and-vertical-cuts/)`思路：`数学+贪心`,解决了这道题
3. `[2547. 拆分数组的最小代价](https://leetcode.cn/problems/minimum-cost-to-split-an-array/)`尝试用`暴搜+记忆化`依然超时，还有可以优化的部分，决定先暂时放下这道题

## 10月29日 周日

1. `[274. H 指数](https://leetcode.cn/problems/h-index/)`力扣每日一题，自己的思路：`排序+双指针`，题解的思路：`排序+二分`，经过对比，发现自己的双指针思路也是可行的。

### 参加第369场力扣周赛

发现自己t2想得太复杂了,但最后能够理出正确的清晰的思路还是OK的，慢慢的养成了打力扣周赛的习惯

## 10月30日 周一

1. `[275. H 指数 II](https://leetcode.cn/problems/h-index-ii/)`力扣每日一题，思路：`二分`，学会用文字的形式使自己的思路更加清晰

