---
title: Cache Management for Large Data Transfers in Named Data Networking using SDN
authors:
- Mohammad Alhowaidi
- Deepak Nadig
- Byrav Ramamurthy
date: '2019-12-01'
publishDate: '2024-07-21T02:26:11.221512Z'
publication_types:
- paper-conference
publication: '*2019 IEEE International Conference on Advanced Networks and Telecommunications
  Systems (ANTS)*'
doi: 10.1109/ANTS47819.2019.9118137
abstract: The Compact Muon Solenoid (CMS) on the Large Hadron Collider (LHC) manage
  high volumes of data that currently exceeds 100PB across different sites. An important
  challenge of delivering data to experimenters in the CMS workflow is the data volume.
  An experiment data file has an average size of 2 Gigabytes, with file sizes ranging
  between 100 Megabytes and 20 Gigabytes. Also, a complete dataset comprises of multiple
  files, with the dataset files ranging from 2 Terabytes and 100 Terabytes in size.
  Providing fast access to datasets is an important enabler for data-intensive science
  research. In our work, we demonstrate a Information-Centric Networking (ICN) approach
  to providing fast in-network access to CMS datasets. To that end, we must first
  address the problem of how to store large CMS files in network caches closer to
  the end-users. We propose a software-defined, storage-aware routing mechanism using
  named data networking (NDN) to achieve this goal. Due to the inherent capacity limitations
  of the NDN router caches, we use software defined networking (SDN) to provide an
  intelligent and efficient solution for data distribution and routing across multiple
  NDN router caches. We demonstrate how software-defined control can be used for partitioning
  and distributing large CMS files based on NDN router cache-state knowledge. Further,
  SDN control will also configure the router forwarding strategy to retrieve CMS data
  from the network. Using our proposed architecture, we show that CMS dataset can
  be retrieved 28%–38% faster from the NDN routers caches compared to existing approaches.
  Lastly, we develop a prefetching mechanism to improve the transfer performance of
  files not available in the router's cache.
tags:
- Routing
- telecommunication network routing
- SDN
- cache management
- cache storage
- CMS workflow
- compact Muon Solenoid
- Computer architecture
- data transfer
- data transfers
- data-intensive science research
- distance measurement
- in-network access
- information-centric networking
- Internet
- large hadron collider
- named data networking
- NDN router
- NDN router cache-state knowledge
- prefetching
- prefetching mechanism
- software defined networking
- software-defined control
- storage management
- systems architecture
- telecommunication control
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/9118137
---
