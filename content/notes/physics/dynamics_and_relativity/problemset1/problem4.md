---
title: Problem 4
summary: A long time ago, in a galaxy far far away ...
type: book
---

## Solution
## Fme
## Fyou

First, we dot product $\mathbf{\dot{r}}$ onto both sides of the given equation, we get 
{{< math >}}
$$
\mathbf{\ddot{r}} \cdot \mathbf{\dot{r}} = 0.
$$
{{< math >}}
which means the acceleration is perpendicular to the velocity. Therefore $|\mathbf{\dot{r}}| = v$ is a constant.

Then we dot product $\mathbf{r}$ onto both sides of the given equation, we get
{{< math >}}
$$
\mathbf{\ddot{r}} \cdot \mathbf{r} = 0.
$$
{{< math >}}
Taking the derivative of the original equation, we get
{{< math >}}
$$
\frac{\mathrm d \mathbf{\ddot{r}}}{\mathrm d t} =  \lambda\mathbf{r} \times \mathbf{\ddot{r}}.
$$
{{< math >}}
Dot product equation (1) with $\mathbf{\ddot{r}}$, we get
$$
\mathbf{\ddot{r}} \cdot \frac{\mathrm d \mathbf{\ddot{r}}}{\mathrm d t} = 0,
$$
{{< math >}}
which means the changing of acceleration is perpendicular to the acceleration. Therefore $|\mathbf{\ddot{r}}| = a$ is also a constant.

## Subtask a

If $\mathbf{\dot{r}}$ is parallel to $\mathbf{r}$, then
{{< math >}}
$$
\mathbf{\ddot{r}} = \mathbf{0}.
$$
{{< math >}}
This gives us 
{{< math >}}
$$
\mathbf{\dot{r}} = v\mathbf{\hat{r}}.
$$
{{< math >}}
By integrating equation (2), we will get the trajectory is 
{{< math >}}
$$
\mathbf{r} = (vt+R)\mathbf{\hat{r}}.
$$
{{< math >}}

## Subtask a

Taking the derivative of $\mathbf{r} \cdot \mathbf{r}$, we get
{{< math >}}
$$
\frac{\mathrm d}{\mathrm d t}(\mathbf{r} \cdot \mathbf{r}) = 2 \mathbf{r} \cdot \mathbf{\dot{r}}.
$$
{{< math >}}
Also, given 
{{< math >}}
$$
\mathbf{r} \cdot \mathbf{r} = r^2,
$$
{{< math >}}
as well as 
{{< math >}}
$$
r^2 = v^2(t-t_0)^2 + r_0^2,
$$
{{< math >}}
we have
{{< math >}}
$$
\frac{\mathrm d}{\mathrm d t}(\mathbf{r} \cdot \mathbf{r}) = 2v^2(t-t_0).
$$
{{< math >}}
Thus, we get 
{{< math >}}
$$
\mathbf{r} \cdot \mathbf{\dot{r}} = v^2(t-t_0).
$$
{{< math >}}
Considering that
{{< math >}}
$$
|\mathbf{\ddot{r}}| = \lambda rv \sin\theta,
$$
{{< math >}}
and 
{{< math >}}
$$
\mathbf{r} \cdot \mathbf{\dot{r}} = rv \cos\theta,
$$
{{< math >}}
Combining equation (5) and (6), we find 
{{< math >}}
$$
|\mathbf{\ddot{r}}|^2 + (\lambda \mathbf{r} \cdot \mathbf{\dot{r}}) = \lambda^2r^2v^2.
$$
{{< math >}}
By subsituting equation (7) with (3) and (4), we finally get
{{< math >}}
$$
|\mathbf{\ddot{r}}| = \lambda v r_0.
$$
{{< math >}}
