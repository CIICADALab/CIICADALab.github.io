---
title: "Erik Weyer's Talk on State conditional filtering (11 November, 2022)"
date: 2022-09-28T11:42:30+10:00
draft: false
---

__Title:__ State conditional filtering

__Time, Date, Location__: 11:00, Friday 11 November, 2022, Brian Anderson Building Seminar Room

__Abstract:__ The Kalman Filter is a well-known method for estimating the state vector of a linear dynamical system. It computes on-line the optimal least mean square error estimate of the state given the observed outputs, and it also computes the covariance matrix of the state estimation error. Using the state estimate and the covariance matrix, a confidence ellipsoid for the true state can be constructed under the assumption that the noise in the system is Gaussian.

In many applications some values of the states are more important than others, e.g. values that represent collision or near-collision of two robots, unsafe operating conditions etc. Such events usually have low a priori probability to happen and the Kalman Filter fails to provide adequate estimates and confidence ellipsoids of such rare events. In this talk a state estimation algorithm which under a Gaussian assumption on the noise, delivers confidence ellipsoids which contain the true state, regardless of its value, with a given probability is presented. The results will first be introduced for the static case, and before extended to the dynamic case.

Joint work with Algo Care and Marco Campi, University of Brescia, Italy.

Ref: A. Care, M. Campi and E. Weyer. State Conditional Filtering. IEEE Transactions on Automatic Control. Vol 67, no 7, July 2022 pp. 3381 - 3395


__Bio:__ Erik Weyer is a Professor in the Department of Electrical and Electronic Engineering at the University of Melbourne, Australia. He received the Siv. Ing. degree in 1988 and the Ph.D. in 1993, both from the Norwegian Institute of Technology.  From 1994 to 1996 he was a Research Fellow at the University of Queensland, Australia, before he joined the University of Melbourne in  1997. He has held visiting positions at the University of Brescia, Italy, the Technical University of Vienna, Austria, and Politecnico di Milano, Italy. He is a past  Associate Editor of IEEE Transactions of Automatic Contro (2010-2012) and  Automatica (2015-2021). In 2014 he was awarded, jointly with colleagues at the University of Melbourne, the IEEE Control Systems Technology Award for the development and implementation of controls for irrigation channels and water management. His research interests are in the areas of system identification and control.
