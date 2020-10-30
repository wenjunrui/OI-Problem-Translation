#### 题目描述
有一个 $N\times N$ 的芯片，芯片上有 $N\times N$ 的插槽，可以在里面放零件。

插槽的类型如下：
- `/`：该插槽不可以放零件。
- `C`：该插槽已有一个零件。
- `.`：该插槽可以放零件。

您需要满足：
- 第 $i$ 列和第 $i$ 行的零件个数要一样多。
- 第 $i$ 行的零件个数不能超过放在芯片上的总零件个数的 $\frac{A}{B}$。

您需要求出最多可以另外放多少个零件。
#### 输入格式
**本题多组数据。**

对于每一组数据，先输入三个数 $N,A,B$。

接下来 $N$ 行，每行 $N$ 个字符，表示整个芯片。
#### 输出格式
对于每一组数据，先输出一行 `Case x: `，其中 $x$ 为数据的组号。

接下来输出一个数，表示你的答案。

特别的，如果无解，请输出 `impossible`。
#### 样例
#### 样例 1 输入
```
2 1 1
/.
//
2 50 100
/.
C/
2 100 100
./
C.
5 3 10
CC/..
././/
..C.C
/.C..
/./C/
5 2 10
CC/..
././/
..C.C
/.C..
/./C/
0 0 0
```
#### 样例 1 输出
```
Case 1: 0
Case 2: 1
Case 3: impossible
Case 4: 7
Case 5: impossible
```
#### 数据范围
对于 $100\%$ 的数据，保证 $1\le N\le 40$，$1\le B\le 10^3$，$0\le A\le B$。
#### 提交网址
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3545
- http://acm.hdu.edu.cn/showproblem.php?pid=3840
- https://codeforces.com/gym/101175
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3132
