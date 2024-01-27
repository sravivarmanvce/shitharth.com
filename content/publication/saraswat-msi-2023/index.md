---
title: 'MSI-A: An Energy Efficient Approximated Cache Coherence Protocol'
authors:
- Anant Saraswat
- Kumar Abhishek
- Hiteshwar Kumar Azad
- admin
date: '2023-01-01'
publishDate: '2024-01-23T11:26:30.340878Z'
publication_types:
- article-journal
publication: '*IEEE Access*'
doi: 10.1109/ACCESS.2023.3273219
abstract: Energy consumption has become an essential factor in designing modern computer
  system architecture. Because of physical limits, the termination of Moore’s law
  and Dennard’s scaling has forced the computer design community to investigate new
  approaches to meet the requirements for computing resources. Approximate computing
  has emerged as a promising method for reducing energy consumption while trading
  a controllable quality loss. This paper asserts that an approximated cache coherence
  protocol preserves overall energy for computation. We can approximate the cache
  coherence protocol by adding approximated cache lines to a certain level without
  hindering the output. This paper introduces an enhanced approximated version of
  the MSI (Modified Shared Invalid) cache coherence protocol MSI-A (Modified Shared
  Invalid-Approx). We have verified MSI-A and MSI by employing LTL specifications
  in the NuSMV model checker. To illustrate the benefits of MSI-A, we have added DTMC
  (Discrete-Time Markov Chain) with PCTL (Probabilistic Computational Tree Logic).
  Although the PCTL proves the theory of approximation, we have also simulated the
  MSI-A in the TEJAS hardware simulator on PARSEC 3.0 to investigate the energy gains
  and cycle gains of MSI-A in varied applications. The cache lines considered to be
  approx are between 10 and 30 percent. Each application benefited from approximation
  according to its nature, and VIPS has indicated a total energy gain of 30.18 percent.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10119163
---
