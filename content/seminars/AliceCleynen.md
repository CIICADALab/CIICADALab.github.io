---
title: "Alice Cleynen's Talk on Sequential medical treatment optimization using hidden Semi-Markov Processes"
date: 2023-06-23T11:00:00+10:00
draft: false
---


__Title:__ Sequential medical treatment optimization using hidden Semi-Markov Processes


__Time, Date, Location__: 11:00, Friday, 23 June, 2023, Brian Anderson Building Seminar Room

__Abstract:__ I am interested in monitoring patients in remission from cancer, the 
goal being to detect their relapse as quickly as possible, as well as 
the type of relapse, in order to give them the appropriate treatment as 
efficiently as possible. To this effect, we study the level of cancerous 
cells in the blood, a continuous process measured with noise at discrete 
intervals. This process is modelled by a piecewise deterministic Markov 
process (PDMP). Several decisions must be made based on these incomplete 
and noisy observations.
In the work presented here, I will seek to control the process, by 
authorising treatments that influence the level of cancer cells, and I 
will also want to determine the optimal dates for the next visits. This 
work, carried out with Benoîte de Saporta and Régis Sabaddin, is 
motivated by real data on multiple myeloma.

No pre-requisite on PDMPs is required, I will spend some time on the 
mathematical modelisation choice and the technical difficulties in 
solving our optimisation framework, but I will hide the ugly computations.
I will then describe a possible resolution strategies,  purely based on 
simulations, a promising approach that can scale up to more complex 
problems.


