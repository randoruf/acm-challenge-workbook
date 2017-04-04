# 1 前言

项目为[《挑战程序设计竞赛（第2版）》](http://www.ituring.com.cn/book/1044)习题册，配合书籍或笔记，系统学习算法。

* 题量：约200道，代码注释内含详解。
* 难度：总体高于Leetcode，部分接近ACM地区赛。
* 题解：代码均AC，题解个人向；Bug或优化请建Issue或Pull Request。
* 计划：持续更新，预计2017年4月完成。

# 1.1 题库来源
- Google Code Jam（[GCJ](https://code.google.com/codejam)）
- Peking University Online Judge（[POJ](http://poj.org/)）
- Aizu Online Judge（[AOJ](http://judge.u-aizu.ac.jp/onlinejudge/index.jsp?lang=en)）
- UVa Online Judge（[UVa](https://uva.onlinejudge.org/)）
- CodeForces（[CF](http://codeforces.com/)）

# 1.2 算法笔记
- [初级篇](http://jennica.space/2016/10/14/acm-challenge-easy/)
- [中级篇](http://jennica.space/2016/11/16/acm-challenge-medium/)
- [高级篇](http://jennica.space/2016/11/30/acm-challenge-hard/)

# 1.3 题库目录

* 初级： 
[穷竭搜索 √](#21-穷竭搜索)、
[贪心法 √](#22-贪心法)、
[动态规划 √](#23-动态规划)、
[数据结构 √](#24-数据结构)、
[图论 √](#25-图论)、
[数论 √](#26-数论)

* 中级：
[二分搜索 √](#31-二分搜索)、
[常用技巧 √](#32-常用技巧)、
[数据结构（二） √](#33-数据结构二)、
[动态规划（二） √](#34-动态规划二)、
[网络流](#35-网络流)、
[计算几何](#36-计算几何)

* 高级：
[数论（二）](#41-数论二)、
[博弈论](#42-博弈论)、
[图论（二）](#43-图论二)、
[常用技巧（二）](#44-常用技巧二)、
[智慧搜索](#45-智慧搜索)、
[分治](#46-分治)、
[字符串](#47-字符串)


# 2 初级算法

# 2.1 穷竭搜索
- 深度优先搜索
  - [x] [POJ 1979: Red and Black](http://poj.org/problem?id=1979)
  - [x] [AOJ 0118: Property Distribution](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=0118)
  - [x] [AOJ 0033: Ball](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=0033)
  - [x] [POJ 3009: Curling 2.0](http://poj.org/problem?id=3009)

- 宽度优先搜索
  - [x] [AOJ 0558: Cheese](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=0558)
  - [x] [POJ 3669: Meteor Shower](http://poj.org/problem?id=3669)
  - [x] [AOJ 0121: Seven Puzzle](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=0121)

- 穷竭搜索
  - [x] [POJ 2718: Smallest Difference](http://poj.org/problem?id=2718)
  - [x] [POJ 3187: Backward Digit Sums](http://poj.org/problem?id=3187)
  - [x] [POJ 3050: Hopscotch](http://poj.org/problem?id=3050)
  - [x] [AOJ 0525: Osenbei](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=0525)

# 2.2 贪心法
- 区间贪心
  - [x] [POJ 2376: Cleaning Shifts](http://poj.org/problem?id=2376)
  - [x] [POJ 1328: Radar Installation](http://poj.org/problem?id=1328)
  - [x] [POJ 3190: Stall Reservations](http://poj.org/problem?id=3190)
  
- 其他贪心
  - [x] [POJ 2393: Yogurt factory](http://poj.org/problem?id=2393)
  - [x] [POJ 1017: Packets](http://poj.org/problem?id=1017)
  - [x] [POJ 3040; Allowance](http://poj.org/problem?id=3040)
  - [x] [POJ 1862: Stripies](http://poj.org/problem?id=1862)
  - [x] [POJ 3262: Protecting the Flowers](http://poj.org/problem?id=3262)
  
# 2.3 动态规划
- 基础DP
  - [x] [POJ 3176: Cow Bowling](http://poj.org/problem?id=3176)
  - [x] [POJ 2229: Sumsets](http://poj.org/problem?id=2229)
  - [x] [POJ 2385: Apple Catching](http://poj.org/problem?id=2385)
  - [x] [POJ 3616: Milking Time](http://poj.org/problem?id=3616)
  - [x] [POJ 3280: Cheapest Palindrome](http://poj.org/problem?id=3280)

- 优化递推式
  - [x] [POJ 1742: Coins](http://poj.org/problem?id=1742)
  - [x] [POJ 3046: Ant Counting](http://poj.org/problem?id=3046)
  - [x] [POJ 3181: Dollar Dayz](http://poj.org/problem?id=3181)
  
- 进阶DP
  - [x] [POJ 1065: Wooden Sticks](http://poj.org/problem?id=1065)
  - [x] [POJ 1631: Bridging signals](http://poj.org/problem?id=1631)
  - [x] [POJ 3666: Making the Grade](http://poj.org/problem?id=3666)
  - [x] [POJ 2392: Space Elevator](http://poj.org/problem?id=2392)
  - [x] [POJ 2184: Cow Exhibition](http://poj.org/problem?id=2184)
  
# 2.4 数据结构
- 优先队列
  - [x] [POJ 3614: Sunscreen](http://poj.org/problem?id=3614)
  - [x] [POJ 2010: Moo University - Financial Aid](http://poj.org/problem?id=2010)
  
- 并查集
  - [x] [POJ 2236: Wireless Network](http://poj.org/problem?id=2236)
  - [x] [POJ 1703: Find them, Catch them](http://poj.org/problem?id=1703)
  - [x] [AOJ 2170: Marked Ancestor](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2170)

# 2.5 图论
- 最短路
  - [x] [AOJ 0189: Convenient Location](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=0189)
  - [x] [POJ 2139: Six Degrees of Cowvin Bacon](http://poj.org/problem?id=2139)
  - [x] [POJ 3259: Wormholes](http://poj.org/problem?id=3259)
  - [x] [POJ 3268: Silver Cow Party](http://poj.org/problem?id=3268)
  - [x] [AOJ 2249: Road Construction](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2249)
  - [x] [AOJ 2200: Mr. Rito Post Office](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2200)
  
- 最小生成树
  - [x] [POJ 1258: Agri-Net](http://poj.org/problem?id=1258)
  - [x] [POJ 2377: Bad Cowtractors](http://poj.org/problem?id=2377)
  - [x] [AOJ 2224: Save Your Cats](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2224)
  - [x] [POJ 2395: Out of Hay](http://poj.org/problem?id=2395)
  
# 2.6 数论
- 辗转相除法
  - [x] [AOJ 0005: GCD and LCM](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=0005)
  - [x] [POJ 2429: GCD & LCM Inverse](http://poj.org/problem?id=2429)
  - [x] [POJ 1930: Dead Fraction](http://poj.org/problem?id=1930)
  
- 素数
  - [x] [AOJ 0009: Prime Number](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=0009)
  - [x] [POJ 3126: Prime Path](http://poj.org/problem?id=3126)
  - [x] [POJ 3421: X-factor Chains](http://poj.org/problem?id=3421)
  - [x] [POJ 3292: Semi-prime H-numbers](http://poj.org/problem?id=3292)
  
- 快速幂
  - [x] [POJ 3641: Pseudoprime numbers](http://poj.org/problem?id=3641)
  - [x] [POJ 1995: Raising Modulo Numbers](http://poj.org/problem?id=1995)
  

# 3 中级算法

# 3.1 二分搜索
- 最大化最小值
  - [x] [POJ 3258: River Hopscotch](http://poj.org/problem?id=3258)
  - [x] [POJ 3273: Monthly Expense](http://poj.org/problem?id=3273)
  - [x] [POJ 3104: Drying](http://poj.org/problem?id=3104)
  - [x] [POJ 3045: Cow Acrobats](http://poj.org/problem?id=3045)

- 01分数规划
  - [x] [POJ 2976: Dropping tests](http://poj.org/problem?id=2976)
  - [x] [POJ 3111: K Best](http://poj.org/problem?id=3111)
  
- 第k大值
  - [x] [POJ 3579: Median](http://poj.org/problem?id=3579)
  - [x] [POJ 3685: Matrix](http://poj.org/problem?id=3685)
  
- 最小化第k大值
  - [x] [POJ 2010: Moo University - Financial Aid](http://poj.org/problem?id=2010)
  - [x] [POJ 3662: Telephone Lines](http://poj.org/problem?id=3662)
  
- 其他二分搜索
  - [x] [POJ 1759: Garland](http://poj.org/problem?id=1759)
  - [x] [POJ 3484: Showstopper](http://poj.org/problem?id=3484)
  
# 3.2 常用技巧
- 尺取法
  - [x] [POJ 2566: Bound Found](http://poj.org/problem?id=2566)
  - [x] [POJ 2739: Sum of Consecutive Prime Numbers](http://poj.org/problem?id=2739)
  - [x] [POJ 2100: Graveyard Design](http://poj.org/problem?id=2100)

- 反转
  - [x] [POJ 3185: The Water Bowls](http://poj.org/problem?id=3185)
  - [x] [POJ 1222: EXTENDED LIGHTS OUT](http://poj.org/problem?id=1222)
  
- 弹性碰撞
  - [x] [POJ 2674: Linear world](http://poj.org/problem?id=2674)
  
- 折半枚举
  - [x] [POJ 3977: Subset](http://poj.org/problem?id=3977)
  - [x] [POJ 2549: Sumsets](http://poj.org/problem?id=2549)
  
- 离散化
  - [x] [AOJ 0531: Paint Color](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=0531)
  
# 3.3 数据结构（二）
- 树状数组
  - [x] [POJ 1990: MooFest](http://poj.org/problem?id=1990)
  - [x] [POJ 3109: Inner Vertices](http://poj.org/problem?id=3109)
  - [x] [POJ 2155: Matrix](http://poj.org/problem?id=2155)
  - [x] [POJ 2886: Who Gets the Most Candies?](http://poj.org/problem?id=2886)

- 线段树和平方分割
  - [x] [POJ 3264: Balanced Lineup](http://poj.org/problem?id=3264)
  - [x] [POJ 3368: Frequent values](http://poj.org/problem?id=3368)
  - [x] [POJ 3470: Walls](http://poj.org/problem?id=3470)
  - [x] [POJ 1201: Intervals](http://poj.org/problem?id=1201)
  - [x] [UVa 11990: "Dynamic" Inversion](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3141)
  
# 3.4 动态规划（二）
- 状态压缩DP
  - [x] [POJ 2441: Arrange the Bulls](http://poj.org/problem?id=2441)
  - [x] [POJ 3254: Corn Fields](http://poj.org/problem?id=3254)
  - [x] [POJ 2836: Rectangular Covering](http://poj.org/problem?id=2836)
  - [x] [POJ 1795: DNA Laboratory](http://poj.org/problem?id=1795)
  - [x] [POJ 3411: Paid Roads](http://poj.org/problem?id=3411)

- 矩阵的幂
  - [x] [POJ 3420: Quad Tiling](http://poj.org/problem?id=3420)
  - [x] [POJ 3735: Training little cats](http://poj.org/problem?id=3735)

- 数据结构与DP
  - [x] [POJ 3171: Cleaning Shifts](http://poj.org/problem?id=3171)
  
# 3.5 网络流
- 最大流与最小割
  - [ ] [POJ 3713: ](http://poj.org/problem?id=)
  - [ ] [POJ 2987: ](http://poj.org/problem?id=)
  - [ ] [POJ 2914: ](http://poj.org/problem?id=)
  - [ ] [POJ 3155: ](http://poj.org/problem?id=)
  
- 二分图匹配
  - [ ] [POJ 1274: ](http://poj.org/problem?id=)
  - [ ] [POJ 2112: ](http://poj.org/problem?id=)
  - [ ] [POJ 1486: ](http://poj.org/problem?id=)
  - [ ] [POJ 1466: ](http://poj.org/problem?id=)
  - [ ] [POJ 3692: ](http://poj.org/problem?id=)
  - [ ] [POJ 2724: ](http://poj.org/problem?id=)
  - [ ] [POJ 2226: ](http://poj.org/problem?id=)
  - [ ] [AOJ 2251: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2251)
  
- 最小费用流
  - [ ] [POJ 3068: ](http://poj.org/problem?id=)
  - [ ] [POJ 2195: ](http://poj.org/problem?id=)
  - [ ] [POJ 3422: ](http://poj.org/problem?id=)
  - [ ] [AOJ 2266: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2266)
  - [ ] [AOJ 2230: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2230)
  
# 3.6 计算几何
- 极限
  - [ ] [POJ 1981: ](http://poj.org/problem?id=)
  - [ ] [POJ 1418: ](http://poj.org/problem?id=)
  - [ ] [AOJ 2201: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2201)
  
- 平面扫描
  - [ ] [POJ 3168: ](http://poj.org/problem?id=)
  - [ ] [POJ 3293: ](http://poj.org/problem?id=)
  - [ ] [POJ 2482: ](http://poj.org/problem?id=)
  
# 4.1 数论（二）
- 模运算
  - [ ] [POJ 1150: ](http://poj.org/problem?id=1150)
  - [ ] [POJ 1284: ](http://poj.org/problem?id=1284)
  - [ ] [POJ 2115: ](http://poj.org/problem?id=2115)
  - [ ] [POJ 3708: ](http://poj.org/problem?id=3708)
  - [ ] [POJ 2720: ](http://poj.org/problem?id=2720)
  - [ ] [GCJ 2011 Final B: ](https://code.google.com/codejam/contest/dashboard?c=1363489#s=p1)

- 矩阵
  - [ ] [POJ 2345: ](http://poj.org/problem?id=2345)
  - [ ] [POJ 3532: ](http://poj.org/problem?id=3532)
  - [ ] [POJ 3526: ](http://poj.org/problem?id=3526)
  
- 计数
  - [ ] [POJ 2407: ](http://poj.org/problem?id=2407)
  - [ ] [POJ 1286: ](http://poj.org/problem?id=1286)
  - [ ] [POJ 2409: ](http://poj.org/problem?id=2409)
  - [ ] [AOJ 2164: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2164)
  - [ ] [AOJ 2214: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2214)
  
# 4.2 博弈论
- 博弈DP
  - [ ] [POJ 1082: ](http://poj.org/problem?id=)
  - [ ] [POJ 2068: ](http://poj.org/problem?id=)
  - [ ] [POJ 3688: ](http://poj.org/problem?id=)
  - [ ] [POJ 1740: ](http://poj.org/problem?id=)

- Nim和Grundy数
  - [ ] [POJ 2975: ](http://poj.org/problem?id=)
  - [ ] [POJ 3537: ](http://poj.org/problem?id=)
  - [ ] [CF 138D: ]()
  - [ ] [POJ 2315: ](http://poj.org/problem?id=)
  
# 4.3 图论（二）
- 强连通分量
  - [ ] [POJ 3180: ](http://poj.org/problem?id=)
  - [ ] [POJ 1236: ](http://poj.org/problem?id=)
  
- 2-SAT
  - [ ] [POJ 3678: ](http://poj.org/problem?id=)
  - [ ] [POJ 2723: ](http://poj.org/problem?id=)
  - [ ] [POJ 2749: ](http://poj.org/problem?id=)
  
- LCA
  - [ ] [POJ 1986: ](http://poj.org/problem?id=)
  - [ ] [POJ 3728: ](http://poj.org/problem?id=)

# 4.4 常用技巧（二）
- 栈
  - [ ] [POJ 3250: ](http://poj.org/problem?id=)
  - [ ] [POJ 2082: ](http://poj.org/problem?id=)
  - [ ] [POJ 3494: ](http://poj.org/problem?id=)
  
- 双端队列
  - [ ] [POJ 2823: ](http://poj.org/problem?id=)
  - [ ] [POJ 3260: ](http://poj.org/problem?id=)
  - [ ] [POJ 1180: ](http://poj.org/problem?id=)
  - [ ] [AOJ 1070: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=1070)
  

# 4.5 智慧搜索
- 剪枝
  - [ ] [POJ 1011: ](http://poj.org/problem?id=)
  - [ ] [POJ 2046: ](http://poj.org/problem?id=)
  - [ ] [POJ 3134: ](http://poj.org/problem?id=)
  
- A*与IDA*
  - [ ] [POJ 3523: ](http://poj.org/problem?id=)
  - [ ] [POJ 2032: ](http://poj.org/problem?id=)
  - [ ] [UVa 10181: ]()

# 4.6 分治
- 数列分治
  - [ ] [POJ 1854: ](http://poj.org/problem?id=)

- 平面分治
  - [ ] [GCJ 2009 Final B: ]()
  - [ ] [CF 97B: ]()
  
- 树分治
  - [ ] [POJ 2114: ](http://poj.org/problem?id=)
  - [ ] [UVa 12161: ]()
  - [ ] [SPOJ QTREE5: ]()
  
# 4.7 字符串
- 字符串DP
  - [ ] [AOJ 2212: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2212)
  - [ ] [CF 86C: ]()
  
- 字符串匹配
  - [ ] [CF 25E: ]()
  - [ ] [AOJ 1312: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=1312)

- 后缀数组
  - [ ] [POJ 1509: ](http://poj.org/problem?id=)
  - [ ] [POJ 3415: ](http://poj.org/problem?id=)
  - [ ] [POJ 3729: ](http://poj.org/problem?id=)
  - [ ] [AOJ 2292: ](http://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2292)
  - [ ] [CF 123D: ]()
