---
title: 'Towards Measuring Quality of Service in Untrusted Multi-Vendor Service Function
  Chains: Balancing Security and Resource Consumption'
authors:
- Prasanna Karthik Vairam
- Gargi Mitra
- Vignesh Manoharan
- Chester Rebeiro
- Byrav Ramamurthy
- ' Kamakoti'
date: '2019-04-01'
publishDate: '2024-07-21T02:26:12.420239Z'
publication_types:
- paper-conference
publication: '*IEEE INFOCOM 2019 - IEEE Conference on Computer Communications*'
doi: 10.1109/INFOCOM.2019.8737487
abstract: The IT infrastructure of large organizations consists of devices and software
  services purchased from multiple vendors. The problem of measuring the quality of
  service (QoS) of each of these vendor devices (and services) is challenging since
  the vendors may tamper with the measurements for monetary benefits or saving debugging
  efforts. Existing solutions for QoS measurement in trusted environments cannot be
  extended for this problem since the vendors can easily circumvent them. Solutions
  borrowed from other areas such as client-server QoS measurement do not help either
  since they incur unreasonable storage and network overheads, or require extensive
  modifications to the packet headers. In this paper, we propose the Measuring Tape
  scheme, comprised of (1) a novel data structure called evidence Bloom filter (e-BF)
  that can be deployed at the vendor devices (and services), and (2) unique querying
  techniques, which can be used by the administrator to query the e-BF to measure
  QoS. While e-BF uses storage and computational resources judiciously, the querying
  techniques ensure resilience to adversarial behavior. We evaluate our solution based
  on a few real-world and synthetic traces and with different adversaries. Our results
  highlight the trade-off between resources (i.e., storage and computation) and the
  accuracy of QoS predictions, as well as its implications on security. We also present
  an analytical model of e-BF that establishes the relationship between storage, prediction
  accuracy, and security. Further, we present security arguments to illustrate how
  our solution thwarts adversarial attempts to tamper QoS.
tags:
- quality of service
- reliability
- receivers
- client-server systems
- software
- computer network security
- security
- quality of service measurement
- client-server QoS measurement
- data structure
- data structures
- debugging
- e-BF
- evidence Bloom filter
- measuring tape scheme
- organizations
- QoS predictions
- querying techniques
- resource consumption
- silicon
- software services
- untrusted multivendor service function chains
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/8737487
---
