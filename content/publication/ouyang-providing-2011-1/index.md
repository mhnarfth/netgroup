---
title: Providing NPR-Style Time-Shifted Streaming in P2P Systems
authors:
- Zhipeng Ouyang
- Lisong Xu
- Byrav Ramamurthy
date: '2011-07-01'
publishDate: '2024-07-21T02:26:11.762290Z'
publication_types:
- paper-conference
publication: '*2011 Proceedings of 20th International Conference on Computer Communications
  and Networks (ICCCN)*'
doi: 10.1109/ICCCN.2011.6006056
abstract: Digital video recorder (DVR) style and non-prerecording (NPR) style are
  two possible implementations for P2P-based time-shifted streaming, but existing
  P2P streaming solutions are not suitable to implement the NPR method. Since peers
  can view any arbitrary video segments which have been broadcasted, they might encounter
  severe video quality problems and the server bandwidth consumption can become high.
  In this paper, we focus on minimizing the server bandwidth consumption to maintain
  smooth streaming service in NPR-style P2P-based time-shifted streaming. To reduce
  the server cost, peers prefetch segments which are not required for their current
  viewing. Hence even if they are viewing different parts of the video, they can exchange
  segments with one another. However, segment prefetching competes for bandwidth with
  ordinary segment fetching, and it might bring negative impact. A good prefetching
  solution should not affect peers' viewing experience. We formulate the problem of
  finding a prefetching solution as an optimization problem, with the objective to
  minimize the server bandwidth consumption. Then we propose a heuristic algorithm
  by decomposing the global optimization problem into a set of smaller problems. Each
  peer runs this algorithm to determine which segments to prefetch and how to serve
  other peers. Simulation experiments demonstrate that our design provides P2P-based
  time-shifted streaming at low server bandwidth consumption.
tags:
- bandwidth
- optimization
- streaming media
- delay
- video streaming
- channel allocation
- prefetching
- servers
- digital video recorder
- DVR style
- nonprerecordeing style
- NPR style
- NPR-style time-shifted streaming
- optimization problem
- P2P system
- peer-to-peer computing
- segment prefetching
- server bandwidth consumption
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/6006056
---
