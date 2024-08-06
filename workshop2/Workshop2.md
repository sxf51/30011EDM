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

### 2.1.1

${\bf{l_1}}$ is a straight line.

$$
{\bf{l_1}}(s) = (1-s) {\bf{P_1}} + s {\bf{P_2}}
$$

${\bf{l_2}}$ is circular arc of radius 1.

Let $x = cos(\frac{\pi s}{4})$, $y = sin(\frac{\pi s}{4})$.

$$
x^2 + y^2 = cos^2(\frac{\pi s}{4}) + sin^2(\frac{\pi s}{4}) = 1
$$

In cartesian coordinates, $x^2 + y^2 = 1$ is describing a circle with a radius of 1.

Plus, since $s \in [0, 1]$, $x \in [\frac{\sqrt2}{2}, 1]$, $y \in [0, \frac{\sqrt2}{2}]$.

When s increases, ${\bf{l_2}}$ moves from $(1, 0)$ to $(\frac{\sqrt2}{2}, \frac{\sqrt2}{2})$ along this circle, anticlockwise.

### 2.1.2

Fomular (8) shows that,

$$
{\bf{E}}(x, y, z) = -y {\bf{\hat{x}}} - x {\bf{\hat{y}}}
$$

For ${\bf{l_1}}$, $x = 1 - s + \frac{s}{\sqrt{2}}$, $y = \frac{s}{\sqrt{2}}$

$$
{\bf{E}}({\bf{l_1}}(s)) = -\frac{s}{\sqrt{2}} {\bf{\hat{x}}} - (1 - s + \frac{s}{\sqrt{2}}) {\bf{\hat{y}}}
$$

For ${\bf{l_2}}$, $x = cos(\frac{\pi s}{4})$, $y = sin(\frac{\pi s}{4})$

$$
{\bf{E}}({\bf{l_2}}(s)) = -sin(\frac{\pi s}{4}) {\bf{\hat{x}}} - cos(\frac{\pi s}{4}) {\bf{\hat{y}}}
$$

### 2.1.3

```Matlab
x = 0.6:.2:1.2; y = 0:.2:.8; z = 0:.2:.8;
[xx,yy,zz] = meshgrid(x,y,z);
Exx =-yy; Eyy =-xx; Ezz = 0*xx;
figure(2);
quiver3(xx,yy,zz,Exx,Eyy,Ezz);
grid on; hold on;
xhat = [1;0;0]; yhat = [0;1;0];
s = 0:.05:1;
L1 = (1- s).*xhat + s.*(xhat + yhat)/sqrt(2);
L2 = cos(pi .*s ./4).*xhat + sin(pi .*s ./4).*yhat;
plot3(L1(1,:),L1(2,:),L1(3,:),'Color',[0 .6 0],'LineWidth',2);
plot3(L2(1,:),L2(2,:),L2(3,:),'Color',[1 0 0],'LineWidth',2);
xlabel("x")
ylabel("y")
text(1,0,0,"P1","FontSize",24)
text(1/sqrt(2), 1/sqrt(2), 0, "P2", "FontSize",24)
```

![2_3_1](./img/W2_2_1.png)

### 2.1.4

$$
\begin{align*}
V_{l_1} &= -\int_{l_1} {\bf{E}} \cdot dl_1 \\
&= -\int_{l_1} {\bf{E}(l_1(s))} \cdot \frac{d{\bf{l_1}}}{ds}(s) ds \\
&= 
\end{align*}
$$
