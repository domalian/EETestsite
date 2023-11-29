---
title: "Circuit Analysis Using Laplace Transform"
published: true
morea_id: reading-laplaceinitial
morea_summary: "How to apply Laplace transform to analyze a circuit with initial conditions"
morea_type: reading
morea_labels:
---

# Analyze a Circuit With Initial Conditions Using Laplace Transform

## Prerequisite Knowledge
Before continuing, you must have covered:  
* Voltage-current relationships for resistors, capacitors, and inductors  
* Methods of circuit analysis  
* Laplace transformation  
* Inverse Laplace transformation  

## General steps in applying the Laplace transform:
1. Transform the circuit from time domain to the s-domain.
2. Use methods of circuit analysis such as nodal, mesh, source transformation, superposition, and other techniques that you are familiar with.
3. Transform the solution back to time domain using inverse transform.

## Laplace Transformation of Resistors, Capacitors, and Inductors
Resistors:  
    &nbsp;&nbsp;Time domain: $$ V(t) = Ri(t) $$  
    &nbsp;&nbsp;Frequency domain: $$ V(s) = Ri(s) $$  

    The impedence of resistors do not depend of time
$$
\mathscr{L}\{f(t)\}=\int_{t=0}^{\infty}f(t)e^{-st}dt
$$