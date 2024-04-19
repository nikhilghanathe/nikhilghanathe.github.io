---
title: "MAFIA: Machine Learning Acceleration on FPGAs for IoT Applications"
collection: publications
permalink: /publication/MAFIA
excerpt: 'This paper describes a novel compilation tool that enables efficient ML inference on small form-factor FPGAs for IoT applications.'
date: 2021-09-03
venue: 'International Conference on Field-Programmable Logic and Applications (FPL)'
paperurl: 'http://nikhilghanathe.github.io/files/MAFIA.pdf'
citation: #'Nikhil P Ghanathe and Steve Wilton, Proceedings of the 20th ACM International Conference on Computing Frontiers, pp. 123–133, 2023'
---

Recent breakthroughs in ML have produced new classes of models that allow ML inference to run directly on milliwatt-powered IoT devices. On one hand, existing ML-toFPGA compilers are designed for deep neural-networks on large FPGAs. On the other hand, general-purpose HLS tools fail to exploit properties specific to ML inference, thereby resulting in suboptimal performance. We propose MAFIA, a tool to compile ML inference on small form-factor FPGAs for IoT applications. MAFIA provides native support for linear algebra operations and can express a variety of ML algorithms, including state-of-the-art models. We show that MAFIA-generated programs outperform best-performing variant of a commercial HLS compiler by 2.5x on average