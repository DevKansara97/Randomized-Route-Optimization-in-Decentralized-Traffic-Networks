# 🚦 Randomized Route Optimization in Decentralized Traffic Networks

This project explores a probabilistic routing framework aimed at minimizing average travel time and alleviating congestion in decentralized traffic networks. Developed for the course **CSE400: Fundamentals of Probability in Computing** at Ahmedabad University.

## 📌 Overview

We implement a **Randomized A\*** algorithm that introduces controlled randomness in path selection using a **Boltzmann probability distribution**. The cost function combines actual travel costs with heuristically estimated distances (Euclidean, Manhattan, Diagonal).

## 📊 Key Features

- Probabilistic Path Selection using:  
  `P(P_i) = \frac{e^{-\beta f(P_i)}}{\sum_j e^{-\beta f(P_j)}}`
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

- Dev Kansara (AU2340222)  
- Param Shah (AU2340192)  
- Hir Gaglani (AU2340136)  
- Priscilla R (AU2340001)  
- Hir Vora (AU2340156)

## 📅 Submission Date
13/02/2025
