# What's a Group?

**Definition**: A **_group_** $\left(\mathcal{G}, \circ\right)$ is a mathematical structure that is defined by of a set of elements $\mathcal{G}$, and a binary operation $\circ$. Together, $\mathcal{G}$ and $\circ$ satisfy the following properties:

  0. _Cardinality_: $\#{\mathcal{G}} > 0$
  1. _Closure_: $\forall a, b \in \mathcal{G},\ a \circ b \in \mathcal{G}$
  2. _Associativity_ $\forall a, b, c \in \mathcal{G},\ (a \circ b) \circ c = a \circ (b \circ c)$
  3. _Identity_: $\forall a \in \mathcal{G},\ \exists I \in \mathcal{G}$ such that $a \circ I = I \circ a = a$
  4. _Inverse_: $\forall a \in \mathcal{G},\ \exists b \in \mathcal{G}$ such that $b = a^{-1} \wedge a \circ a^{-1} = I$

Furthermore, a group is **_Abelian_** if and only if $\left(\mathcal{G}, \circ\right)$ satisfies an additional property:

  5. _Commutativity_: $\forall a, b \in \mathcal{G},\ a \circ b = b \circ a$

# An Abelian Group over Addition

**Proposition 1.1a**: The set of all complex numbers, $\mathbb{C}$, forms an Abelian Group under the operation $+$:

$$\forall z_{1}, z_{2} \in \mathbb{C}, z_{1} + z_{2} = (x_{1}, y_{1}) + (x_{2}, y_{2})  = (x_{1} + x_{2}, y_{1} + y_{2})$$

**Proof**: Let $\mathbb{C}$ and $+$ form the group $\left(\mathbb{C}, +\right)$. Then $\left(\mathbb{C}, +\right)$ must satisfy the following properties:

  1. _Closure_: $\forall z_{1}, z_{2} \in \mathbb{C},\ z_{1} + b \in \mathbb{C}$
  2. _Associativity_ $\forall z_{1}, z_{2}, z_{3} \in \mathbb{C},\ (z_{1} + z_{2}) + z_{3} = z_{1} + (z_{2} + z_{3})$
  3. _Identity_: $\forall z \in \mathbb{C},\ \exists I \in \mathbb{C}$ such that $z + I = I + z = z$
  4. _Inverse_: $\forall z \in \mathbb{C},\ \exists z' \in \mathbb{C}$ such that $z' = z^{-1} \wedge z + z^{-1} = I$
  
**Closure**: