---
layout: post
title:  "HF density matrix response"
date:   2016-11-14 06:46:48 -0700
categories: checking out the utilities
---

HF static polarizability {#hf-static-polarizability .unnumbered}
========================

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

Consider the Lagrangian for HF density matrix

$$\tilde{D}_{pq} = D^{\text{HF}}_{pq} + \sum_{tu}\left[\lambda^{(1)}_{pqtu}\left(F_{tu}-\epsilon_{tu}\right)
-\lambda^{(2)}_{pqtu}\left(S_{tu}-\delta_{tu}\right)\right]$$

Using the condition

$$\sum_{\mu}\frac{\partial \tilde{D}_{pq}}{\partial C^r_{\mu}}C^{s}_{\mu} = 0$$

it can be seen that

$$D_{sq}\delta_{qr} + D_{ps}\delta_{qr} + \sum_{tu}\lambda^{(1)}_{pqtu}\left(F_{su}\delta_{rt} + F_{ts}\delta_{ru}  
  + 2 \left[(tu|rs) - (tr|us) \right] + \lambda^{(2)}_{pqtu} \left(S_{su}\delta_{tr} + S_{ts}\delta_{ru}\right) \right) = 0 \qquad\quad$$

When $r=i$ and $s=a$

$$D_{aq}\delta_{pi} + D_{pa}\delta_{qi} + \sum_{tu}\lambda^{(1)}_{pqtu}\left(F_{au}\delta_{it} + F_{ta}\delta_{iu}  
  + 2 \left[(tu|ia) - (ti|ua) \right] + \lambda^{(2)}_{pqtu} \left(S_{au}\delta_{ti} + S_{ta}\delta_{iu}\right) \right) = 0 \label{eq:orbrot1}\qquad\quad$$

and when $r=a$ and $s=i$

$$D_{iq}\delta_{pa} + D_{pi}\delta_{qa} + \sum_{tu}\lambda^{(1)}_{pqtu}\left(F_{iu}\delta_{at} + F_{ti}\delta_{au}  
  + \lambda^{(2)}_{pqtu} \left(S_{iu}\delta_{ta} + S_{ti}\delta_{au}\right) \right) = 0\label{eq:orbrot2} \qquad$$

Since we have taken the derivative and evaluated the expressions at the
stationary point, we see that $S_{pq} = \delta_{pq}$ and the fock matrix
elements can be replaced by the corresponding orbital energies. Finally
subtracting [eq:orbrot1] - [eq:orbrot2] we get

$$\begin{split}
D_{iq}\delta_{pa} + D_{pi}\delta_{qa} &= \sum_{tu} \lambda_{pqtu} \left(F_{au}\delta_{it} + F_{ta}\delta_{iu} - F_{iu}\delta_{at} \
- F_{ti}\delta_{au} + 2 \left[(tu|ia) - (ti|ua) \right] \right) \\
&=\sum_{tu} \lambda_{pqtu}\left((\epsilon_{a}-\epsilon_i)\delta_{ta}\delta_{iu} + (\epsilon_a-\epsilon_i)\delta_{ti}\delta_{au} + 2 \left[(tu|ia) - (ti|ua) \right]\right)
\end{split}$$

where the terms involving $S$ cancel out when the equations are
subtracted.
