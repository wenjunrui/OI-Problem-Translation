#### 题目描述
称一对区间 $[L_1:R_1],[L_2:R_2]$ 是相交的当且仅当 $L_1\le R_2$ 且 $L_2\le R_1$。

现在有一道经典问题出现在了小 T 与小 A 的面前：

有 $N$ 个区间 $[L_1:R_1],\cdots,[L_N:R_N]$，现想选出尽量多的区间，保证区间两两不相交。

小 T 选择先将区间按 $R_i$ 的值从小到大排序，再贪心选择。

小 A 选择先将区间按 $L_i$ 的值从小到大排序，再贪心选择。

现给出 $N$ 和 $M$，请构造 $N$ 个区间，使得小 T 的方法求出的值减去小 A 的方法求出的值恰好等于 $M$。
#### 输入格式
仅有两个整数 $N$，$M$。
#### 输出格式
输出 $N$ 行，每行两个整数 $L_i,R_i$。

您需要保证：
- $1\le L_i<R_i\le 10^9$。
- $L_i\not=L_j(i\not=j)$。
- $R_i\not=R_j(i\not=j)$。
- $L_i\not=R_j$。
- $L_i,R_i$ 均为整数
#### 样例
#### 样例 1 输入
```
5 1
```
#### 样例 1 输出
```
1 10
8 12
13 20
11 14
2 4
```
#### 样例 2 输入
```
10 -10
```
#### 样例 2 输出
```
-1
```
#### 数据范围
对于 $100\%$ 的数据，保证 $1\le N\le 2\times 10^5$，$-N\le M\le N$。