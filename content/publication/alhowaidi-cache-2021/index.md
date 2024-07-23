---
title: Cache management for large data transfers and multipath forwarding strategies
  in Named Data Networking
authors:
- Mohammad Alhowaidi
- Deepak Nadig
- Boyang Hu
- Byrav Ramamurthy
- Brian Bockelman
date: '2021-11-01'
publishDate: '2024-07-21T02:26:09.278088Z'
publication_types:
- article-journal
publication: '*Computer Networks*'
doi: 10.1016/j.comnet.2021.108437
abstract: Named Data Networking (NDN) is a promising approach to provide fast in-network
  access to compact muon solenoid (CMS) datasets. It proposes a content-centric rather
  than a host-centric approach to data retrieval. Data packets with unique and immutable
  names are retrieved from a content store (CS) using Interest packets. The current
  NDN architecture relies on forwarding strategies that are only dependent upon on-path
  caching. Such a design does not take advantage of the cached content available on
  the adjacent off-path routers in the network, thus reducing data transfer efficiency.
  In this work, we propose a software-defined, storage-aware routing mechanism that
  leverages NDN router cache-states, software defined networking (SDN) and multipath
  forwarding strategies to improve the efficiency of very large data transfers. First,
  we propose a novel distributed multipath (D-MP) forwarding strategy and enhancements
  to the NDN Interest forwarding pipeline. In addition, we develop a centralized SDN-enabled
  control for the multipath forwarding strategy (S-MP), which leverages the global
  knowledge of NDN network states that distributes Interests efficiently. We perform
  extensive evaluations of our proposed methods on an at-scale wide area network (WAN)
  testbed spanning six geographically separated sites. Our proposed solutions easily
  outperform the existing NDN forwarding strategies. The D-MP strategy results in
  performance gains ranging between 10.4x to 12.5x over the default NDN implementation
  without in-network caching, and 12.2x to 18.4x with in-network caching enabled.
  For S-MP strategy, we demonstrate a performance improvement of 10.6x to 12.6x, and
  12.9x to 18.5x, with in-network caching disabled and enabled, respectively. Further,
  we also present a comprehensive analysis of NDN cache management for large data
  transfers and propose a novel prefetching mechanism to improve data transfer performance.
  Due to the inherent capacity limitations of the NDN router caches, we use SDN to
  provide an intelligent and efficient solution for data distribution and routing
  across multiple NDN router caches. We demonstrate how software-defined control can
  be used to partition and distribute large CMS files based on NDN router cache-state
  knowledge. Further, SDN control will also configure the router forwarding strategy
  to retrieve CMS data from the network. Our proposed solution demonstrates that the
  CMS datasets can be retrieved 28%–38% faster from the NDN routers’ caches than existing
  NDN approaches. Lastly, we develop a prefetching mechanism to improve the transfer
  performance of files that are not available in the router’s cache.
tags:
- SDN
- Cache management
- Compact Muon Solenoid
- Forwarding strategy
- NDN
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1389128621003972
---
