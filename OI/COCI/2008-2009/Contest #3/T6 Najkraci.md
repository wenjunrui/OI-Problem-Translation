#### 题目描述
有一个含 $n$ 个点，$m$ 条边的**有向图**。

对于每一条边，求出它被任意两点的最短路径经过的次数对 $10^9+7$ 取模的值。

如果 $A, B$ 两点之间有多条最短路，每条最短路都要计算一遍。你可以参考样例 $4$ 中第 $3, 4$ 条边的输出来理解这句话。
#### 输入格式
第一行两个整数 $n$ 和 $m$。

接下来 $m$ 行，每行三个整数 $x$ ，$y$，$d$，即有一条 $x$ 到 $y$ 的有向边，边权为 $d$。
#### 输出格式
共 $m$ 行，每一行输出一个整数，第 $i$ 行的数表示在第 $i+1$ 行读入的边被任意两点的最短路径经过的次数对 $10^9+7$ 取模的值。
#### 样例
#### 样例 1 输入
```
4 3
1 2 5
2 3 5
3 4 5
```
#### 样例 1 输出
```
3
4
3 
```
#### 样例 2 输入
```
4 4
1 2 5
2 3 5
3 4 5
1 4 8 
```
#### 样例 2 输出
```
2
3
2
1 
```
#### 样例 3 输入
```
5 8
1 2 20
1 3 2
2 3 2
4 2 3
4 2 3
3 4 5
4 3 5
5 4 20
```
#### 样例 3 输出
```
0
4
6
6
6
7
2
6
```
#### 样例 4 输入
```
4 4
1 2 1
2 3 1
1 3 2
3 4 1
```
#### 样例 4 输出
```
3
4
2
4
```
#### 数据范围与约定
- 对于 $30\%$ 的数据，保证 $n\le 15$，$m\le 30$。
- 对于 $60\%$ 的数据，保证 $n\le 300$，$m\le 10^3$。
- 对于 $100\%$ 的数据，保证 $1\le n\le 1.5\times 10^3$，$1\le m\le 5\times 10^3$，$a\neq b$，$1\le a,b\le n$，$1\le d\le 10^4$。