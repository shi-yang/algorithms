# 算法学习之旅

> 建个仓库，打算把自己 A 过的题的代码都交到这儿。

## 初期:

### 一.基本算法:

1. 枚举. (poj1753,poj2965)
2. 贪心(poj1328,poj2109,poj2586)
3. 递归和分治法.
4. 递推.
5. 构造法.(poj3295)
6. 模拟法.(poj1068,poj2632,poj1573,poj2993,poj2996)

### 二.图算法:

1. 图的深度优先遍历和广度优先遍历.
2. 最短路径算法(dijkstra,bellman-ford,floyd,heap+dijkstra) (poj1860,poj3259,poj1062,poj2253,poj1125,poj2240)
3. 最小生成树算法(prim,kruskal) (poj1789,poj2485,poj1258,poj3026)
4. 拓扑排序(poj1094)
5. 二分图的最大匹配(匈牙利算法)(poj3041,poj3020)
6. 最大流的增广路算法(KM算法).(poj1459,poj3436)

### 三.数据结构.

1. 串(poj1035,poj3080,poj1936)
2. 排序(快排、归并排(与逆序数有关)、堆排)(poj2388,poj2299)
3. 简单并查集的应用.
4. 哈希表和二分查找等高效查找法(数的Hash,串的Hash) (poj3349,poj3274,POJ2151,poj1840,poj2002,poj2503)
5. 哈夫曼树(poj3253)
6. 堆
7. trie树(静态建树、动态建树)(poj2513)

### 四.简单搜索

1. 深度优先搜索(poj2488,poj3083,poj3009,poj1321,poj2251)
2. 广度优先搜索(poj3278,poj1426,poj3126,poj3087.poj3414)
3. 简单搜索技巧和剪枝(poj2531,poj1416,poj2676,1129)

### 五.动态规划

1.背包问题.(poj1837,poj1276)
2.型如下表的简单DP(可参考lrj的书page149):

1. E[j]=opt{D+w(i,j)}(poj3267,poj1836,poj1260,poj2533)
2. E[i,j]=opt{D[i-1,j]+xi,D[i,j-1]+yj,D[i-1][j-1]+zij}(最长公共子序列) (poj3176,poj1080,poj1159)
3. C[i,j]=w[i,j]+opt{C[i,k-1]+C[k,j]}.(最优二分检索树问题)

### 六.数学

(1)组合数学:

1. 加法原理和乘法原理.
2. 排列组合.
3. 递推关系.
(POJ3252,poj1850,poj1019,poj1942)

(2)数论.
1. 素数与整除问题
2. 进制位.
3. 同余模运算.
(poj2635,poj3292,poj1845,poj2115)

(3)计算方法.
1. 二分法求解单调函数相关知识.(poj3273,poj3258,poj1905,poj3122)

### 七.计算几何学.
(1)几何公式.
(2)叉积和点积的运用(如线段相交的判定,点到线段的距离等).(poj2031,poj1039)
(3)多边型的简单算法(求面积)和相关判定(点在多边型内,多边型是否相交)
(poj1408,poj1584)
(4)凸包.(poj2187,poj1113)

## 中级:

### 一.基本算法:
1. C++的标准模版库的应用.(poj3096,poj3007)
2. 较为复杂的模拟题的训练(poj3393,poj1472,poj3371,poj1027,poj2706)

### 二.图算法:
1. 差分约束系统的建立和求解.(poj1201,poj2983)
2. 最小费用最大流(poj2516,poj2516,poj2195)
3. 双连通分量(poj2942)
4. 强连通分支及其缩点.(poj2186)
5. 图的割边和割点(poj3352)
6. 最小割模型、网络流规约(poj3308,)

### 三.数据结构.
1. 线段树.(poj2528,poj2828,poj2777,poj2886,poj2750)
2. 静态二叉检索树.(poj2482,poj2352)
3. 树状树组(poj1195,poj3321)
4. RMQ.(poj3264,poj3368)
5. 并查集的高级应用.(poj1703,2492)
6. KMP算法.(poj1961,poj2406)

### 四.搜索
1. 最优化剪枝和可行性剪枝
2. 搜索的技巧和优化(poj3411,poj1724)
3. 记忆化搜索(poj3373,poj1691)

### 五.动态规划
1. 较为复杂的动态规划(如动态规划解特别的施行商问题等)
(poj1191,poj1054,poj3280,poj2029,poj2948,poj1925,poj3034)
2. 记录状态的动态规划.(POJ3254,poj2411,poj1185)
3. 树型动态规划(poj2057,poj1947,poj2486,poj3140)

### 六.数学

#### 组合数学:
1. 容斥原理.
2. 抽屉原理.
3. 置换群与Polya定理(poj1286,poj2409,poj3270,poj1026).
4. 递推关系和母函数.

#### 数学.
1. 高斯消元法(poj2947,poj1487,poj2065,poj1166,poj1222)
2. 概率问题.(poj3071,poj3440)
3. GCD、扩展的欧几里德(中国剩余定理)(poj3101)

#### 计算方法.
1. 0/1分数规划.(poj2976)
2. 三分法求解单峰(单谷)的极值.
3. 矩阵法(poj3150,poj3422,poj3070)
4. 迭代逼近(poj3301)
5. 随机化算法(poj3318,poj2454)
6. 杂题.(poj1870,poj3296,poj3286,poj1095)

### 七.计算几何学
1. 坐标离散化.
2. 扫描线算法(例如求矩形的面积和周长并,常和线段树或堆一起使用).
(poj1765,poj1177,poj1151,poj3277,poj2280,poj3004)
3. 多边形的内核(半平面交)(poj3130,poj3335)
4. 几何工具的综合应用.(poj1819,poj1066,poj2043,poj3227,poj2165,poj3429)

## 高级:
### 一.基本算法要求:
1. 代码快速写成,精简但不失风格
(poj2525,poj1684,poj1421,poj1048,poj2050,poj3306)
2. 保证正确性和高效性.poj3434

### 二.图算法:
1. 度限制最小生成树和第K最短路.(poj1639)
2. 最短路,最小生成树,二分图,最大流问题的相关理论(主要是模型建立和求解)
(poj3155,poj2112,poj1966,poj3281,poj1087,poj2289,poj3216,poj2446
3. 最优比率生成树.(poj2728)
4. 最小树形图(poj3164)
5. 次小生成树.
6. 无向图、有向图的最小环

### 三.数据结构.
1. trie图的建立和应用.(poj2778)
2. LCA和RMQ问题(LCA(最近公共祖先问题)有离线算法(并查集+dfs)和在线算法(RMQ+dfs)).(poj1330)
3. 双端队列和它的应用(维护一个单调的队列,常常在动态规划中起到优化状态转移的目的).(poj2823)
4. 左偏树(可合并堆).
5. 后缀树(非常有用的数据结构,也是赛区考题的热点).(poj3415,poj3294)

### 四.搜索
1. 较麻烦的搜索题目训练(poj1069,poj3322,poj1475,poj1924,poj2049,poj3426)
2. 广搜的状态优化:利用M进制数存储状态、转化为串用hash表判重、按位压缩存储状态、双向广搜、A*算法.(poj1768,poj1184,poj1872,poj1324,poj2046,poj1482)
3. 深搜的优化:尽量用位运算、一定要加剪枝、函数参数尽可能少、层数不易过大、可以考虑双向搜索或者是轮换搜索、IDA*算法.(poj3131,poj2870,poj2286)

### 五.动态规划
1. 需要用数据结构优化的动态规划.(poj2754,poj3378,poj3017)
2. 四边形不等式理论.
3. 较难的状态DP(poj3133)

### 六.数学

(1)组合数学.
1. MoBius反演(poj2888,poj2154)
2. 偏序关系理论.

(2)博奕论.
1. 极大极小过程(poj3317,poj1085)
2. Nim问题.

### 七.计算几何学.
1. 半平面求交(poj3384,poj2540)
2. 可视图的建立(poj2966)
3. 点集最小圆覆盖.
4. 对踵点(poj2079)

### 八.综合题.
(poj3109,poj1478,poj1462,poj2729,poj2048,poj3336,poj3315,poj2148,poj1263)

补充dp状态设计与方程总结

#### 1.不完全状态记录
1. 青蛙过河问题
2. 利用区间dp

#### 2.背包类问题
1. 0-1背包，经典问题
2. 无限背包，经典问题
3. 判定性背包问题
4. 带附属关系的背包问题
5. +-1背包问题
6. 双背包求最优值
7. 构造三角形问题
8. 带上下界限制的背包问题(012背包)

#### 3.线性的动态规划问题
1. 积木游戏问题
2. 决斗（判定性问题）
3. 圆的最大多边形问题
4. 统计单词个数问题
5. 棋盘分割
6. 日程安排问题
7. 最小逼近问题(求出两数之比最接近某数/两数之和等于某数等等)
8. 方块消除游戏(某区间可以连续消去求最大效益)
9. 资源分配问题
10. 数字三角形问题
11. 漂亮打印
12. 邮局问题与构造答案
13. 最高积木问题
14. 两段连续和最大
15. 2次幂和问题
16. N个数的最大M段子段和
17. 交叉最大数问题

#### 4.判定性问题的dp(如判定整除、判定可达性等)
1. 模K问题的dp
2. 特殊的模K问题，求最大(最小)模K的数
3. 变换数问题

#### 5.单调性优化的动态规划
1. 1-SUM问题
2. 2-SUM问题
3. 序列划分问题(单调队列优化)

#### 6.剖分问题(多边形剖分/石子合并/圆的剖分/乘积最大)
1. 凸多边形的三角剖分问题
2. 乘积最大问题
3. 多边形游戏(多边形边上是操作符,顶点有权值)
4. 石子合并(N^3/N^2/NLogN各种优化)

#### 7.贪心的动态规划
1. 最优装载问题
2. 部分背包问题
3. 乘船问题
4. 贪心策略
5. 双机调度问题Johnson算法

#### 8.状态dp
1. 牛仔射击问题(博弈类)
2. 哈密顿路径的状态dp
3. 两支点天平平衡问题
4. 一个有向图的最接近二部图

#### 9.树型dp
1. 完美服务器问题(每个节点有3种状态)
2. 小胖守皇宫问题
3. 网络收费问题
4. 树中漫游问题
5. 树上的博弈
6. 树的最大独立集问题
7. 树的最大平衡值问题
8. 构造树的最小环

# 题目列表

1. 数论
2. 图论
3. 动态规划
4. 计算几何
5. 搜索
6. 博弈
7. 组合数学
8. 数据结构
9. 模拟

## 数论

大概有素数测试（筛法），扩展欧几里得算法，同余模运算，高斯消元，中国剩余定理，莫比乌斯反演等等。

推荐题目：

同余模运算：poj2635, poj3292,poj1845,poj2115

素数测试与筛法：poj2191，poj1811

高斯消元：poj1681，poj1222

扩展欧几里得算法：poj2891，poj1061

中国剩余定理：poj1006,zoj3538

莫比乌斯反演：poj2154

## 图论

最短路，最小生成树，拓扑排序，二分图，最大团，最大流，强连通分量，最近公共祖先，次小生成树，欧拉回路，哈密顿回路等等。

推荐题目：

最小费用最大流(poj2516,poj2516,poj2195)

双连通分量(poj2942)

强连通分支及其缩点.(poj2186)

图的割边和割点(poj3352)

最小割模型、网络流规约(poj3308, )

## 动态规划

背包问题，树形DP，数位DP等等。

推荐题目：

背包问题：hdu2602、poj3624、hdu2546、hdu2955、poj2184、hdu2639

树形DP：poj1155、hdu1011、poj1947、hdu1561、hdu4003、poj2486

概率DP：zoj3383、zoj3460、hdu4405、hdu4336

数位DP：hdu2089、hdu3555、hdu3652、poj3252

## 计算几何

点积和叉积、线段相交、多边形面积、凸包、半平面、圆与点的切线、圆与直线的交、圆与圆的交、圆与多边形的并和交、三维凸包、三维点和直线等等。

推荐题目：

点积和叉积：poj2318、poj2398

线段相交：poj3304、poj1269、poj2653、poj1066、poj1039

凸包：poj1113、poj3348、poj1318、poj1696、hdu1392、poj2187、hdu1348

半平面交：poj3335、poj3130、poj1474、poj1278

曼哈顿距离：hdu4666、poj2926

## 搜索

dfs、bfs、A*、IDA*、双向广搜等等。

推荐题目：

dfs：poj1724、hrbustoj1179、hdu1728、hdu1045、hdu1312、sdut2152、hdu1426、poj2386、hdu2553、hdu1022、hdu1241、hdu1016、hdu1010、hdu1175

bfs:poj3984、poj3278、hdu1242、hdu1240、hdu1195、hdu2717、hdu1253、hdu1026、hdu1180、hdu2612

## 博弈

巴什博弈、威佐夫博奕、Fibonacci博弈、尼姆博弈、公平组合博弈等等。

博弈代码一般都很短，只要分析出来公式（或规律），不难实现。

推荐题目：

poj1067、poj1740、poj2234、poj1082、poj2348、poj2413、poj2419

## 组合数学

容斥原理、抽屉原理、置换群与Polya定理、母函数等等。

推荐题目：

置换群：poj2369、poj1026、poj1721、poj3270、poj1879

Polya定理：hdu1812、hdu1817、hdu2481、hdu1286

容斥原理：hdu2204、hdu3208、hdu1796、hdu2841、hdu1695

## 数据结构

串处理、栈和队列、树、哈希、二分查找、并查集、线段树、二维线段树、哈夫曼树、后缀数组等等。

数据结构内容比较杂，涉及的又都是基础的知识，其中的很多思想都可以用在其他题目上，一定要学好。

这里把它作为一个方向，是为了它到了后期的一些高级的数据结构，例如字典树、划分树、线段树、AC自动机等等。

推荐题目：

查找（二分、哈希）：poj3349、poj1002、hdu2141、hdu1025

串（AC自动机、KMP）：hdu3695、hdu2203、sdut2411、poj2406、hdu1358、hdu3336

并查集：poj2236、poj2524、poj1182、poj1611、hdu1232

字典树：poj2503、poj2001、hdu1247、hdu1075、hdu1251

树状数组：hdu1556、poj1195、poj3321、hdu1541/poj2352

线段树：poj2155、poj1195、poj3468、poj3264、hdu1556、hdu1698、hdu1754、hdu1166

划分树：poj2104、sdut2610

## 模拟
题目：

hdu1030、hdu1033、hdu1035、hdu1057、hdu1063、hdu1002、hdu1004、hdu1013、hdu1015、hdu1017、hdu1020、hdu1022、hdu1029、hdu1031、hdu1033、hdu1034、hdu1035、hdu1036、hdu1037、hdu1039、hdu1042、hdu1047、hdu1048、hdu1049、hdu1050、hdu1057、hdu1062



最后加个10。

## STL

STL，Standard Template Library，标准模板库。
