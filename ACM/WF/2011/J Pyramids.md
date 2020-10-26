#### 题目描述
定义高金字塔为从下到上分别由 $a\times a\times 1$ 的长方体、$(a-1)\times (a-1)\times 1$ 的长方体 $\ldots$ $1\times 1\times 1$ 的长方体组成。

定义矮金字塔从下到上分别由 $a\times a\times 1$ 的长方体、$(a-2)\times (a-2)\times 1$ 的长方体 $\ldots$ $1\times 1\times 1$ 或者 $2\times 2\times 1$ 的长方体组成。

现在有 $n$ 块 $1\times 1\times 1$ 的正方体，现在您需要构造一种满足下述条件建金字塔的方案：

1. 所有的正方体都要用到。
1. 您必须最小化金字塔的个数。
3. 所有的金字塔必须不同。
4. 每个金字塔的高度至少为 $2$。
1. 在满足以上条件的前提下，最大的金字塔包含尽可能多的正方体。
1. 在满足以上条件的前提下，次大的金字塔包含尽可能多的正方体。
1. 以此类推。

输出可能存在的方案，或者直接输出 `impossible`，表示这是不可能的。
#### 输入格式
**本题多组数据。**

每组数据的读入仅有一行一个整数 $n$。

输入以一个 $0$ 为结束。
#### 输出格式
对于每组数据，先输出一行 `Case x: `，$x$ 为数据的编号。

接下来输出您构造的方案，您构造的方案顺序应如下：

1. 底边大的先输出。
2. 如果底边相等，先输出高金字塔。

每个金字塔的表示由一个数字（表示底边长度）和一个字母 `H` 或 `L` （`H` 为高金字塔，`L` 为矮金字塔）表示。

如果无解，请输出 `impossible`。
#### 样例
#### 样例 1 输入
```
29
28
0
```
#### 样例 1 输出
```
Case 1: 3H 3L 2H
Case 2: impossible
```
#### 数据范围及限制
对于 $100\%$ 的数据，保证 $1\le n\le 10^6$。
#### 提交网址
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3551
- http://acm.hdu.edu.cn/showproblem.php?pid=3846
- https://codeforces.com/gym/101175/
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3138
