---
title: "Solitary Waves in the Linear Shallow Water Equation"
date: 2025-12-10
layout: post
---

{% include mathjax.html %}

# Solitary Waves in the Linear Shallow Water Equation

In this post we derive conditions under which the linear shallow water equations produce a **pure right-moving wave**.

## Governing Equations

We study the linear SWE system:

\[
h_t + \bar h\, v_x = 0, \qquad
v_t + g\, h_x = 0.
\]

## Riemann Invariants

Define

\[
w_\pm = v \pm \sqrt{\frac{g}{\bar h}}\, h.
\]

These satisfy

\[
w_{+t} + c w_{+x} = 0, \qquad
w_{-t} - c w_{-x} = 0,
\]

meaning \(w_+\) moves right and \(w_-\) moves left.

## Pure Right-Moving Solutions

To eliminate the left-traveling wave:

\[
w_-(x,0) = 0 
\quad \Longleftrightarrow \quad
v(x,0) = \sqrt{\frac{g}{\bar h}} h(x,0).
\]

This yields a solution of the form:

\[
h(x,t) = h(x - ct, 0), \qquad
v(x,t) = v(x - ct, 0).
\]

Exactly the solitary wave used in the assignment.
