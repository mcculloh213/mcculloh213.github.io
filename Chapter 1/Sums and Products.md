# Complex Numbers &mdash; Sums and Products

> **Definition 1.1.1**: A **_complex number_** can be defined as an ordered pair $(x, y)$ of real numbers that may be interpreted as points on the complex plane.

<hr />

> **Definition 1.1.2**: The **_complex plane_** (also referred to as the **_z-plane_**) is a geometric representation of the complex numbers established by the real axis and the perpendicular imaginary axis. It may be thought of as a modified Cartesian plane, with the real part of a complex number represented by a displacement along the x-axis (real axis), and the imaginary part by a displacement along the y-axis (imaginary axis).

&mdash; [Wikipedia](https://en.wikipedia.org/wiki/Complex_plane)

<hr />

> **Definition 1.1.3**: When a real number $x \in \mathbb{R}$ is displayed as a point $(x, 0)$, the resulting point is projected on the x-axis, or the **_real axis_** of the complex plane.

<hr />

> **Definition 1.1.4**: Complex numbers of the form $(0, y)$ are called **_pure imaginary numbers_** when $y \neq 0$. The resulting point is projected on the y-axis or the **_imaginary axis_** of the complex plane.

<hr />

By denoting a complex number, $z$, as a point $(x, y)$, we may plot $z$ as if it were a point on the Cartesian plane, such that (see [Figure 1](<./cartesian-plot.ipynb>)):

$$z = (x, y)$$

![Figure 1](<./img/c1-fig1.svg> "Figure 1: The Complex Plane")

> **Definition 1.1.5**: The real number $x$ is known as the **_real part_** of $z$. This part may be written as $x = \Re{(z)}$

> **Definition 1.1.6**: The real number $y$ is known as the **_imaginary part_** of $z$. This part may be written as $y = \Im{(z)}$

### Equality of Complex Numbers

Two complex numbers are **_equal_** if and only if they have the same real and imaginary parts. For two complex numbers $z_{1}, z_{2} \in \mathbb{C}$,

$$z_{1} = z_{2} \Longleftrightarrow \big(\Re{(z_{1})} = \Re{(z_{2})}\big) \wedge \big(\Im{(z_{1})} = \Im{(z_{2})}\big)$$

### Operation: Addition

The **_sum_** of any two complex numbers, $z_{1}, z_{2} \in \mathbb{C}$, may be defined as follows:

$$z_{1} + z_{2} = (x_{1}, y_{1}) + (x_{2}, y_{2})  = (x_{1} + x_{2}, y_{1} + y_{2})$$

Naturally, it follows that the sum of two complex numbers (neither with an **_imaginary part_**), the operation follows the expected definition of addition under real numbers.

$$(x_{1}, 0) + (x_{2}, 0) = (x_{1} + x_{2}, 0)$$

**Proposition 1.1a**: The set of all complex numbers, $\mathbb{C}$, forms an Abelian Group under the operation $+$:

$$\forall z_{1}, z_{2} \in \mathbb{C}, z_{1} + z_{2} = (x_{1}, y_{1}) + (x_{2}, y_{2})  = (x_{1} + x_{2}, y_{1} + y_{2})$$

_[proof](<./Proposition 1-1a.md>)_

### Operation: Multiplication

The **_product_** of any two **_complex numbers_**, $z_{1}, z_{2} \in \mathbb{C}$, may be defined as follows:

$$z_{1}z_{2} = (x_{1}, y_{1})(x_{2}, y_{2}) = (x_{1}x_{2} - y_{1}y_{2}, y_{1}x_{2} + x_{1}y_{2})$$

Much like addition, the product of two complex numbers (neither with an **_imaginary part_**) follows the expected definition of multiplication under real numbers.

$$(x_{1}, 0) (x_{2}, 0) = (x_{1} x_{2}, 0)$$

### A Natural Extension of the Real Numbers

Using the previously stated definitions of addition and multiplication, we may begin to rationalize the **_complex numbers_** as a natural extention of the real numbers.



**Proposition 1.1b**: The set of all complex numbers, $\mathbb{C}$, forms an Abelian Group under the operation $\times$:

$$\forall z_{1}, z_{2} \in \mathbb{C}, z_{1} z_{2} = (x_{1}, y_{1}) (x_{2}, y_{2}) = (x_{1}x_{2} - y_{1}y_{2}, y_{1}x_{2} + x_{1}y_{2})$$