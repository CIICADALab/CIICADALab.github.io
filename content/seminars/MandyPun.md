---
title: "Yuen-Man (Mandy) Pun's Talk on Error Bound for Target Tracking Based on Time-of-Arrival Measurements"
date: 2022-10-28T11:00:00+10:00
draft: false
---


__Title:__  Error Bound for Target Tracking Based on Time-of-Arrival Measurements

__Time, Date, Location__: 11:00, Friday, 28 October, 2022, Brian Anderson Building Seminar Room

__Abstract:__ Target tracking is a key enabling technology in many applications of multi-agent systems and wireless sensor networks, such as motion planning and surveillance. While Kalman filtering technique has achieved a great success in tracking a moving target over the past few decades, it requires some model assumption on the target dynamics and noise statistics. In this talk, we consider a time-varying optimization approach to the target tracking problem using noisy time-of-arrival (TOA) measurements, which imposes only minimal assumptions on the target trajectory and/or noise distribution. Specifically, we formulate the problem as a sequence of TOA-based source localization problem and apply online gradient descent (OGD) to generate sequential updates of the target. To analyze the tracking performance of OGD, we first revisit the classic least-squares formulation of the (static) TOA-based source localization problem. Under standard assumptions on the TOA measurement model, we establish a bound on the distance between an optimal solution to the least-squares formulation and the true target position. Using this bound, we show that the loss function in the formulation, albeit non-convex in general, is locally strongly convex at its global minima. To the best of our knowledge, these results are new and can be of independent interest. By combining them with existing techniques from online strongly convex optimization, we then establish the first non-trivial bound on the cumulative target tracking error of OGD. Our numerical results corroborate the theoretical findings and show that OGD can effectively track the target at different noise levels.

__Biography:__ Yuen-Man Pun is currently a postdoctoral fellow with CIICADA Lab, School of Engineering at Australian National University. Prior to that, she received a PhD degree in Systems Engineering and Engineering Management (SEEM) in 2022, an MPhil degree in SEEM in 2018 and a BSc degree in Mathematics in 2016, all from the Chinese University of Hong Kong. Her research focuses on algorithmic design and analysis and its applications in data science and signal processing.
