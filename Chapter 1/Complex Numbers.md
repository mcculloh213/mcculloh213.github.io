# Chapter 1: Complex Numbers

In this chapter, we survey the algebraic and geometric structure of the complex number system. We assume various corresponding properties of real numbers to be known.

## 1.1: Sums and Products

  > **Definition 1.1.1**: **_Complex Numbers_**
  >
  > A **_complex number_** can be defined as an ordered pair $(x, y)$ of real numbers that are to be interpreted as points on the **_complex plane_**.

  > **Definition 1.1.2**: **_Complex Plane_**
  >
  > The **_complex plane_** (also referred to as the **_z-plane_**) is a geometric representation of the **_complex numbers_** established by the **_real axis_** and the perpendicular **_imaginary axis_**. It may be thought of as a modified Cartesian plane, with the **_real part_** of a complex number represented by a displacement along the x-axis (**_real axis_**), and the **_imaginary part_** by a displacement along the y-axis (**_imaginary axis_**).
  
  > **Definition 1.1.3**: **_Real Axis_**
  >
  > When a real number $x \in \mathbb{R}$ is displayed as a point $(x, 0)$, the resulting point is projected on the x-axis, or the **_real axis_** of the **_complex plane_**.
  
  > **Lemma 1.1**: $\mathbb{R} \subset \mathbb{C}$
  
  > **Definition 1.1.4**: **_Imaginary Axis_**
  >
  > Complex numbers of the form $(0, y)$ are called **_pure imaginary numbers_** when $y \neq 0$. The resulting point is projected on the y-axis or the **_imaginary axis_** of the **_complex plane_**.

It is customary to denote a **_complex numbers_** $(x, y)$ by $z$, so that (see [Figure 1](<./cartesian-plot.ipynb>))

$$z = (x, y)$$

![Figure 1](<./img/c1-fig1.svg> "Figure 1: The Complex Plane")

 > **Definition 1.1.5**: **_Real Part_**
 >
 > The real number $x$ is known as the **_real part_** of $z$. This part may be written as $x = \Re{(z)}$

 > **Definition 1.1.6**: **_Imaginary Part_**
 >
 > The real number $y$ is known as the **_imaginary part_** of $z$. This part may be written as $y = \Im{(z)}$

### Equality of Complex Numbers

Two **_complex numbers_** are **_equal_** if and only if they have the same **_real and imaginary parts_**. For two complex numbers $z_{1}, z_{2} \in \mathbb{C}$,

$$z_{1} = z_{2} \Longleftrightarrow \big(\Re{(z_{1})} = \Re{(z_{2})}\big) \wedge \big(\Im{(z_{1})} = \Im{(z_{2})}\big)$$

### Sum of Complex Numbers

The sum of any two **_complex numbers_**, $z_{1}, z_{2} \in \mathbb{C}$, may be defined as follows:

$$z_{1} + z_{2} = (x_{1}, y_{1}) + (x_{2}, y_{2})  = (x_{1} + x_{2}, y_{1} + y_{2})$$

### Product of Complex Numbers

The product of any two **_complex numbers_**, $z_{1}, z_{2} \in \mathbb{C}$, may be defined as follows:

$$z_{1}z_{2} = (x_{1}, y_{1})(x_{2}, y_{2}) = (x_{1}x_{2} - y_{1}y_{2}, y_{1}x_{2} + x_{1}y_{2})$$

# Appendix A: Definitions

## Definition 1.1.1: Complex Numbers

  > A **_complex number_** can be defined as an ordered pair $(x, y)$ of real numbers that are to be interpreted as points on the **_complex plane_**.
  
## Definition 1.1.2: Complex Plane

  > The **_complex plane_** (also referred to as the **_z-plane_**) is a geometric representation of the **_complex numbers_** established by the **_real axis_** and the perpendicular **_imaginary axis_**. It may be thought of as a modified Cartesian plane, with the **_real part_** of a complex number represented by a displacement along the x-axis (**_real axis_**), and the **_imaginary part_** by a displacement along the y-axis (**_imaginary axis_**).
  
## Definition 1.1.3: Real Axis
  
  > When a real number $x \in \mathbb{R}$ is displayed as a point $(x, 0)$, the resulting point is projected on the x-axis, or the **_real axis_** of the **_complex plane_**.
  
## Definition 1.1.4: Imaginary Axis
  
  > Complex numbers of the form $(0, y)$ are called **_pure imaginary numbers_** when $y \neq 0$. The resulting point is projected on the y-axis or the **_imaginary axis_** of the **_complex plane_**.
  
## Definition 1.1.5: Real Part

  > The real number $x$ is known as the **_real part_** of $z$. This part may be written as $x = \Re{(z)}$
  
## Definition 1.1.6: Imaginary Part

  > The real number $y$ is known as the **_imaginary part_** of $z$. This part may be written as $y = \Im{(z)}$