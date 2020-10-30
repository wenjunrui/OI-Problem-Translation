#### 题目描述
有 $n$ 个机器，第 $i$ 个机器仅能在第 $D_i$ 天用 $P_i$ 元购买。

只能拥有一台机器。

购买后的第 $i$ 个机器会在第 $D_i+1$ 天起开始工作，每一天的工作可以得到 $G_i$ 元。

可以在购置第 $i$ 个机器后的任意一天以 $R_i$ 元卖出这台机器，在卖出的当天，可以买入机器，但机器无法工作。

现在有 $C$ 元，在第 $D$ 天，所有的机器都会被卖出。

您需要求出最大收益。
#### 输入格式
**本题多组数据。**

对于每组数据的第一行为三个正整数 $n,C,D$。

接下来 $n$ 行，一行四个整数 $D_i,P_i,R_i,G_i$。

输入以三个 $0$ 为结束。
#### 输出格式
对于每一组输入，请先输出 `Case x: `，其中 $x$ 为数据的组数。

接下来输出一个整数，表示能获得的最大利润。
#### 样例
#### 样例 1 输入
```
6 10 20
6 12 1 3
1 9 1 2
3 2 1 2
8 20 5 4
4 11 7 4
2 10 9 1
0 0 0
```
#### 样例 1 输出
```
Case 1: 44
```
#### 数据范围
对于 $100\%$ 的数据，保证 $1\le N\le 10^5$，$1\le C,G_i\le 10^9$，$1\le D_i\le D\le 10^9$，$1\le R_i<P_i\le 10^9$。
#### 提交网址
- https://codeforces.com/gym/101175
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3134
- http://acm.hdu.edu.cn/showproblem.php?pid=3842
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3547
