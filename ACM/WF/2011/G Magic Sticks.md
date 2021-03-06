#### 题目描述
有一根可以折叠的木棍，木棍上有 $n+1$ 个节点（包括木棍的头尾）把木棍分为 $n$ 段。

仅有节点可以作为折叠的端点。

您要求出，将木棍折叠后并将两端接起来后所形成的多边形的面积最大值。
#### 输入格式
**本题多组数据。**

对于每一组数据，先输入一个整数 $n$。

接下来一行 $n$ 个数，表示 $n+1$ 个节点将木棍分成 $n$ 段后，每一段的长度 $S_i$。

输入以一个 $0$ 为结束。
#### 输出格式
对于每一组数据，先输出一行 `Case x: `，$x$ 表示数据的组号。

接下来输出一个浮点数，表示将木棍折叠后并将两端接起来后所形成的多边形的面积最大值。
#### 样例
#### 样例 1 输入
```
4
1 2 3 4
8
3 4 5 33 3 4 3 5
0
```
#### 样例 1 输出
```
Case 1: 4.898979
Case 2: 19.311
```
#### 数据范围
对于 $100\%$ 的数据，保证 $1\le n\le 500$，$1\le S_i\le 10^3$。
#### 提交网址
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3548
- http://acm.hdu.edu.cn/showproblem.php?pid=3843
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3135
- https://codeforces.com/gym/101175
