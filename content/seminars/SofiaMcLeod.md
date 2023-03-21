---
title: "Sofia McLeod's Talk on Globally Optimal Event-Based Divergence Estimation for Ventral Landing"
date: 2023-03-23T14:00:00+10:00
draft: false
---

__Title:__  Globally Optimal Event-Based Divergence Estimation for Ventral Landing



__Time, Date, Location__: 14:00, Thursday, 23 March, 2023, Brian Anderson Building Seminar Room

__Abstract:__   Event sensing is a major component in bio-inspired flight guidance and control systems. We explore the usage of event cameras for predicting time-to-contact (TTC) with the surface during ventral landing. This is achieved by estimating divergence (inverse TTC), which is the rate of radial optic flow, from the event stream generated during landing. Our core contributions are a novel contrast maximisation formulation for event-based divergence estimation, and a branch-and-bound algorithm to exactly maximise contrast and find the optimal divergence value. GPU acceleration is conducted to speed up the global algorithm. Another contribution is a new dataset containing real event streams from ventral landing that was employed to test and benchmark our method. Owing to global optimisation, our algorithm is much more capable at recovering the true divergence, compared to other heuristic divergence estimators or event-based optic flow methods. With GPU acceleration, our method also achieves competitive runtimes.

The paper was published at ECCV’s AI for Space Workshop.




