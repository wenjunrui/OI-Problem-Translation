#### 题目描述
现在有一个序列 $a$，将序列中的元素依次放进一个 BST 里，求 BST 中插入函数的执行次数。

**注意：第一个数已经作为 BST 的根。**

如果您无法理解上面说的话，这里有一份伪代码：

```
insert( number x, node n )
    c+1;
    if x is less than the number in node n
        if n has no left child
            create a new node with the number x and set it to be the left child of node n
     else
         insert(x, left child of node n)
     else (x is greater than the number in node n)
         if n has no right child
             create a new node with the number x and set it to be the right child of node n
         else
             insert(x, right child of node n) 
```
您需要求的就是上面的 insert 函数每进行一次后 $c$ 的值。

**再次注意：第一个数已经作为 BST 的根。**
#### 输入格式
第一行，一个整数 $n$，表示序列 $a$ 的长度。

接下来 $n$ 行，每行一个整数，第 $i$ 行为 $a_i$。
#### 输出格式
共 $n$ 行，一行一个整数，表示上面的 insert 函数每进行一次后 $c$ 的值。
#### 样例
#### 样例 1 输入
```
4
1
2
3
4
```
#### 样例 1 输出
```
0
1
3
6
```
#### 样例 2 输入
```
5
3
2
4
1
5 
```
#### 样例 2 输出
```
0
1
2
4
6 
```
#### 样例 3 输入
```
8
3
5
1
6
8
7
2
4 
```
#### 样例 3 输出
```
0
1
2
4
7
11
13
15 
```
#### 数据范围
- 对于 $50\%$ 的数据，保证 $n\le 10^3$。
- 对于 $100\%$ 的数据，保证 $1\le n\le 3\times 10^5$，$1\le a_i\le n$。
