---
layout: post
title:  "Hartree-Fock density matrix response"
date:   2016-11-14 06:46:48 -0700
categories: checking out the utilities
---

HF static polarizability {#hf-static-polarizability .unnumbered}
========================

Consider the Lagrangian for HF density matrix

<span>rCl</span> ~pq~ &=& D^^~pq~ + ~tu~

Using the condition

<span>rCl</span> ~~C^s^~~ = 0

it can be seen that

<span>rCl</span> D~sqqr~ + D~psqr~ + ~tu~^(1)^~pqtu~(F~surt~ + F~tsru~ +
2 + ^(2)^~pqtu~ (S~sutr~ + S~tsru~) ) = 0

When $r=i$ and $s=a$

<span>rCl</span> D~aqpi~ + D~paqi~ + ~tu~^(1)^~pqtu~(F~auit~ + F~taiu~ +
2 + ^(2)^~pqtu~ (S~auti~ + S~taiu~) ) = 0 [eq:orbrot1]

and when $r=a$ and $s=i$

<span>rCl</span> D~iqpa~ + D~piqa~ + ~tu~^(1)^~pqtu~(F~iuat~ + F~tiau~ +
^(2)^~pqtu~ (S~iuta~ + S~tiau~) ) = 0[eq:orbrot2]

Since we have taken the derivative and evaluated the expressions at the
stationary point, we see that $S_{pq} = \delta_{pq}$ and the fock matrix
elements can be replaced by the corresponding orbital energies. Finally
subtracting [eq:orbrot1] - [eq:orbrot2] we get

<span>rCl</span> D~iqpa~ + D~piqa~ &=& ~tu~ ~pqtu~ (F~auit~ + F~taiu~ -
F~iuat~ - F~tiau~ + 2 )\
&=&~tu~ ~pqtu~((~a~-~i~)~taiu~ + (~a~-~i~)~tiau~ + 2 )

where the terms involving $S$ cancel out when the equations are
subtracted.

<span>rCl</span> A
