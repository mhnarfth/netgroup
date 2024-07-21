---
title: Continuous and Parallel Optimization of Dynamic Bandwidth Scheduling in WDM
  Networks
authors:
- Pragatheeswaran Angu
- Byrav Ramamurthy
date: '2010-12-01'
publishDate: '2024-07-21T02:26:09.200564Z'
publication_types:
- paper-conference
publication: '*2010 IEEE Global Telecommunications Conference GLOBECOM 2010*'
doi: 10.1109/GLOCOM.2010.5683580
abstract: Many scientific and Grid applications require high-speed circuits of guaranteed
  bandwidth for scheduled transfers. Offline optimization of dynamic scheduled bandwidth
  demands is an efficient way of finding the near-optimal solution to the bandwidth
  scheduling problem. In this paper, we propose a continuous and parallel optimization
  method to address the dynamic and deterministic bandwidth scheduling problem in
  next generation wavelength-division multiplexing (WDM) networks. In this method
  a greedy algorithm and genetic algorithm are run in parallel in separate threads
  and both of them take the Dynamic Scheduled Bandwidth Demand (D-SBD) as their input.
  The user gets his response only from the greedy algorithm and hence he will get
  a deterministic answer in a short amount of time. The genetic algorithm takes as
  one of its inputs the output of the greedy algorithm and does the optimization of
  the D-SBDs with minimizing blocking probability as its fitness function. The greedy
  algorithm copies the optimized reservation database of the genetic algorithm at
  regular intervals. The user submitting a D-SBD request is unaware of the optimization
  done by the genetic algorithm. This method is evaluated using both trace-driven
  simulation of real network traffic from the DOE ESnet network and stochastic traffic
  in ESnet network topology and a 24 node network topology. We also compare our approach
  with an earlier proposed method called re-optimization at blocking. Adding the genetic
  algorithm improves the performance of the network (in terms of blocking probability)
  compared to using only the greedy approach or the re-optimization at blocking method.
tags:
- bandwidth
- telecommunication traffic
- Wavelength division multiplexing
- WDM networks
- probability
- telecommunication network topology
- dynamic scheduling
- greedy algorithms
- optimization
- 24 node network topology
- bioinformatics
- blocking probability minimization
- continuous optimization
- D-SBD
- databases
- deterministic algorithms
- deterministic bandwidth scheduling
- DOE ESnet network
- dynamic scheduled bandwidth demand
- ESnet network topology
- genetic algorithms
- genomics
- high-speed circuit
- minimization
- next generation networks
- next generation wavelength-division multiplexing networks
- offline optimization
- parallel optimization
- real network traffic
- stochastic processes
- stochastic traffic
- trace-driven simulation
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/5683580/keywords
---