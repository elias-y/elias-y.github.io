---
title: "Solitary Waves in the Linear Shallow Water Equation"
date: 2025-12-10
layout: post
---

{% include mathjax.html %}

# Solitary Waves in the Linear Shallow Water Equation

In this post we derive conditions under which the linear shallow water equations produce a **pure right-moving wave**.

## Governing Equations

We study the linear Shallow Water Equation (SWE):

$$
\begin{aligned}
h_t + \bar h\, v_x = 0 \\
v_t + g\, h_x = 0
\end{aligned}
$$

## Riemann Invariants

Define

$$
w_\pm = v \pm \sqrt{\frac{g}{\bar h}}h
$$

It is easy to check that these satisfy

$$
\begin{aligned}
w_{+t} + c w_{+x} = 0 \\
w_{-t} - c w_{-x} = 0
\end{aligned}
$$

These are constant coefficient transport equations, meaning $w_+$ moves right and $w_-$ moves left.

## Pure Right-Moving Solutions

To eliminate the left-traveling wave we impose that

$$
w_-(x,0) = 0 
\quad \Longleftrightarrow \quad
v(x,0) = \sqrt{\frac{g}{\bar h}} h(x,0).
$$

Changing back to the physical variables, this yields a solution of the form:

$$
\begin{aligned}
h(x,t) = h(x - ct, 0) \\
v(x,t) = v(x - ct, 0)
\end{aligned}
$$

Exactly a solitary right moving wave.
