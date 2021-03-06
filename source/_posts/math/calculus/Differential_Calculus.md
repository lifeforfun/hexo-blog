---
title: 微分
---
### 导函数
> 对于定义域和值域都是实数域的函数,若 $f(x)$ 在点 $x_{0}$ 的某个邻域 $\Delta{x}$ 内,极限
> $$f'(x_{0})=\lim_{\Delta{x}\to0}\frac{f(x_0+\Delta{x})-f(x_0)}{\Delta{x}}$$
> 存在,则称函数 $f(x)$ 在点 $x_{0}$ 处可导, $f'(x0)$ 成为其`导数`,即`导函数`,可记为(`莱布尼茨`写法)
> $$\frac{df(x_0)}{dx}$$
> $f'(x)$ 为`拉格朗日`写法


> 在几何上，导数可看作函数曲线的切线斜率。

> 给定一个连续函数，计算其导数的过程称为`微分(Differentiation)`。
> 微分的逆过程称为`积分(Integration)`,函数$f(x)$的积分可以写为
> $F(x)=\int f(x)dx$
> 其中 $F(x)$ 称为 $f(x)$ 的原函数。

> - 若函数在其定义域包含的某区间内每一个点都可导，那么可以说函数在这个区间内可导。
> - 若函数在定义域中所有点都存在导数，则函数为`可微函数(Differentiable Function)`
> - 可微函数一定连续，但连续函数不一定可微。

> 对导数继续求导称为`高阶导数`。比如二阶导数可记做
> $f''(x)$ 或 $\frac{d^2f(x)}{dx^2}$
> $$(\frac{d}{dx})\times(\frac{d}{dx})\times{y}=\frac{d^{2}y}{dx^{2}}$$

### 求导基本公式
1. $p'=0$ ( $p$ 为常数)
2. $(px)'=p$ ( $p$ 为常数) 
3. $\{f(x)+g(x)\}'=f'(x)+g'(x)$ 
4. $(x^{n})'=nx^{n-1}$ (n为常数) 
5. $\{f(x)g(x)\}'=f'(x)g(x)+f(x)g'(x)$



### 三角函数导数
$$\frac{d}{dx}\sin(x)=\cos(x)$$
$$\frac{d}{dx}\cos(x)=-\sin(x)$$
$$\frac{d}{\tan(x)}=\sec^2(x)$$
$$\frac{d}{dx}\sec(x)=\sec(x)\tan(x)$$
$$\frac{d}{dx}\csc(x)=-\csc(x)\cot(x)$$
$$\frac{d}{dx}\cot(x)=-\csc^2(x)$$


### 反函数求导
$$如果y=f^{-1}(x),则\frac{dy}{dx}=\frac{1}{f'(y)}$$
$$\frac{d}{dx}(f^(-1)(x))=\frac{1}{f'(f^{-1}(x))}$$