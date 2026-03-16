# Numerical Optimization & Root-Finding Algorithms
**Python · NumPy · SciPy · Scientific Computing · University of Toronto**

## Overview
Implementation and analysis of core numerical methods for root-finding, 
optimization, and constrained problems — validated against NumPy/SciPy 
library routines.

## Methods Implemented

| Notebook | Method | Category |
|----------|--------|----------|
| `01_root_finding` | Bisection, Newton's, Secant | Root-Finding |
| `02_fixed_point_iteration` | Fixed-Point Iteration, Convergence Analysis | Root-Finding |
| `03_optimization` | Golden Section, Newton's, Parabolic Interpolation | Optimization |
| `04_linear_programming` | Feasible Region, Vertex Evaluation | Linear Programming |
| `05_lagrange_multipliers` | Lagrange Multipliers, Hessian, SLSQP | Constrained Optimization |

## Key Results
- Bisection, Newton's, and Secant methods validated against SciPy `fsolve`
- Convergence rates confirmed for fixed-point iteration schemes
- Optimization minima matched SciPy `minimize_scalar` results
- Lagrange multiplier solution matched SciPy `minimize` (SLSQP) results

## Tools & Technologies
- **Language:** Python 3.9
- **Libraries:** NumPy, SciPy, Matplotlib
- **Methods:** Root-Finding, Fixed-Point Iteration, Gradient-Based 
  Optimization, Linear Programming, Constrained Optimization

## Academic Context
Completed as part of **CSC338 — Numerical Methods**, University of Toronto, 
Winter 2025. All implementations are original work.
