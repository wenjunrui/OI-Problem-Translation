#### 题目描述
在您的家乡有许多咖啡店。

您的家乡可以被抽象成一个二维的平面，长为 $dx$，宽为 $dy$。

每个咖啡店用一个横坐标和一个纵坐标表示。

定义 $\text{dist}(a,b)=\lvert a_x-b_x\rvert+\lvert a_y-b_y\rvert$，这表示 $a,b$ 两点的距离。

共有 $q$ 组询问，每组询问给出 $x$。

请您求出一个点 $a$，使得 $\text{dist}(\text{咖啡店},a)\le x$ 的咖啡店个数最大。

如果有多个点，请输出横坐标最小的，如果还有多个点，请输出纵坐标最小的。
#### 输入格式
**本题多组数据。**

每组数据的第一行为四个整数 $dx,dy,n,q$。

接下来 $n$ 行，一行两个整数 $x_i,y_i$，表示第 $i$ 个咖啡馆的坐标。

接下来 $q$ 行，一行一个整数 $x$。
#### 输出格式
对于每组数据，请先输出一行 `Case x:`，其中 $x$ 为数据组号。

接下来 $q$ 行，每一行的格式如：`x (y,z)`，其中 $x$ 为 $\text{dist}(\text{咖啡店},a)\le x$ 的咖啡店个数，$y$ 为 $a$ 的横坐标，$z$ 为 $a$ 的纵坐标。

可参照样例理解。
#### 样例
#### 样例 1 输入
```
4 4 5 3
1 1
1 2
3 3
4 4
2 4
1
2
4
0 0 0 0
```
#### 样例 1 输出
```
Case 1:
3 (3,4)
4 (2,2)
5 (3,1)
```
#### 数据范围及限制
对于 $100\%$ 的数据，保证 $1\le dx,dy\le 10^3$，$0\le n\le 5\times 10^5$，$1\le q\le 20$，$1\le x_i\le dx$，$1\le y_i\le dy$，$0\le x\le 10^6$。
#### 提交网址
- https://www.e-olymp.com/en/problems/2285
- http://acm.hdu.edu.cn/showproblem.php?pid=3841
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3133
- https://codeforces.com/gym/101175/
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3546
