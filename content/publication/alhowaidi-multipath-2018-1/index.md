---
title: Multipath Forwarding Strategies and SDN Control for Named Data Networking
authors:
- Mohammad Alhowaidi
- Deepak Nadig
- Byrav Ramamurthy
- Brian Bockelman
- David Swanson
date: '2018-12-01'
publishDate: '2024-07-21T02:26:11.920390Z'
publication_types:
- paper-conference
publication: '*2018 IEEE International Conference on Advanced Networks and Telecommunications
  Systems (ANTS)*'
doi: 10.1109/ANTS.2018.8710068
abstract: Named Data Networking (NDN) proposes a contentcentric rather than a host-centric
  approach to data retrieval. Data packets with unique and immutable names are retrieved
  from a content store (CS) using Interest packets. The current NDN architecture relies
  on forwarding strategies that are dependent upon on-path caching and is therefore
  inefficient. This approach reduces data transfer efficiency by ignoring the cached
  content available on the adjacent off-path routers in the network. In this paper,
  we propose a novel distributed multipath (D-MP) forwarding strategy and enhancements
  to the NDN Interest forwarding pipeline. Furthermore, we develop a centralized SDNenabled
  control for the multipath forwarding strategy (S-MP) that distributes Interests
  efficiently by using the global knowledge of the NDN network states. We perform
  extensive evaluations of our proposed methods on an at-scale WAN testbed spanning
  six geographically separated sites. Our solutions outperform the existing NDN forwarding
  strategies by a significant margin. We show that the D-MP strategy results in performance
  gains ranging between 10.4x to 12.5x over the default NDN implementation without
  in-network caching, and gains of 12.2x to 18.4x with in-network caching. In addition,
  for the S-MP case, we demonstrate a performance improvement of 10.6x to 12.6x, and
  12.9x to 18.5x, for with- and without in-network caching respectively.
tags:
- internet
- telecommunication network routing
- routing
- Computer architecture
- data transfer
- named data networking
- software defined networking
- telecommunication control
- wide area networks
- Routing protocols
- D-MP strategy
- data retrieval
- in-network caching
- ip networks
- multipath forward strategy
- NDN architecture
- off-path routers
- on-path caching
- pipeline processing
- pipelines
- SDN control
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/8710068
---
