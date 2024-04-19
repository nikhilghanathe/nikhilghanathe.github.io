---
title: "Compiling KB-sized machine learning models to tiny IoT devices"
collection: publications
permalink: /publication/Seedot
excerpt: 'This paper presents SeeDot, a domain-specific language/compiler for efficiently translating ML inference into fixed-point code for execution on resource-constrained microcontrollers and FPGAs.'
date: 2019-06-26
venue: 'ACM SIGPLAN Conference on Programming Language Design and Implementation (PLDI)'
paperurl: 'http://nikhilghanathe.github.io/files/Seedot.pdf'
citation: #'Nikhil P Ghanathe and Steve Wilton, Proceedings of the 20th ACM International Conference on Computing Frontiers, pp. 123–133, 2023'
---

Recent advances in machine learning (ML) have produced KiloByte-size models that can directly run on constrained IoT devices. This approach avoids expensive communication between IoT devices and the cloud, thereby enabling energy-efficient real-time analytics. However, ML models are expressed typically in floating-point, and IoT hardware typically does not support floating-point. Therefore, running these models on IoT devices requires simulating IEEE-754 floating-point using software, which is very inefficient.

We present SeeDot, a domain-specific language to express ML inference algorithms and a compiler that compiles SeeDot programs to fixed-point code that can efficiently run on constrained IoT devices. We propose 1) a novel compilation strategy that reduces the search space for some key parameters used in the fixed-point code, and 2) new efficient implementations of expensive operations. SeeDot compiles state-of-the-art KB-sized models to various microcontrollers and low-end FPGAs. We show that SeeDot outperforms 1) software emulation of floating-point (Arduino), 2) high-bitwidth fixed-point (MATLAB), 3) post-training quantization (TensorFlow-Lite), and 4) floating- and fixed-point FPGA implementations generated using high-level synthesis tools.