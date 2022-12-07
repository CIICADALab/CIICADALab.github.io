---
title: "Pieter van Goor's Talk on Constructive Equivariant Observer Design for Inertial Velocity-Aided Attitude and Matthew Hampsey's Talk on Exploiting Symmetries for Trajectory Tracking Control"
date: 2022-12-29T11:00:00+10:00
draft: false
---

We have a double-bill.


__Time, Date, Location__: 11:00, Friday, 9 December, 2022, Brian Anderson Building Seminar Room

The details are given below.

__Title:__ Constructive Equivariant Observer Design for Inertial Velocity-Aided Attitude by Pieter van Goor

__Abstract:__ Inertial Velocity-Aided Attitude (VAA), the estimation of the velocity and attitude of a vehicle using gyroscope, accelerometer, and inertial-frame velocity (e.g. GPS velocity) measurements,  is an important problem in the control of Remotely Piloted Aerial Systems (RPAS). Existing solutions provide limited stability guarantees, relying on local linearisation, high gain design, or assuming specific trajectories such as constant acceleration of the vehicle. In this presentation, I discuss a novel non-linear observer for inertial VAA with almost globally asymptotically and locally exponentially stable error dynamics. The approach exploits Lie group symmetries of the system dynamics to construct a globally valid correction term. To the authors' knowledge, this construction is the first observer to provide almost global convergence for the inertial VAA problem. The observer performance is verified in simulation, where it is shown that the estimation error converges to zero even with an extremely poor initial condition.


__Title:__  Exploiting Symmetries for Trajectory Tracking Control (with Application to Quadrotors) by Matthew Hampsey



__Abstract:__  High performance trajectory tracking control of quadrotor vehicles is an important challenge in aerial robotics. Symmetry is a fundamental property of physical systems and offers the potential to provide a tool to design high-performance control algorithms. We propose a design methodology that takes any given symmetry, linearises the associated error in a single set of coordinates, and uses LQR design to obtain a high performance control; an approach we term Equivariant Regulator design. We show that quadrotor vehicles admit several different symmetries: the direct product symmetry, the extended pose symmetry and the pose and velocity symmetry, and show that each symmetry can be used to define a global error. We compare the linearised systems via simulation and find that the extended pose and pose and velocity symmetries outperform the direct product symmetry in the presence of large disturbances. This suggests that choices of equivariant and group affine symmetries have improved linearisation error.
