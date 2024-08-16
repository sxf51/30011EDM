# ELEN30011 EDM Task

- Xiufu SUN 1372750
- Wenyang SUN 1354302

## 1.1

### 1.1.1

The electric field is given as:

$$
\mathbf{E} = \mathbf{E}(r, \phi, \theta) = E(r) \mathbf{\hat{r}}
$$

This means that the electric field is a function of the radial distance \(r\) and is directed along the radial unit vector \(\hat{r}\). The hint suggests considering symmetry to explain this configuration.

### Solution

1. **Symmetry Considerations**:
   - The spherical symmetry of the problem suggests that the electric field should be the same in all directions from the center. This means that the electric field cannot depend on the angular coordinates \(\phi\) and \(\theta\), as this would imply a preferred direction, which contradicts the symmetry.
   - Since the system is spherically symmetric, the electric field must be radial. The only remaining degree of freedom is the distance from the center, so the electric field can only be a function of \(r\), the radial distance.

2. **Gauss’s Law**:
   - Gauss’s law for electricity states that the electric flux through a closed surface is proportional to the charge enclosed by that surface.
   - To apply Gauss’s law effectively in this configuration, the electric field must be uniform over the surface of a sphere centered at the origin. This uniformity ensures that the flux can be easily calculated as the product of the electric field magnitude and the surface area of the sphere.
   - If the electric field had components in directions other than the radial direction, these components would cancel out when integrated over a symmetric spherical surface, leaving only the radial component.

3. **Conclusion**:
   - Due to the spherical symmetry of the problem, the electric field \(\mathbf{E}\) must be radially directed and uniform with respect to the angles \(\phi\) and \(\theta\). The form \(E(r)\hat{r}\) reflects this requirement, where \(E(r)\) is a scalar function that depends only on the radial distance \(r\).

### 1.1.2

$$
\begin{align}
   \rho_{in}(r) = (\frac{Q}{\pi a^4})r && Cm^{-3}
\end{align}
$$

$$
\begin{align*}
   Q_{in}(r) &= \int_0^r\int_0^{2\pi}\int_0^{\pi} \rho_{in}(\alpha)\alpha^2 sin\theta d\theta d\phi d\alpha \\
   &= 2\pi \int_0^r\int_0^{\pi} (\frac{Q}{\pi a^4})\alpha^3 sin\theta d\theta d\alpha \\
   &= 4\pi (\frac{Q}{\pi a^4}) \int_0^r \alpha^3 d\alpha \\
   &= Q(\frac{r}{a})^4 & C
\end{align*}
$$

### 1.1.3

In 1.1.2, we get when $r \in [0, a]$, $Q_{in}(r) = Q(\frac{r}{a})^4$ C.

If $r \in (a, b)$, $\rho = 0$, $Q$ will be:

$$
\begin{align*}
   Q_{in}(r) &= \int_0^a\int_0^{2\pi}\int_0^{\pi} \rho_{in}(\alpha)\alpha^2 sin\theta d\theta d\phi d\alpha \\
   &= 2\pi \int_0^a\int_0^{\pi} (\frac{Q}{\pi a^4})\alpha^3 sin\theta d\theta d\alpha \\
   &= 4\pi (\frac{Q}{\pi a^4}) \int_0^a \alpha^3 d\alpha \\
   &= Q(\frac{a}{a})^4 \\
   &= Q & C
\end{align*}
$$

### 1.1.4

- Based on Gauss's law in its integral form states:

   $$
   \oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{in}}{\epsilon},
   $$

1. **For \(r \in [0, a]\)**:

   $$
   \begin{align*}
      Q_{in}(r) &= Q(\frac{r}{a})^4 & C
   \end{align*}
   $$

   Gauss's law:

   $$
   \oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{in}}{\epsilon},
   $$

   Solving $\oint_{\partial V} \mathbf{E} \cdot d\mathbf{A}$:

   $$
   \begin{align*}
   \oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} &= \iint \mathbf{E} \cdot r^2 sin\phi d\phi d\theta \mathbf{\hat{r}}\\
   &= 4\pi r^2 \mathbf{E}(r)
   \end{align*}
   $$

   Hence, when $r \in [0, a]$:

   $$
   E(r) = \frac{Q(\frac{r}{a})^4}{4\pi \epsilon r^2} = \frac{Q}{4 \pi \epsilon a^2} \left(\frac{r}{a}\right)^2.
   $$

2. **For $r \in (a, b]$**:

   $$
   \begin{align*}
      Q_{in}(r) &= Q & C
   \end{align*}
   $$

   Solving $\oint_{\partial V} \mathbf{E} \cdot d\mathbf{A}$:

   $$
   \oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = 4\pi r^2 \mathbf{E}(r)
   $$

   Hence, when $r \in (a, b)$:

   $$
   E(r) = \frac{Q}{4\pi \epsilon r^2} = \frac{Q}{4 \pi \epsilon a^2} \left(\frac{a}{r}\right)^2.
   $$

The electric field \(\mathbf{E}(r)\) in the interior and immediately surrounding the solid sphere is derived using Gauss's law and is given by:

$$
\mathbf{E}(r) = \frac{Q}{4 \pi \epsilon a^2}
\begin{cases}
   \left(\frac{r}{a}\right)^2 \hat{r}, & r \in [0, a], \\
   \left(\frac{a}{r}\right)^2 \hat{r}, & r \in (a, b].
\end{cases}
$$

## 1.2

### 1.2.1

The charge enclosed by that surface is zero. From Gauss'law $\oint \mathbf{E} d\mathbf{A} = 0$ this implies that the electric field inside a sphere is zero. If we add an electron inside the shell, the electrons on the surface will experience a force. This will cause them to move on the surface such that the net forcefield becomes zero again. The charge will move freely to counteract any electric field inside. Therefore, when a conductive spherical shell is in electronic equilbrium, there should be no net electric field present inside. This is because the charge within the conductor will redistribute itself so as to create opposing electric fields within the candutert to cancel out any electric field present within it.

### 1.2.2

Based on the answer to 1.2.1,we knew that the value of electric field in the interval from $r \in (b, b + d)$ is zero. According to the formula of flux: $\oiint_{\mathbf{A}} \mathbf{E} d\mathbf{A}$, because of $\mathbf{E} = \mathbf{0}$ the flux $\oiint_{\mathbf{A}} \mathbf{E} d\mathbf{A} = 0$.
$\mathbf{Q} = \mathbf{E} \cdot \phi$ because of $E = 0, \mathbf{Q} = 0$, thus the total charge contained with this test surface must be zero.

### 1.2.3

## 1.3

### 1.3.1

If $r \in (b, b + d)$, $Q$ will be:

$$
\begin{align*}
   Q(r) &= \oiint_{A} \rho d\mathbf{A} \\
   &= \int_0^a\int_0^{2\pi}\int_0^{\pi} \rho_{in}(\alpha)\alpha^2 sin\theta d\theta d\phi d\alpha \\
   &= 2\pi \int_0^a\int_0^{\pi} (\frac{Q}{\pi a^4})\alpha^3 sin\theta d\theta d\alpha \\
   &= 4\pi (\frac{Q}{\pi a^4}) \int_0^a \alpha^3 d\alpha \\
   &= Q(\frac{a}{a})^4 \\
   &= Q & C
\end{align*}
$$
