# ELEN30011 EDM Task

- Xiufu SUN 1372750
- Wenyang SUN 1354302

## 1.1

${\bf{\nabla \cdot F}}$ (div $\bf{F}$) is a scalar, ${\bf{\nabla \times F}}$ is a vector field.

Explaination: $\Downarrow$

## 1.2

Let $\bf{F}$ : $\mathbb{R^3} \to \mathbb{R^3}$ be a vector field with

$$
{\bf{F}}(x, y, z) = F_x(x, y, z){\bf{\hat{x}}} + F_y(x, y, z){\bf{\hat{y}}} + F_z(x, y, z){\bf{\hat{z}}}
$$

The divergence of $\bf{F}$ (div $\bf{F}$) is

$$
\begin{align*}
    {\bf{\nabla \cdot F}} &= (\frac{\partial}{\partial{x}}, \frac{\partial}{\partial{y}}, \frac{\partial}{\partial{z}})\cdot (F_x, F_y, F_z) \\
    &= \frac{\partial{F_x}}{\partial{x}} + \frac{\partial{F_y}}{\partial{y}} + \frac{\partial{F_z}}{\partial{z}}
\end{align*}
$$

${\bf{\nabla \cdot F}}$ is a scalar.

$$
\begin{align*}
{\bf{\nabla \times F}} &= (\frac{\partial}{\partial{x}}{\bf{\hat{x}}} + \frac{\partial}{\partial{y}}{\bf{\hat{y}}} + \frac{\partial}{\partial{z}}{\bf{\hat{z}}}) \times (F_x(x, y, z){\bf{\hat{x}}} + F_y(x, y, z){\bf{\hat{y}}} + F_z(x, y, z){\bf{\hat{z}}}) \\
&=
\begin{vmatrix}
    {\bf{\hat{x}}} &{\bf{\hat{y}}} &{\bf{\hat{z}}} \\
    \frac{\partial}{\partial{x}} & \frac{\partial}{\partial{y}} & \frac{\partial}{\partial{z}} \\
    F_x & F_y & F_z
\end{vmatrix} \\
&= (\frac{\partial{F_z}}{\partial{y}} - \frac{\partial{F_y}}{\partial{z}}){\bf{\hat{x}}} + (\frac{\partial{F_x}}{\partial{z}} - \frac{\partial{F_z}}{\partial{x}}){\bf{\hat{y}}} + (\frac{\partial{F_x}}{\partial{y}} - \frac{\partial{F_y}}{\partial{x}}){\bf{\hat{z}}}
\end{align*}
$$

${\bf{\nabla \times F}}$ is a vector field.

## 1.3

(a)

$$
grad f = \nabla{f} = \frac{\partial{f}}{\partial{x}}{\bf{\hat{x}}} + \frac{\partial{f}}{\partial{y}}{\bf{\hat{y}}} + \frac{\partial{f}}{\partial{z}}{\bf{\hat{z}}} = 0{\bf{\hat{x}}} + 0{\bf{\hat{y}}} + 0{\bf{\hat{z}}}
$$

(b)

$$
grad f = \nabla{f} = \frac{\partial{f}}{\partial{x}}{\bf{\hat{x}}} + \frac{\partial{f}}{\partial{y}}{\bf{\hat{y}}} + \frac{\partial{f}}{\partial{z}}{\bf{\hat{z}}} = 1{\bf{\hat{x}}} + z{\bf{\hat{y}}} + y{\bf{\hat{z}}}
$$

(c)

$$
grad f = \nabla{f} = \frac{\partial{f}}{\partial{x}}{\bf{\hat{x}}} + \frac{\partial{f}}{\partial{y}}{\bf{\hat{y}}} + \frac{\partial{f}}{\partial{z}}{\bf{\hat{z}}} = x{\bf{\hat{x}}} + (y+\frac{1}{2}z^2 siny){\bf{\hat{y}}} - zcosy{\bf{\hat{z}}}
$$

(d)

$$
grad f = \nabla{f} = \frac{\partial{f}}{\partial{x}}{\bf{\hat{x}}} + \frac{\partial{f}}{\partial{y}}{\bf{\hat{y}}} + \frac{\partial{f}}{\partial{z}}{\bf{\hat{z}}} = \frac{2x}{x^2 + y^2 + z^2}{\bf{\hat{x}}} + \frac{2y}{x^2 + y^2 + z^2}{\bf{\hat{y}}} + \frac{2z}{x^2 + y^2 + z^2}{\bf{\hat{z}}}
$$

## 1.4

(a)

$$
div {\bf{F}} = {\bf{\nabla \cdot F}} = \frac{\partial{F_x}}{\partial{x}} + \frac{\partial{F_y}}{\partial{y}} + \frac{\partial{F_z}}{\partial{z}} = 0
$$

$$
curl {\bf{F}} = {\bf{\nabla \times F}} =
\begin{vmatrix}
    {\bf{\hat{x}}} &{\bf{\hat{y}}} &{\bf{\hat{z}}} \\
    \frac{\partial}{\partial{x}} & \frac{\partial}{\partial{y}} & \frac{\partial}{\partial{z}} \\
    F_x & F_y & F_z
\end{vmatrix} =
\begin{vmatrix}
    {\bf{\hat{x}}} &{\bf{\hat{y}}} &{\bf{\hat{z}}} \\
    \frac{\partial}{\partial{x}} & \frac{\partial}{\partial{y}} & \frac{\partial}{\partial{z}} \\
    0 & 0 & 0
\end{vmatrix} = 0{\bf{\hat{x}}} + 0{\bf{\hat{y}}} + 0{\bf{\hat{z}}}
$$

(b)

$$
div {\bf{F}} = {\bf{\nabla \cdot F}} = \frac{\partial{F_x}}{\partial{x}} + \frac{\partial{F_y}}{\partial{y}} + \frac{\partial{F_z}}{\partial{z}} = -1 + 1 = 0
$$

$$
curl {\bf{F}} = {\bf{\nabla \times F}} =
\begin{vmatrix}
    {\bf{\hat{x}}} &{\bf{\hat{y}}} &{\bf{\hat{z}}} \\
    \frac{\partial}{\partial{x}} & \frac{\partial}{\partial{y}} & \frac{\partial}{\partial{z}} \\
    F_x & F_y & F_z
\end{vmatrix} =
\begin{vmatrix}
    {\bf{\hat{x}}} &{\bf{\hat{y}}} &{\bf{\hat{z}}} \\
    \frac{\partial}{\partial{x}} & \frac{\partial}{\partial{y}} & \frac{\partial}{\partial{z}} \\
    -x & 0 & z
\end{vmatrix} = 0{\bf{\hat{x}}} + 0{\bf{\hat{y}}} + 0{\bf{\hat{z}}}
$$

(c)

$$
div {\bf{F}} = {\bf{\nabla \cdot F}} = \frac{\partial{F_x}}{\partial{x}} + \frac{\partial{F_y}}{\partial{y}} + \frac{\partial{F_z}}{\partial{z}} = 0
$$

$$
curl {\bf{F}} = {\bf{\nabla \times F}} =
\begin{vmatrix}
    {\bf{\hat{x}}} &{\bf{\hat{y}}} &{\bf{\hat{z}}} \\
    \frac{\partial}{\partial{x}} & \frac{\partial}{\partial{y}} & \frac{\partial}{\partial{z}} \\
    F_x & F_y & F_z
\end{vmatrix} =
\begin{vmatrix}
    {\bf{\hat{x}}} &{\bf{\hat{y}}} &{\bf{\hat{z}}} \\
    \frac{\partial}{\partial{x}} & \frac{\partial}{\partial{y}} & \frac{\partial}{\partial{z}} \\
    z & 0 & -x
\end{vmatrix} = [1 - (-1)] {\bf{\hat{y}}} = 2 {\bf{\hat{y}}}
$$

(d)

$$
div {\bf{F}} = {\bf{\nabla \cdot F}} = \frac{\partial{F_x}}{\partial{x}} + \frac{\partial{F_y}}{\partial{y}} + \frac{\partial{F_z}}{\partial{z}} = \frac{\partial^2{f}}{\partial{x^2}} + \frac{\partial^2{f}}{\partial{y}} + \frac{\partial^2{f}}{\partial{z^2}}
$$

$$
\begin{align*}
curl {\bf{F}} = {\bf{\nabla \times F}} &=
\begin{vmatrix}
    {\bf{\hat{x}}} &{\bf{\hat{y}}} &{\bf{\hat{z}}} \\
    \frac{\partial}{\partial{x}} & \frac{\partial}{\partial{y}} & \frac{\partial}{\partial{z}} \\
    F_x & F_y & F_z
\end{vmatrix} =
\begin{vmatrix}
    {\bf{\hat{x}}} &{\bf{\hat{y}}} &{\bf{\hat{z}}} \\
    \frac{\partial}{\partial{x}} & \frac{\partial}{\partial{y}} & \frac{\partial}{\partial{z}} \\
    \frac{\partial{f}}{\partial{x}} & \frac{\partial{f}}{\partial{y}} & \frac{\partial{f}}{\partial{z}}
\end{vmatrix} \\
&= (\frac{\partial^2{f}}{\partial{y}\partial{z}} - \frac{\partial^2{f}}{\partial{z}\partial{y}}){\bf{\hat{x}}} + (\frac{\partial^2{f}}{\partial{z}\partial{x}} - \frac{\partial^2{f}}{\partial{x}\partial{z}}){\bf{\hat{y}}} + (\frac{\partial^2{f}}{\partial{y}\partial{x}} - \frac{\partial^2{f}}{\partial{x}\partial{y}}){\bf{\hat{z}}} \\
&= 0{\bf{\hat{x}}} + 0{\bf{\hat{y}}} + 0{\bf{\hat{z}}}
\end{align*}
$$

## 1.5

```Matlab
close all
clear
clc

x = -3:.75:3;
y = -2:.75:2;
z = -3:.75:3;

[X, Y, Z] = meshgrid(x, y, z);

FX = -X;
FY = 0.*Y;
FZ = Z;

figure(1);
quiver3(X,Y,Z,FX,FY,FZ)
xlabel("x");
ylabel("y");
zlabel("z");
title("Visualization of the field F in 1.4(b)")
```

![Visualization of the field F in 1.4(b)](./img/W2_1_5b.png)

```Matlab
close all
clear
clc

x = -3:.75:3;
y = -2:.75:2;
z = -3:.75:3;

[X, Y, Z] = meshgrid(x, y, z);

FX = Z;
FY = 0.*Y;
FZ = -X;

figure(1);
quiver3(X,Y,Z,FX,FY,FZ)
xlabel("x");
ylabel("y");
zlabel("z");
title("Visualization of the field F in 1.4(c)")
```

![Visualization of the field F in 1.4(c)](./img/W2_1_5c.png)

## 2.1
