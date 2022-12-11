---
title: Problem 4
summary: A long time ago, in a galaxy far far away ...
type: book
---

## Solution
First, we dot product $\mathbf{\dot{r}}$ onto both sides of the given equation, we get 
$$
\mathbf{\ddot{r}} \cdot \mathbf{\dot{r}} = 0.
$$
which means the acceleration is perpendicular to the velocity. Therefore $|\mathbf{\dot{r}}| = v$ is a constant.

Then we dot product $\mathbf{r}$ onto both sides of the given equation, we get
$$
\mathbf{\ddot{r}} \cdot \mathbf{r} = 0.
$$
Taking the derivative of the original equation, we get
$$
\frac{\mathrm d \mathbf{\ddot{r}}}{\mathrm d t} =  \lambda\mathbf{r} \times \mathbf{\ddot{r}}.
$$
Dot product equation (1) with $\mathbf{\ddot{r}}$, we get
$$
\mathbf{\ddot{r}} \cdot \frac{\mathrm d \mathbf{\ddot{r}}}{\mathrm d t} = 0,
$$
which means the changing of acceleration is perpendicular to the acceleration. Therefore $|\mathbf{\ddot{r}}| = a$ is also a constant.

### Subtask a

If $\mathbf{\dot{r}}$ is parallel to $\mathbf{r}$, then
$$
\mathbf{\ddot{r}} = \mathbf{0}.
$$
This gives us 
$$
\mathbf{\dot{r}} = v\mathbf{\hat{r}}.
$$
By integrating equation (2), we will get the trajectory is 
$$
\mathbf{r} = (vt+R)\mathbf{\hat{r}}.
$$

### Subtask b

Taking the derivative of $\mathbf{r} \cdot \mathbf{r}$, we get
$$
\frac{\mathrm d}{\mathrm d t}(\mathbf{r} \cdot \mathbf{r}) = 2 \mathbf{r} \cdot \mathbf{\dot{r}}.
$$
Also, given 
$$
\mathbf{r} \cdot \mathbf{r} = r^2,
$$
as well as 
$$
r^2 = v^2(t-t_0)^2 + r_0^2,
$$
we have
$$
\frac{\mathrm d}{\mathrm d t}(\mathbf{r} \cdot \mathbf{r}) = 2v^2(t-t_0).
$$
Thus, we get 
$$
\mathbf{r} \cdot \mathbf{\dot{r}} = v^2(t-t_0).
$$
Considering that
$$
|\mathbf{\ddot{r}}| = \lambda rv \sin\theta,
$$
and 
$$
\mathbf{r} \cdot \mathbf{\dot{r}} = rv \cos\theta,
$$
Combining equation (5) and (6), we find 
$$
|\mathbf{\ddot{r}}|^2 + (\lambda \mathbf{r} \cdot \mathbf{\dot{r}}) = \lambda^2r^2v^2.
$$
By subsituting equation (7) with (3) and (4), we finally get
$$
|\mathbf{\ddot{r}}| = \lambda v r_0.
$$
