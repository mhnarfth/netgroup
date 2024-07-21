---
title: Enhancing the SDTMA-NDN architecture for transferring the scientific data software
  using named data networking
authors:
- Mohammad Alhowaidi
- Byrav Ramamurthy
- Brian Bockelman
- David Swanson
date: '2020-01-01'
publishDate: '2024-07-21T02:26:09.982987Z'
publication_types:
- article-journal
publication: '*Computer Networks*'
doi: 10.1016/j.comnet.2019.106954
abstract: 'Named Data Networking (NDN) is one of the promising future internet architectures,
  which focuses on the data rather than its location (IP/host-based system). NDN has
  several characteristics which facilitate addressing and routing the data: fail-over,
  in-network caching and load balancing. This makes it useful in areas such as managing
  scientific data across a distributed infrastructure. The Compact Muon Solenoid (CMS)
  experiment on the Large Hadron Collider (LHC) runs such an infrastructure and has
  a data access pattern amenable to Information-Centric Networking (ICN). In this
  paper, we propose SDTMA-NDN (Scientific Data Transfer Management Architecture using
  NDN) to distribute CMS’s software to worker-nodes and end-users. We provide several
  strategies to enhance the performance of NDN in transferring the scientific data.
  We build this on top of CERN Virtual Machine File System (CVMFS), a global, distributed
  filesystem designed to be used with cache-friendly workloads. CVMFS maintains its
  data by using content-addressable storage, which makes it suitable for NDN and a
  reasonable starting point for CMS. We examine the effect of in-network caching of
  NDN on the latency, how NDN provides transparent path selection to avoid high latency
  in the path, and how it balances several paths for retrieving the data. We compare
  SDTMA-NDN to the HTTP proxies used in the existing CVMFS-Content Distribution Network
  (CDN). Also, we propose two NDN forwarding strategies for retrieving the data; NDN
  Best-Path strategy (NDN-BP) and NDN Multi-path strategy (NDN-MP). SDTMA-NDN shows
  a better performance than the existing HTTP protocol in transferring the data. Further,
  it shows more resiliency and outperforms CVMFS-CDN under different network conditions.'
tags:
- CERN virtual machine file system (CVMFS)
- Named data networking
- Scientific data
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1389128619302087
---
