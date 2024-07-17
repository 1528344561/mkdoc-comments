# 函数

## To Review

区间再现

## 积分

### 积分的性质

含有第一类间断点或无穷间断点的函数f(x)在包含该间断点的区间内一定没有原函数

导函数一定没有可去间断点,跳跃间断点,无穷间断点.

以上均不包括震荡间断点. $x^2\sin\frac1x$

### $\int e^{ax}\sin bxdx$ / $\int e^{ax}\cos bxdx$ 

$\int e^{ax}\sin bx dx$ = 
$\frac 1{a^2+b^2}
\begin{vmatrix}
(e^{ax})' & (\sin bx)' \\
e^{ax} & \sin bx
\end{vmatrix}
$

### $\Gamma$ 函数

$\Gamma(\alpha) = \int_{0}^{+\infty} x^{\alpha-1}e^{-x}dx =^{x=t^2}2\int_{0}^{+\infty} t^{2\alpha-1}e^{-t^2}dt$

$\Gamma(1) = \Gamma(2) = 1$ $\ \ \ \ \ \Gamma(\frac{1}{2}) = \sqrt{\pi}$

$\Gamma(1+\alpha) = \alpha\Gamma(\alpha)$

### 反常积分

#### 变上限积分

$\int_{0}^{\varphi(x)} f(t) dt$ 阶数为 $\varphi(x)$ 的阶数乘以 $(f(t)$ 的阶数 $+1)$

#### 关于变限积分的可导性和连续性

只有可去间断点的函数其变限积分一定可导.

有跳跃间断点,则变限积分不可导,但连续.

> 注意可积和有原函数不是一个概念,可积不代表有原函数.
> 含有第一类间断点或无穷间断点的函数一定没有原函数.
> 求原函数(即不定积分)是求导的逆运算,而可积(积分)本质上是求面积

参见[https://blog.csdn.net/weixin_45415929/article/details/127674480](1)

可导性:可导即意味着变化率,如果变化率处处存在,自然就代表可导.
$对于一个变限积分F(x)=\int_a^xf(x)dx,他的变化量就是\Delta xf(x),那么变化率就是f(x),自然,若f(x)连续,也就是F'(x)处处存在,自然可导$

$而如果f(x)有可去间断点,那么在这个点的两端的f(x)极限存在且相等,F(x)从左右两边逼近的变化量就都是\Delta xf(x),变化率也是相等的$
## 二重积分

### 偏导数

对 $x$ 求偏导若为 $0$,不能说明 $f(x,y) = g(y)$.  (张宇第1讲研究对象大观02 53:20)

事实上,对 $x$ 求偏导为 $0$ ,只能说明在一个很小的区间上是与 $x$ 无关,不能说明在整个区域上也无关