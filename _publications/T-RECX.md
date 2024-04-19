---
title: "T-RecX: Tiny-Resource Efficient Convolutional neural networks with early-eXit"
collection: publications
permalink: /publication/T-RECX
excerpt: 'This paper describes a early-exit network architecture optimized for tinyML models, and presents a novel resource-efficient method to mitigate overthinking in tiny neural networks. This work recieved the ACM Best paper award.'
date: 2023-05-11
venue: 'International Conference on Computing Frontiers (CF23) - <b>BEST PAPER AWARD</b> ' 
paperurl: 'http://nikhilghanathe.github.io/files/T-RECX.pdf'
citation: #'Nikhil P Ghanathe and Steve Wilton, Proceedings of the 20th ACM International Conference on Computing Frontiers, pp. 123–133, 2023'
---

Deploying Machine learning (ML) on milliwatt-scale edge devices (tinyML) is gaining popularity due to recent breakthroughs in ML and Internet of Things (IoT). Most tinyML research focuses on model compression techniques that trade accuracy (and model capacity) for compact models to fit into the KB-sized tiny-edge devices. In this paper, we show how such models can be enhanced by the addition of an early exit intermediate classifier. If the intermediate classifier exhibits sufficient confidence in its prediction, the network exits early thereby, resulting in considerable savings in time. Although early exit classifiers have been proposed in previous work, these previous proposals focus on large networks, making their techniques suboptimal/impractical for tinyML applications. Our technique is optimized specifically for tiny-CNN sized models. In addition, we present a method to alleviate the effect of network overthinking by leveraging the representations learned by the early exit. We evaluate T-RecX on three CNNs from the MLPerf tiny benchmark suite for image classification, keyword spotting and visual wake word detection tasks. Our results show that T-RecX 1) improves the accuracy of baseline network, 2) achieves 31.58% average reduction in FLOPS in exchange for one percent accuracy across all evaluated models. Furthermore, we show that our methods consistently outperform popular prior works on the tiny-CNNs we evaluate.