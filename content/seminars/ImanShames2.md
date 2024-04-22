---
title: "Iman Shames' Talk on Distributed Nonconvex Optimisation Via Modified ADMM" 
date: 2024-04-26T11:00:00+10:00
draft: false
---


__Title:__ Distributed Nonconvex Optimisation Via Modified ADMM

__Time, Date, Location__: 11:00, Friday, 26 April, 2024, Ian Ross Seminar Room

__Abstract:__ This talk addresses the problem of nonconvex nonsmooth decentralised optimisation in multi-agent networks with undirected connected communication graphs. We introduce an algorithmic framework designed for the distributed minimisation of the sum of a smooth (possibly nonconvex and non-separable) function and a convex (possibly nonsmooth and non-separable) regulariser. The proposed algorithm can be seen as a modified version of the ADMM algorithm where, at each step, an “inner loop” needs to be iterated for a number of iterations. The role of the inner loop is to aggregate and disseminate information across the network. We observe that a naive decentralised approach (one iteration of the inner loop) may not converge. We establish the asymptotic convergence of the proposed algorithm to the set of stationary points of the nonconvex problem where the number of iterations of the inner loop increases logarithmically with the step count of the ADMM algorithm. We present numerical results demonstrating the proposed method's performance.


