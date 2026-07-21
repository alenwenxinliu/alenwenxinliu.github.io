---
layout: home
title: Wenxin Liu
permalink: /
---

<style>
.profile {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 220px;
  gap: 2rem;
  align-items: center;
  margin: 1.5rem 0 2rem;
}

.profile img {
  width: 220px;
  height: 282px;
  object-fit: cover;
  border-radius: 18px;
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.18);
}

.profile .tagline {
  font-size: 1.15rem;
  line-height: 1.65;
}

.links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1rem;
}

.links a {
  display: inline-block;
  padding: 0.45rem 0.8rem;
  border-radius: 999px;
  background: #f2f5f8;
  text-decoration: none;
}

@media (max-width: 700px) {
  .profile {
    grid-template-columns: 1fr;
  }

  .profile img {
    width: 180px;
    height: 231px;
  }
}
</style>

# Wenxin Liu

<div class="profile">
  <div>
    <p class="tagline">
      Incoming PhD student in Applied Mathematics at the University of Warwick, with an MSc in Applied Mathematics
      (Scientific Computing &amp; Machine Learning) from Imperial College London. My work sits at the intersection of
      computational optimal transport, numerical PDEs, sparse linear algebra, and scientific machine learning.
    </p>
    <div class="links">
      <a href="/CV.pdf">Download CV</a>
      <a href="mailto:alenwenxinliu01@gmail.com">Email</a>
      <a href="https://github.com/alenwenxinliu">GitHub</a>
    </div>
  </div>
  <img src="/photo.jpg" alt="Portrait of Wenxin Liu">
</div>

---

## About Me

I am an applied mathematician focused on **scientific computing, numerical optimization, and machine-learning-assisted solvers**.
My recent work combines mathematical modeling with efficient algorithms for large-scale computational problems.

Current research interests include:

- Computational optimal transport and Schrödinger bridge problems
- PDE-constrained optimization and trajectory planning under uncertainty
- Large-scale sparse linear algebra and iterative solver acceleration
- Finite element methods for elliptic, Stokes, and transport-type PDEs
- Graph neural networks for scientific computing workflows

---

## Education

- **University of Warwick** — PhD in Applied Mathematics, incoming, Sep. 2026–Sep. 2030
- **Imperial College London** — MSc in Applied Mathematics, Scientific Computing & Machine Learning, First Class Distinction, 2024–2025

---

## Research Highlights

### Optimal Transport & Schrödinger Bridges

- Co-authored *A PDE-constrained Optimization Approach to Optimal Trajectory Planning under Uncertainty via Reflected Schrödinger Bridges*, accepted by **European Control Conference 2026**.
- Co-authored *Computational Methods for Generalized Schrödinger Bridge Problems*, accepted by **MTNS 2026**.
- Implemented Douglas–Rachford splitting, primal-dual proximal methods, finite element solvers, nonlinear prior drift models, and reflective boundary conditions in 2D/3D settings.
- Preprint: <http://arxiv.org/abs/2511.14355>

### Machine Learning for Sparse Linear Algebra

- Developed a hybrid **GNN–MLP framework** for intelligent solver and preconditioner selection, achieving more than **3.75× acceleration** on large sparse linear systems.
- Built machine-learning-based optimization tools for **Algebraic Multigrid (AMG)** parameter tuning, improving robustness and convergence efficiency.
- Designed a GNN-based initial-guess prediction framework for iterative linear solvers, reducing solution time by **1.79× on average** and up to **19.51×** on challenging pressure Poisson systems.

### Numerical PDEs & Finite Elements

- Implemented object-oriented finite element solvers in Python for Helmholtz, Poisson, and Stokes equations with sparse matrix assembly.
- Built numerical methods for nonlinear ODEs, nonlinear heat equations, wave equations, AMR-enhanced elliptic PDEs, and IMEX wave-heat systems.
- Designed a position-dependent Perfectly Matched Layer that reduced boundary reflections by **85%** in wave-equation experiments.

---

## Projects & Theses

- **Postgraduate Thesis:** *Optimal Transport* — [Download PDF](/PG_thesis.pdf)
- **Undergraduate Thesis:** *Numerical Theory and Methods for Optimization: Primal-Dual and Interior Point Methods* — [Download PDF](/UG_thesis.pdf)
- **Computational Linear Algebra:** QR solvers, regularized least squares, Wilkinson-shift QR eigenvalue methods, and GMRES with Jacobi/Gauss-Seidel preconditioning.
- **Data Science:** Random forests, Huberised SVMs, transfer learning, U-Net regression in PyTorch, and spectral graph analysis.

---

## Technical Expertise

**Scientific Computing:** finite element methods, multigrid and Krylov solvers, Fourier stability analysis, IMEX schemes, sparse matrix assembly, high-performance computing

**Machine Learning:** graph neural networks, CNN feature extraction for sparse matrices, U-Net models, transfer learning, PyTorch

**Programming:** Python, MATLAB, C++, R, Java, Linux, NumPy, SciPy, Pandas, PyTorch

---

## CV & Contact

- [Download my CV](/CV.pdf)
- Email: [alenwenxinliu01@gmail.com](mailto:alenwenxinliu01@gmail.com)
- GitHub: <https://github.com/alenwenxinliu>
