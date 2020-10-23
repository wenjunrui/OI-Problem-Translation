#### 题目描述
您需要在一幅图像中识别六种古埃及文字，如图：

![](https://cdn.luogu.com.cn/upload/image_hosting/eijy6t9f.png)
#### 输入格式
**本题多组数据。**

每组样例的第一行包含两个整数 $H,W$。

接下来 $H$ 行，一行 $W$ 个整数，中间没有空格，表示图像扫描后（`0` 表示白色，`1` 表示黑色）用 $16$ 进制转换后表示的图像。

输入的结束以两个零为标记。
#### 输出格式
对于每一组输入，请先输出 `Case x: `，其中 $x$ 为数据的组数。

接下来，按字典序输出您识别到的文字的编码，如下所示：

| 文字 | 编码 |
|:-:|:-:|
| Ankh | A | 
| Wedjat | W | 
| Djed | D | 
| Scarab | S |
| Was | W | 
| Akhet | K | 

可根据样例进行理解。
#### 样例
#### 样例 1 输入
```
100 25
0000000000000000000000000
0000000000000000000000000
省略 50 行。
00001fe0000000000007c0000
00003fe0000000000007c0000
省略 44 行。
0000000000000000000000000
0000000000000000000000000
150 38
00000000000000000000000000000000000000
00000000000000000000000000000000000000
省略 75 行。
0000000003fffffffffffffffff00000000000
0000000003fffffffffffffffff00000000000
省略 69 行。
00000000000000000000000000000000000000
00000000000000000000000000000000000000
0 0
```
#### 样例 1 输入
```
Case 1: AKW
Case 2: AAAAA
```
#### 样例 1 解释
![](https://cdn.luogu.com.cn/upload/image_hosting/xs43gqzp.png)
![](https://cdn.luogu.com.cn/upload/image_hosting/ucq721oc.png)

以上两幅图是样例。
#### 数据范围及限制
对于 $100\%$ 的数据，保证 $1\le H\le 200$，$1\le W\le 50$，输入的图像不会包含其他的象形文字，每张图像里至少包含一个有效的象形文字，图中的每个黑色像素都属于一个象形文字，象形文字之间不接触，不包含，象形文字可能会变形，但在拓扑上仍等价于给出的几种象形文字。
#### 名词解释
> 拓扑

如果可以通过拉伸而使得两个图形转换成同一个图形，则这两个图形在拓扑上等价。
#### 提交网址
- https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3131
- https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3544
- https://codeforces.com/gym/101175
- http://acm.hdu.edu.cn/showproblem.php?pid=3839
