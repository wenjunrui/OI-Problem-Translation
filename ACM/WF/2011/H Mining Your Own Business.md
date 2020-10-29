#### 题目描述
有一个含 $n$ 条边的无向连通图，图中的点从 $1$ 开始编号。

您可以设置一些特殊点。

您要保证，在任意删掉一个点后，任意一个点都可以到达一个特殊点。

请计算最小化特殊点的个数以及在特殊点的个数最小时存在的方案总数。
#### 输入格式
**本题多组数据。**

每组数据的第一行为一个整数 $n$。

接下来 $n$ 行，每行两个整数 $s,t$，表示 $s$ 到 $t$ 有一条边。

输入以一个 $0$ 为结束。
#### 输出格式
对于每组数据，先输出一行 `Case x: `，$x$ 为数据的组数。

接下来不换行，输出特殊点的最小个数以及在特殊点的个数最小时存在的方案总数。

可参照样例进行理解。
#### 样例
#### 样例 1 输入
```
9
1 3
4 1
3 5
1 2
2 6
1 5
6 3
1 6
3 2
6
1 2
1 3
2 4
2 5
3 6
3 7
0
```
#### 样例 1 输出
```
Case 1: 2 4
Case 2: 4 1
```
#### 数据范围
对于 $100\%$ 的数据，保证 $1\le N\le 5\times 10^4$。
#### 提交网址
- http://acm.hdu.edu.cn/showproblem.php?pid=3844
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3549
- https://www.spoj.com/problems/BUSINESS/en/
- https://codeforces.com/gym/101175/
- https://www.e-olymp.com/en/problems/2288
- https://vjudge.net/problem/UVALive-5135/origin
