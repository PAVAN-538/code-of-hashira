# Secret Constant Recovery using Lagrange Interpolation

This repository contains my solution to a **technical hiring assignment**.  
The task was to determine the **constant term** (the hidden secret) of a polynomial using a set of given points.  
Each point was provided in different number bases, and only the first **k** points were required to recover the secret.

---

## 🧠 Problem Summary

We are given:
- `n` → total points available  
- `k` → minimum points required to reconstruct the polynomial  
- For each point:  
  - `x` = point index  
  - `y` = value encoded in a specific base  

The goal is to:
1. Convert all values to decimal.
2. Take only the first `k` points.
3. Apply **Lagrange Interpolation** to reconstruct the polynomial.
4. Extract the **constant term**, which is the hidden secret.

---
