# De Giorgi Conjecture for the p-Laplace Equation

This repository hosts AI-assisted research manuscripts on the De Giorgi conjecture for the p-Laplace equation $$-\Delta_p u = u(1-u^2)^{p-1}$$. Together the drafts address one-dimensional symmetry in dimension seven and eight for different ranges of $$p$$, construct nonplanar monotone entire solutions in dimension nine for every $$p>1$$, and produce nonplanar entire minimizers in dimension eight for every $$1<p<\infty$$. They complement the classical $$p=2$$ Allen–Cahn theory and illustrate how the exponent $$p$$ affects both the positive symmetry results and the counterexamples.

**Draft status:** All manuscripts present candidate proofs. The team is continuing to verify every argument. The summaries below describe the statements and proofs as currently drafted.

* * *

## Manuscripts

### 1. Stable De Giorgi conjecture for the p-Laplace equation in dimension seven

**[Read the PDF](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/Stable_DeGiorgi_N7.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 7 |
| **Range** | $$p > 1$$ |
| **Length** | Scanned PDF (text layer unavailable) |

The PDF is a scanned document without an extractable text layer, so the following description is based on the filename and the surrounding p-Laplace De Giorgi literature. The manuscript appears to address the stability of entire solutions to the matched p-Laplace equation in dimension seven. It is expected to serve as one of the dimension-seven inputs for the dimension-eight symmetry result in Manuscript 4.

* * *

### 2. The matched p-Laplace De Giorgi problem near $$p=2$$ in dimension eight

**[Read the PDF](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/p_laplace_N8_near_two.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 8 |
| **Range** | $$0 < |p-2| < \varepsilon_0$$ |
| **Length** | Research manuscript |

Assuming two rigidity results in dimension seven, the manuscript proves that every entire weak solution of $$-\Delta_p u = u(1-u^2)^{p-1}$$ in $$\mathbb{R}^8$$, with values in $$(-1,1)$$ and a positive derivative in one direction, is a planar layer whenever $$0 < |p-2| < \varepsilon_0$$. The number $$\varepsilon_0$$ is independent of the solution, and the same conclusion holds in lower dimensions[reference:6]. The proof studies limits of vertical translates: a sequence of nonconstant nonplanar limits as $$p \to 2$$ would produce neighboring zero sheets with exponentially small pressure, and stress balance then yields a Toda system for the gaps. Stability of the original solution gives an inequality for this system, and a two-sheet test in the six horizontal dimensions rules out the positive interaction[reference:7].

* * *

### 3. Nonplanar monotone entire solutions of a p-Laplace Allen–Cahn equation for every $$p>1$$

**[Read the PDF](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/p_laplace_degiorgi_counterexample_all_p.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 9 (and $$N \ge 9$$ by constant extension) |
| **Range** | $$p > 1$$ |
| **Length** | Research manuscript |

For every fixed $$p>1$$, the manuscript constructs a smooth stable entire solution of $$-\Delta_p u = u(1-u^2)^{p-1}$$ in $$\mathbb{R}^9$$ with values in $$(-1,1)$$, strictly positive vertical derivative, and a nonplanar zero set[reference:8]. The vertical limits are the two wells locally uniformly in the horizontal variables, and the zero set is a smooth normal graph over a large dilation of the Bombieri–De Giorgi–Giusti minimal graph, with displacement decaying at horizontal infinity[reference:9]. Two weighted Jacobi estimates cancel the averaged cubic-curvature error and provide strict ordered core barriers. An exact phase identity reduces the core calculation to a smooth equation near a unit gradient, and asymmetric ambient tails extend the cores to monotone global barriers. A whole-space nonlinear resolvent produces an exact solution, and affine comparison with vertical translates proves positivity of the vertical derivative. Constant extension gives stable nonplanar solutions with the same monotonicity in every dimension $$N \ge 9$$[reference:10].

* * *

### 4. De Giorgi conjecture of p-Laplace with $$p>2$$ holds in dimension eight

**[Read the PDF](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/p_laplace_degiorgi_p_greater_than_two.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 7 as the core classification; $$N \le 8$$ as the final range |
| **Range** | $$p > 2$$ |
| **Length** | Research manuscript |

Fix $$p>2$$. The manuscript first proves that every scalar-stable entire weak solution of $$-\Delta_p u = u(1-u^2)^{p-1}$$ **in $$\mathbb{R}^7$$** with values in $$[-1,1]$$ is either a constant well $$\pm 1$$ or a planar transition $$\tanh(a_p(\omega \cdot x - t_0))$$, where $$a_p = [2(p-1)]^{-1/p}$$[reference:11]. An endpoint-profile theorem of Farina and Valdinoci then gives the same planar form for entire weak solutions $$u: \mathbb{R}^N \to (-1,1)$$ with **$$N \le 8$$** and $$\partial_{x_N} u > 0$$, with no energy-growth bound or directional limits assumed[reference:12]. Weighted Jacobi tests handle the degeneracy at critical gradients, sharp propagation of the phase discrepancy controls errors in normal tubes, and a mean-curvature estimate retains a negative curvature term. Penalized reach estimates and fourth-moment bounds exclude unbounded energy density, and the constants are uniform when $$p$$ ranges over a compact subinterval of $$(2,\infty)$$[reference:13].

* * *

### 5. Nonplanar entire minimizers for a p-Laplace phase-transition equation

**[Read the PDF](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/p_laplace_nonplanar_minimizers_all_p.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 8 (and $$N \ge 8$$ by constant extension) |
| **Range** | $$1 < p < \infty$$ |
| **Length** | Research manuscript |

For every fixed $$1<p<\infty$$, the manuscript constructs a bounded entire global minimizer of $$-\Delta_p u = u(1-u^2)^{p-1}$$ in $$\mathbb{R}^8$$ whose level sets are not all hyperplanes[reference:14]. The solution is invariant under $$O(4) \times O(4)$$, and its zero set outside a compact set is a smooth normal graph over the Simons cone with height $$O(|x|^{-2})$$[reference:15]. Constant extension gives nonplanar global minimizers in every dimension $$N \ge 8$$[reference:16]. The construction uses a positive forced Jacobi function on a Hardt–Simon leaf, an explicit phase correction through fourth order, and ordered strict barriers. A radial tail correction gives a nonzero gradient wherever a barrier is active, including in the singular range $$1<p<2$$. Unconstrained minimization on balls and a strict-contact argument then yield the entire minimizer. The manuscript explicitly states that **no assertion is made at $$p=1$$ or about strict monotonicity in an added coordinate**[reference:17].

* * *

## Citing a manuscript

Use the full manuscript title and the date printed in the PDF. Include the [repository URL](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace) and the commit hash or a commit-specific PDF link for the version consulted, so that the cited draft can be identified after revisions.

* * *

## Repository structure

| File | Description |
|---|---|
| [`Stable_DeGiorgi_N7.pdf`](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/Stable_DeGiorgi_N7.pdf) | Dimension 7, $$p>1$$, stable solutions (scanned PDF) |
| [`p_laplace_N8_near_two.pdf`](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/p_laplace_N8_near_two.pdf) | Dimension 8, $$p$$ near $$2$$ |
| [`p_laplace_degiorgi_counterexample_all_p.pdf`](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/p_laplace_degiorgi_counterexample_all_p.pdf) | Dimension 9, every $$p>1$$, nonplanar monotone solutions |
| [`p_laplace_degiorgi_p_greater_than_two.pdf`](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/p_laplace_degiorgi_p_greater_than_two.pdf) | Dimension 7 core, final range $$N \le 8$$, $$p>2$$, symmetry |
| [`p_laplace_nonplanar_minimizers_all_p.pdf`](https://github.com/mingfeng87/De-Giorgi-Conjecture-p-Laplace/blob/main/p_laplace_nonplanar_minimizers_all_p.pdf) | Dimension 8, every $$1<p<\infty$$, nonplanar minimizers |

* * *

## Keywords

p-Laplace equation; De Giorgi conjecture; phase transitions; stable solutions; entire weak solutions; one-dimensional symmetry; nonplanar minimizers; Toda system; weighted Jacobi fields; Hardt–Simon foliation; Simons cone; Bombieri–De Giorgi–Giusti graph.
