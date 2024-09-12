# Geometric Approach to Factor Analysis

## What is Factor Analysis?

Factor Analysis seeks to understand the underlying relationships between observed variables by grouping them into latent factors based on their correlations. While it is a widely recognized and practical tool, Factor Analysis often lacks a rigorous formalism and a clear geometric interpretation.

## Why a Geometric Approach?

Studying factors is equivalent to studying frames. Given the common assumption of orthogonality among factors, a natural way to analyze them is to view these frames as elements of the Stiefel manifold (the set of orthogonal $k$-frames in $\mathbb{R}^d$).

## How Do These Concepts Connect?

The connection can be understood through the following optimization problem:

$$
\min_{U \in \text{St}(d,k)} W_2(\mu, P_U \sharp\mu)
$$

where $P_U$ is the projection of the measure $\mu$ onto the frame $U$ (note that the projection is onto the frame, not the subspace generated by the frame).

## Objective

This project aims to visually illustrate how this approximation works. 

---

