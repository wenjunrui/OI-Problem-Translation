#### 题目描述
有一款数字处理器，它的名字叫 `a-C-m`。

这款数字处理器接受一个参数 $x$，可对其进行如下操作：
- `A`：$x\gets x+a$。
- `M`：$x\gets x\times m$。

现在我们有多个 `a-C-m` 处理器和四个整数 $p,q,r,s$，您需要求出在 $p\le x\le q$ 中的 $x$ 经过尽量少的操作后可以得到 $r\le y\le s$ 中的 $y$ 所使用的方案。

如果无解，请输出 `impossible`。

如果不需要操作，请输出 `empty`。

由于这个题的出题人不愿意写 SPJ，所以您需要输出字典序最小的方案。
#### 输入格式
**本题多组数据。**

每一组数据有六个正整数 $a,m,p,q,r,s$。

输入由六个 $0$ 结束。
#### 输出格式
对于每一个数据，先输出一行 `Case x: `，$x$ 为数据的编号。

接下来输出您所使用的方案，如果无解，请输出 `impossible`，如果不需要操作，请输出 `empty`。

方案输出方式：
- `nA`：进行 $n$ 次 `A` 操作。
- `nM`：进行 $n$ 次 `M` 操作。

操作用空格隔开。

可根据样例进行理解。
#### 样例
#### 样例 1 输入
```
1 2 2 3 10 20
1 3 2 3 22 33
3 2 2 3 4 5
5 3 2 3 2 3
0 0 0 0 0 0
```
#### 样例 1 输出
```
Case 1: 1A 2M
Case 2: 1M 2A 1M
Case 3: impossible
Case 4: empty
```
#### 数据范围及限制
对于 $100\%$ 的数据，保证 $1\le a,m,p,q,r,s\le 10^9$，$p\le q$，$r\le s$，$n>0$。
#### 提交网址
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3542
- https://codeforces.com/gym/101175
- http://acm.hdu.edu.cn/showproblem.php?pid=3837
- https://www.spoj.com/problems/ADDMUL/en/
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3129
