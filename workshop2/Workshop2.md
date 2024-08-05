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
