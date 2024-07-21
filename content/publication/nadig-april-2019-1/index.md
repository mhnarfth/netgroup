---
title: 'APRIL: An Application-Aware, Predictive and Intelligent Load Balancing Solution
  for Data-Intensive Science'
authors:
- Deepak Nadig
- Byrav Ramamurthy
- Brian Bockelman
- David Swanson
date: '2019-04-01'
publishDate: '2024-07-21T02:26:11.246179Z'
publication_types:
- paper-conference
publication: '*IEEE INFOCOM 2019 - IEEE Conference on Computer Communications*'
doi: 10.1109/INFOCOM.2019.8737537
abstract: In this paper, we propose an application-aware intelligent load balancing
  system for high-throughput, distributed computing, and data-intensive science workflows.
  We leverage emerging deep learning techniques for time-series modeling to develop
  an application-aware predictive analytics system for accurately forecasting GridFTP
  connection loads. Our solution integrates with a major U.S. CMS Tier-2 site; we
  use a real dataset representing 670 million GridFTP transfer connections measured
  over 18 months to drive our predictive analytics solution. First, we perform extensive
  analysis on this dataset and use the connection loads as an example to study the
  temporal dependencies between various user-roles and workflow memberships. We use
  the analysis to motivate the design of a gated recurrent unit (GRU) based deep recurrent
  neural network (RNN) for modeling long-term temporal dependencies and predicting
  connection loads. We develop a novel application-aware, predictive and intelligent
  load balancer, APRIL, that effectively integrates application metadata and load
  forecast information to maximize server utilization. We conduct extensive experiments
  to evaluate the performance of our deep RNN predictive analytics system and compare
  it with other approaches such as ARIMA and multi-layer perceptron (MLP) predictors.
  The results show that our forecasting model, depending on the user-role, performs
  between 5.88%-92.6% better than the alternatives. We also demonstrate the effectiveness
  of APRIL by comparing it with the load balancing capabilities of an existing production
  Linux Virtual Server (LVS) cluster. Our approach improves server utilization, on
  an average, between 0.5 to 11 times, when compared with its LVS counterpart.
tags:
- resource allocation
- data analysis
- grid computing
- deep learning
- recurrent neural nets
- application metadara
- application-aware
- application-aware intelligent load balancing system
- application-aware predictive analytics system
- big data
- connection load prediction
- correlation
- data-intensive science workflows
- dataset
- deeo recurrent neural network
- deep learning techniques
- deep RNN predictive analytics system
- electronic data interchange
- forecasting model
- gated recurrent unit
- GridFTP connection loads
- GridFTP transfer connections
- high energy physics instrumentation computing
- intelligent load balancer
- intelligent load balancing solution
- learning (artificial intelligence)
- Linux
- Linux virtual server cluster
- load forecast information
- load management
- load modeling
- long-term temporal dependencies
- LVS cluster
- meta data
- multilayer perceptions
- predictive
- predictive analytics solution
- predictive models
- servers
- time 18.0 month
- time series
- time-series modeling
- US CMS Tier-2 site
- workflow memberships
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/8737537
---
