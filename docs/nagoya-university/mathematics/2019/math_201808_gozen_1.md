---
sidebar_label: "2018年8月実施 午前の部 [1]"
tags:
  - Nagoya-University
  - Linear-Algebra
---
# 名古屋大学 多元数理科学研究科 2018年8月実施 午前の部 \[1\]

## **Author**
[Miyake](https://miyake.github.io/exams/index.html)

## **Description**

## **Kai**
### (1)
与えられた3本のベクトルからなる行列

$$
  \begin{aligned}
  \begin{pmatrix}
  1 & 1 & 1 \\ 2 & 0 & 1 \\ 0 & -2 & 0 \\ 1 & -1 & 2
  \end{pmatrix}
  \end{aligned}
$$

は次のように列基本変形できる：

$$
  \begin{align}
  \begin{pmatrix}
  1 & 0 & 0 \\ 2 & -2 & -1 \\ 0 & -2 & 0 \\ 1 & -2 & 1
  \end{pmatrix} \nonumber
  \\
  \begin{pmatrix}
  1 & 0 & 0 \\ 2 & 1 & -1 \\ 0 & 1 & 0 \\ 1 & 1 & 1
  \end{pmatrix} \nonumber
  \\
  \begin{pmatrix}
  1 & 0 & 0 \\ 0 & 1 & 0 \\ -2 & 1 & 1 \\ -1 & 1 & 2
  \end{pmatrix} \nonumber
  \\
  \begin{pmatrix}
  1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \\ 3 & -1 & 2
  \end{pmatrix}
  \tag{i} \label{i}
  \end{align}
$$

最後の表式の3つの列ベクトルは1次独立なので、
与えられた3本のベクトルは1次独立であることがわかる。

### (2)
与えられた3本のベクトルからなる行列

$$
  \begin{aligned}
  \begin{pmatrix}
  1 & 2 & 2 \\ 1 & 3 & 1 \\ 1 & 1 & -1 \\ 1 & 2 & 0
  \end{pmatrix}
  \end{aligned}
$$

は次のように列基本変形できる：

$$
  \begin{align}
  \begin{pmatrix}
  1 & 0 & 0 \\ 1 & 1 & -1 \\ 1 & -1 & -3 \\ 1 & 0 & -2
  \end{pmatrix} \nonumber
  \\
  \begin{pmatrix}
  1 & 0 & 0 \\ 0 & 1 & 0 \\ 2 & -1 & -4 \\ 1 & 0 & -2
  \end{pmatrix} \nonumber
  \\
  \begin{pmatrix}
  1 & 0 & 0 \\ 0 & 1 & 0 \\ 2 & -1 & 1 \\ 1 & 0 & \frac{1}{2}
  \end{pmatrix} \nonumber
  \\
  \begin{pmatrix}
  1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \\ 0 & \frac{1}{2} & \frac{1}{2}
  \end{pmatrix}
  \tag{ii} \label{ii}
  \end{align}
$$

最後の表式の3つの列ベクトルは1次独立なので、
与えられた3本のベクトルは1次独立であることがわかる。

### (3)
(1), (2) から $V_1, V_2$ はどちらも3次元であり、
($\ref{i}$), ($\ref{ii}$) から $V_1 \ne V_2$ がわかるので、
$V_1 + V_2$ は4次元であることがわかる。

### (4)
($\ref{i}$), ($\ref{ii}$) の列ベクトルを使って、
実数 $a,b,c,d,e,f$ について

$$
\begin{align}
a \begin{pmatrix} 1 \\ 0 \\ 0 \\ 3 \end{pmatrix}
+ b \begin{pmatrix} 0 \\ 1 \\0 \\ -1 \end{pmatrix}
+ c \begin{pmatrix} 0 \\ 0 \\ 1 \\ 2 \end{pmatrix}
=
d \begin{pmatrix} 1 \\ 0 \\ 0 \\ 0 \end{pmatrix}
+ e \begin{pmatrix} 0 \\ 1 \\ 0 \\ \frac{1}{2} \end{pmatrix}
+ f \begin{pmatrix} 0 \\ 0 \\ 1 \\ \frac{1}{2} \end{pmatrix}
\tag{iii} \label{iii}
\end{align}
$$

が成り立つとすると、

$$
\begin{aligned}
a=d, b=e, c=f, 2a-b+c=0
\end{aligned}
$$

を得る。
$a,b$ を決めると $c,d,e,f$ が決まるので、
$V_1 \cap V_2$ は2次元であることがわかる。

$a=1,b=0$ とすると、 $c=-2,d=1,e=0,f=-2$ となり、
ベクトル ($\ref{iii}$) は

$$
\begin{aligned}
u = \begin{pmatrix} 1 \\ 0 \\ -2 \\ -1 \end{pmatrix}
\end{aligned}
$$

となる。
また、 $a=0,b=1$ とすると、 $c=1,d=0,e=1,f=1$ となり、
ベクトル ($\ref{iii}$) は

$$
\begin{aligned}
v = \begin{pmatrix} 0 \\ 1 \\ 1 \\ 1 \end{pmatrix}
\end{aligned}
$$

となる。
ここで求めた $u,v$ は $V_1 \cap V_2$ の基底である。