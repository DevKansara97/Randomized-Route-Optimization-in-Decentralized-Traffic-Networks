# 🚦 Randomized Route Optimization in Decentralized Traffic Networks

This project explores a probabilistic routing framework aimed at minimizing average travel time and alleviating congestion in decentralized traffic networks. Developed for the course **CSE400: Fundamentals of Probability in Computing** under the guidance of Prof. Dhaval Patel, Ahmedabad University.

## 📌 Overview

We implement a **Randomized A\*** algorithm that introduces controlled randomness in path selection using a **Boltzmann probability distribution**. The cost function combines actual travel costs with heuristically estimated distances (Euclidean, Manhattan, Diagonal).

## 📊 Key Features

- Probabilistic Path Selection using:  
  We use a Boltzmann-like probability mass function (PMF) to assign probabilities to paths:

    ![PMF Equation](https://latex.codecogs.com/png.image?\dpi{120}P(P_i)=\frac{e^{-\beta%20f(P_i)}}{\sum_j%20e^{-\beta%20f(P_j)}})

  Here, `f(Pᵢ)` is the cost of path `Pᵢ`, and `β` controls the influence of the heuristic.

- Distance heuristics:  
  - Euclidean  
  - Manhattan  
  - Diagonal  
- Algorithms used:  
  - Dijkstra’s (Baseline)  
  - Standard A*  
  - Randomized A*

## 📚 Reference

Nguyen, H.T., Wiering, M.A., & van den Berg, J. (2015).  
*A randomized path routing algorithm for decentralized route allocation in transportation networks*.  
[ACM SIGSPATIAL CTScience 2015](https://dl.acm.org/doi/10.1145/2834882.2834886)

## 👥 Team

- Dev Kansara (AU2340222) - Mathematical Modelling
- Param Shah (AU2340192)  - Coding
- Hir Gaglani (AU2340136) - Inferences
- Priscilla R (AU2340001) - Randomized Algorithm 
- Hir Vora (AU2340156)    - Derivation of Bounds

## 📅 Submission Date
13/02/2025
