---
title: Problem 5
summary: A particle of mass $m$, charge $q$ and position $\mathbf{x}$ ...
type: book
---

## Solution

According to Newton's second law of motion, the equation of motion is written as
{{< math >}}
$$
\mathbf{\ddot{x}} = \mathbf{g} + \frac{q}{m} \mathbf{\dot{x}} \times \mathbf{B}.
$$
{{< math >}}

Now suppose we have
{{< math >}}
$$
\mathbf{\dot{x}} = \alpha \mathbf{x} \times \mathbf{n} + \mathbf{g}t + \mathbf{a},
$$
{{< math >}}
where $\alpha = qB/m$, $\mathbf{n}$ is the unit vector in the direction of  $\mathbf{B}$ and $\mathbf{a} = a\mathbf{n}$, we want to find the initial position $\mathbf{x}(0) = (x(0), y(0), z(0))$ with repect to the chosen origin. Since the magnetic field $\mathbf{B}$ is horizontal, we can represent its direction as $\mathbf{n} = (\cos\theta, \sin\theta, 0)$. Now the equation above can be rewritten as a group of 3 equations,
{{< math >}}
$$
\begin{align*}
\dot{x} &= a\cos\theta - \frac{qB}{m}z\sin\theta \\
\dot{y} &= a\sin\theta + \frac{qB}{m}z\cos\theta \\
\dot{z} &= \frac{qB}{m}(x\sin\theta - y\cos\theta) - gt
\end{align*}.
$$
{{< math >}}
Solving these equations by taking the derivative of the third equation and substituting $\dot{x}$ and $\dot{y}$ with the first two equations. Then we get 
{{< math >}}
$$
\ddot{z} = -(\frac{qB}{m})^2z - g.
$$
{{< math >}}
Thus, we can solve $(x(t), y(t), z(t))$ as following,
{{< math >}}
$$
\begin{align*}
x(t) &= a\cos\theta t - \sin\theta(A\sin(\omega t + \varphi) - \frac{g}{\omega^2}t) \\
y(t) &= a\sin\theta t + \cos\theta(A\sin(\omega t + \varphi) - \frac{g}{\omega^2}t) \\
z(t) &= A\cos(\omega t + \varphi) - \frac{g}{\omega^2}
\end{align*},
$$
{{< math >}}
where $\omega = (\frac{qB}{m})^2$, $A$ and $\varphi$ are parameters related to the inital position. Now we have
{{< math >}}
$$
\begin{align*}
x(0) &= -A\sin\theta\sin\varphi \\
y(0) &= A\cos\theta\sin\varphi \\
z(0) &= A\cos\varphi
\end{align*},
$$
{{< math >}}
which means that the projection of the initial position vector $\mathbf{x}(0)$ on the $xy$-plane should be perpendicular to the magnetic field $\mathbf{B}$.

We choose $x$-axis the same direction as $\mathbf{B}$, and to simplify the problem, we choose $a=0$ and $\varphi = 0$, then we find that 
{{< math >}}
$$
\begin{align*}
\dot{x} &= 0 \\
\dot{y} &= A\omega\cos\omega t - \frac{g}{w} \\
\dot{z} &= -A\omega\sin\omega t
\end{align*}.
$$
{{< math >}}
The equations above show that the particle is undergoing a helical motion with a constant horizontal drift. To eliminate this drift, we can apply an electric field
{{< math >}}
$$
\mathbf{E} = -\frac{m}{q}\mathbf{g}.
$$
{{< math >}}
