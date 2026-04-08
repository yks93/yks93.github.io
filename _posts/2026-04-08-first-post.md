---
layout: default
title: "Geometry of Representations"
date: 2026-04-09
---

Modern machine learning models can be interpreted through the **geometry of their representations**.

Rather than viewing neural networks as purely algebraic systems, we can understand them as constructing and transforming geometric structures in high-dimensional spaces.

---

## 1. Representation as Geometry

Each layer defines a mapping:

$$
x \;\mapsto\; \phi(x)
$$

This induces a geometry on the data manifold.

- distances encode similarity  
- angles capture relational structure  
- curvature reflects complexity of representation  

👉 The network is effectively **learning a metric space** over data.

---

## 2. Attention as Geometric Interaction

Attention computes pairwise interactions:

$$
A(Q, K) = QK^\top
$$

This can be interpreted as an **inner product geometry** over token representations.

After scaling and normalization:

$$
\text{softmax}\!\left(\frac{QK^\top}{\sqrt{d}}\right)
$$

we obtain a distribution over interactions.

👉 Attention defines a **data-dependent metric** that evolves across layers.

---

## 3. Learning as Geometric Transformation

Training can be viewed as progressively reshaping geometry:

- aligning semantically similar points  
- separating classes via deformation  
- amplifying task-relevant directions  

This suggests:

> Learning = **geometric optimization of representation space**

---

## 4. Broader Perspective

This viewpoint connects machine learning with:

- differential geometry  
- information geometry  
- statistical physics  

It opens directions for:

- principled architectures  
- interpretability via geometry  
- generalization through structure  

---

## 5. Open Questions

- What geometric invariants are preserved across layers?  
- Can curvature predict generalization?  
- Is attention learning an adaptive Riemannian metric?  

---

## Summary

Neural networks do not merely compute—they **organize space**.

Understanding this geometry may be key to explaining:
- why models generalize  
- how representations emerge  
- what structure is being learned
