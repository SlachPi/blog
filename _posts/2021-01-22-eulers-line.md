# A Proof Of Euler's Theorem

After reading coxeter's book "Introduction to geometry"...which is awesome ! I tried to find my own proof that in any triangle the center of gravity, the circumcenter and the orthocenter lies on a same line, the so called Euler's line. This proof that I present here, I hope, is a new proof of this classical Euler's Line Theorem.

## The Proof

Let's consider a triangle $ABC$ and denote by $O$ its circumcenter, by $G$ its center of gravity, and by $H$ its orthocenter. Whthout loss of generality, we will suppose that neither of $\angle BAC$ and $\angle ACB$ is a right angle.

First let's put a cartesian coordinate system such that O is the origin and the X-axis is parallel to $AC$. So that we will, consequently, have that the Y-axis intersect $AC$ perpendicularly in the middle, and thus $x_A = -x_C$ and $y_A = y_C$.

It is an elementary fact that if $x_B = 0$ each of $G$,$O$ and $H$ will lie on the Y-axis. So let's consider the non-obvious case where $x_B \neq 0$.

We can easily calculate that:

$$\left\{\begin{array}{c}x_G = {1\over 3}(x_A + x_B + x_C) = {1 \over 3}x_B\\y_G = {1\over 3}(y_A + y_B + y_C) ={2\over 3} y_A + {1 \over 3} y_B\end{array}\right.$$

Now, if we call $H'$ the intersection of $(OG)$ and the altitude of $AC$. Because the line $(BH')$ , being perpendicular to the X-axis, is defined by the equation $x = x_B$ , we have :

$$\left\{\begin{array}{c} x_{H'} = x_B \\ y_h = ({y_G \over x_G}) \times x_{H'} = 2y_A+y_B\end{array}\right.$$

We remind that $x_G = {1 \over 3}x_B \neq 0$. 

Now, if we can prove that $H'$ lies on the altitude of $AB$, the proof will be complete.

To prove that it suffies to show that the lines $(CH')$ and $(AB)$ are perpendicular, or equivalently that the product of their slopes is equal to $-1$.

This product is :

$${{y_A - y_B}\over{x_A - x_B}} \times {{y_{H'} - y_C}\over{x_{H'} - x_C}} = {{y_A - y_B}\over{x_A - x_B}} \times {{2y_A+y_B - y_A}\over{x_B + x_A}} = - {{y_A^2 - y_B^2}\over{x_B^2 - x_A^2}}$$

We remind that neither $x_A - x_B$ nor $x_{H'} - x_C$ is equal to $0$ because neither $\angle BAC$ nor $\angle ACB$ is a right angle . 

Let's now use the fact that $A$, $B$ and $C$ are lying on the same circle centered at the origin.

$$R^2 = x_A^2 + y_A^2 = x_B^2+y_B^2  \implies {{y_A^2 - y_B^2}\over{x_B ^2-x_A^2}}=1$$

And thus the proof is complete.

This shows how a right choice of coordinate system can make things obvious.
