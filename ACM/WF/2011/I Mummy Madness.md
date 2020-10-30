#### 题目描述
您在被 $n$ 只怪物追逐！

您和怪物所在的地图被抽象成了一个二维网格。

您最初位于 $(0,0)$。

追逐分为一轮一轮来追逐。

对于每一轮：
- 首先行动的是您，您可以移动到您所在的方格八连通的任意方格。
- 接下来行动的是怪物们，每个怪物都会移动到距您最近的八连通方格，距离以欧几里得距离计算。

您已经呼叫了救援，但您需要拖怪物们更多的时间，您需要求出，您能拖延的最长时间，即您最多需要多久会被抓住。
#### 输入格式
**本题多组数据。**

每组数据的第一行只有一个数 $n$。

接下来 $n$ 行，每行两个数 $x,y$，表示有一个怪物位于 $(x,y)$。

数据以一个 $-1$ 为结束。
#### 输出格式
对于每一组数据，先输出一行 `Case x: `，$x$ 为数据的组号。

接下来输出您最多需要多久会被抓住，如果您永远也不会被抓住，输出 `never`。

可参照样例进行理解。
#### 样例
#### 样例 1 输入
```
4
-3 5
3 4
-6 -2
1 -5
1
0 -1
-1
```
#### 样例 1 输出
```
Case 1: 4
Case 2: never
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
对于 $100\%$ 的限制，保证 $0\le n\le 10^5$，$|x|,|y|\le 10^6$。
#### 提交网址
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3550
- http://acm.hdu.edu.cn/showproblem.php?pid=3845
- https://codeforces.com/gym/101175
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3137
- 
