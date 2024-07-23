---
title: Towards simulating dynamic routing and wavelength assignment using GNPy and
  SIMON
authors:
- Boyang Hu
- Byrav Ramamurthy
date: '2021-12-01'
publishDate: '2024-07-21T02:26:10.482938Z'
publication_types:
- paper-conference
publication: '*2021 IEEE International Conference on Advanced Networks and Telecommunications
  Systems (ANTS)*'
doi: 10.1109/ANTS52808.2021.9936914
abstract: In this article, we enhanced the capability of SIMON (Simulator for Optical
  Networks) by considering the nonlinear effect of the optical network components
  and different industry network devices. This is achieved by using an optical route
  planning library called GNPy (Gaussian Noise model in python) as the calculation
  model within SIMON. SIMON is implemented in C++ and has mainly been used as an optical
  network learning tool for studying the performance of wavelength-routed optical
  networks. It measures the network blocking probability by taking into consideration
  the optical device characteristics. SIMON can capture the most significant impairments
  when estimating the Bit-Error Rate (BER) but does not consider fiber dispersion
  and non-linearities. These impairments can be significant when simulating a large-scale
  network. GNPy, on the other hand, considers those physical impairments and can give
  a more accurate signal-to-noise ratio (SNR) estimation validated by real-world measurements.
  By integrating GNPy with SIMON, we are able to set a minimum SNR threshold, which
  must be satisfied by any call set up in the network. The integration of SIMON and
  GNPy makes the resulting simulator not only suitable for academic learning but also
  valuable for real-world network planning, evaluation, and deployment of optical
  networks.
tags:
- Wavelength assignment
- telecommunication network routing
- telecommunication network management
- wavelength assignment
- optical fiber networks
- probability
- WDM
- routing
- telecommunication computing
- performance evaluation
- error statistics
- wavelength-routed optical networks
- wavelength measurement
- BER
- bit-error rate
- C++
- different industry network devices
- estimation
- gaussian noise
- Gaussian noise model in python
- Gaussian-noise (GN) model
- GNPy
- large-scale network
- network blocking probability
- optical device characteristics
- optical network components
- optical network learning tool
- Optical networks simulation
- optical route planning library
- optical variables measurement
- performance measurement
- real-world network planning
- signal-to-noise ratio estimation
- SIMON
- simulating dynamic routing
- simulator for optical networks
- SNR estimation
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/9936914
---
