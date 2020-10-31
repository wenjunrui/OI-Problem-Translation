#### 题目描述
您需要构造一个 $n\times n$ 字符矩阵 $M$。

这个字符矩阵有如下几条限制：
1. $M_{i,j}=M_{j,i}(1\le i,j\le n)$。
1. 必须恰好含有 $a_i$ 个字符 $c_i$。

因为构造的方案有很多种，所以你需要输出方案中字典序最小的。

因为输出太多不好，所有你只需要输出 $p$ 列，具体的方案将会在输入格式中声明。

如果无解，请输出 `IMPOSSIBLE`。
#### 输入格式
第一行为两个整数 $n$ 和 $k$，$k$ 表示限制 $2$ 的条数。

接下来 $k$ 行，每一行为一个大写字母和一个整数，分别为 $c_i$ 和 $a_i$。

接下来一行为一个整数 $p$。

接下来一行 $p$ 个整数，表示你需要输出的列的标号，保证按升序出现。
#### 输出格式
为一个 $p$ 行 $n$ 列的字符矩阵，如果无解，请输出 `IMPOSSIBLE`。
#### 样例
#### 样例 1 输入
```
3 3
A 3
B 2
C 4
3
1 2 3 
```
#### 样例 1 输出
```
AAB
ACC
BCC
```
#### 样例 2 输入
```
4 4
A 4
B 4
C 4
D 4
4
1 2 3 4
```
#### 样例 2 输出
```
AABB
AACC
BCDD
BCDD
```
#### 样例 3 输入
```
4 5
E 4
A 3
B 3
C 3
D 3
2
2 4 
```
#### 样例 3 输出
```
AC
BE
DE
ED 
```
#### 样例 4 输入
```
4 6
F 1
E 3
A 3
B 3
C 3
D 3
4
1 2 3 4 
```
#### 样例 4 输出
```
IMPOSSIBLE
```
#### 数据范围
- 对于 $60\%$ 的数据，保证 $n\le 300$。
- 对于 $80\%$ 的数据，保证 $n\le 3\times 10^3$。
- 对于 $100\%$ 的数据，保证 $1\le n\le 3\times 10^4$，$1\le k\le 26$，$\sum a_i=n^2$，$c_i\neq c_j$，$1\le p\le 50$。
#### 提交网址