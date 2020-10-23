#### 题目描述
您有一个含 $n$ 个点的多边形。

您想将其放入一个长方形内，长方形的长无限长。

您可以将多边形进行旋转，使可以被放进该多边形的长方形的宽最小。

输出这个宽值。
#### 输入格式
**本题多组数据。**

每组数据的第一行为一个整数 $n$。

接下来 $n$ 行，一行两个整数 $x_i,y_i$，表示第 $i$ 个节点的坐标。

输入以一个零为结束。
#### 输出格式
对于每一个数据，先输出一行 `Case x: `，$x$ 为数据的编号。

接下来输出一个实数，表示可以被放进该多边形的长方形的最小的宽。
#### 样例
#### 样例 1 输入
```
3
0 0
3 0
0 4
4
0 10
10 0
20 10
10 20
0
```
#### 样例 1 输出
```
Case 1: 2.40
Case 2: 14.15
```
#### 数据范围及限制
对于 $100\%$ 的数据，保证 $3\le n\le 100$，$0\le x_i,y_i\le 10^4$，多边形的每一边除顶点外不交。
#### SPJ 计分标准
如果您的答案与正确答案相差在 $\frac{1}{100}$ 以内，您 AC。
#### 提交网址
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3552
- http://acm.hdu.edu.cn/showproblem.php?pid=3847
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3139
- https://codeforces.com/gym/101175
