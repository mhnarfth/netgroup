---
title: Using OpenFlow to provide cut-through switching in MobilityFirst
authors:
- Adrian Lara
- Byrav Ramamurthy
- Kiran Nagaraja
- Aravind Krishnamoorthy
- Dipankar Raychaudhuri
date: '2014-10-01'
publishDate: '2024-07-21T02:26:12.527102Z'
publication_types:
- article-journal
publication: '*Photonic Network Communications*'
doi: 10.1007/s11107-014-0461-3
abstract: Mobile devices are expected to become the Internet’s predominant technology.
  Current protocols such as TCP/IP were not originally designed with mobility as a
  key consideration, and therefore underperform under challenging mobile and wireless
  conditions. MobilityFirst, a clean slate architecture proposal, embraces several
  key concepts centered around secure identifiers that inherently support mobility
  and trustworthiness as key requirements of the network architecture. This includes
  a hop-by-hop segmented data transport based on a globally unique identifier. This
  allows late and dynamic rebinding of end-point addresses to support mobility. While
  this provides critical gains in wireless segments, some overheads are incurred even
  in stable segments such as in the core. Bypassing routing-layer decisions in these
  cases, with lower layer cut-through forwarding, can improve said gains. In this
  work, we introduce a general bypass capability within the MobilityFirst architecture
  that provides better performance and enables both individual and aggregate flow-level
  traffic control. Furthermore, we present an OpenFlow-based proof-of-concept implementation
  of the bypass function using layer 2 VLAN tagging. We run experiments on the ORBIT
  and Global Environment for Network Innovations (GENI) testbeds to evaluate the performance
  and scalability of the solution. By implementing the bypass functionality, we are
  able to significantly reduce the number of messages processed by the controller
  as well as the number of flow rules that need to be pushed into the switches.
tags:
- MobilityFirst
- OpenFlow
- FIA
- Software-defined networks
- VLAN tag
links:
- name: URL
  url: https://doi.org/10.1007/s11107-014-0461-3
---
