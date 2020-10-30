#### 题目描述
在平面直角坐标系上有 $3$ 个点。

但是，这些点经历了缩放、平移、旋转过后，早不在他们原来的地方了。

缩放的系数是非零整数，若这个系数 $<0$，为缩小负系数倍，若 $>0$，为扩大系数倍，缩放的中心为 $(0,0)$。

每个坐标的平移量为整数，但方向未知。

旋转操作是这样进行的：选择一个整点 $(x,y)(-10\le x,y\le 10)$，旋转 $x$ 轴使其通过 $(x,y)$，并保持原先的相对长度不变，旋转之后，每个点的坐标四舍五入，注意，形如 $-x+0.5(x>0)$ 的坐标会变为 $-x$。

您知道这三个点最初的坐标和最后的坐标，您希望推断出这一系列操作。
#### 输入格式
**本题多组数据。**

对于每一组数据，输入两行，一行六个整数，第一行每两个整数表示最初一个点的横纵坐标，第二行每两个整数表示最后一个点的横纵坐标。

最后一组数据后以六个 $0$ 为结束。
#### 输出格式
对于每一组数据，先输出：`Case x: `，$x$ 为数据的组号。

接下来可能有三种输出：
- `equivalent solutions`：表示存在一个或多个解，并且每一个解中，三个点所对应的点相同。
- `inconsistent solutions`：表示存在多个解，并且解中，三个点所对应的点至少有两个解是不同的。
- `no solution`：无解。

具体可参照样例输出自行理解。
#### 样例
#### 样例 1 输入
```
3 0 4 0 1 4
-2 -4 -1 3 3 -4
0 1 1 1 2 1
1 2 2 2 3 2
1 0 2 0 3 0
3 3 1 1 2 2
1 0 2 0 3 0
3 2 1 1 2 2
2 3 0 6 1 2
2 3 0 6 1 2
0 0 0 0 0 0
```
#### 样例 1 输出
```
Case 1: equivalent solutions
Case 2: inconsistent solutions
Case 3: no solution
Case 4: inconsistent solutions
Case 5: equivalent solutions
```
#### 数据范围
对于 $100\%$ 的数据，保证输入的数 $\le 500$ 且 $\ge -500$。
#### 提交网址
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3543
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3130
- http://acm.hdu.edu.cn/showproblem.php?pid=3838
- https://codeforces.com/gym/101175
