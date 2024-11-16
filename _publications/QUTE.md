---
title: "QUTE: Quantifying Uncertainty in TinyML with Early-exit-assisted ensembles for model-monitoring"
collection: publications
permalink: /publication/QUTE
excerpt: 'This paper describes a resource-efficient method to practically quantify uncertainty for tinyML model-monitoring while meeting the strict tinyML constraints.'
date: 2024-04-19
venue: 'Under Review'
paperurl: 'http://nikhilghanathe.github.io/files/QUTE.pdf'
citation: #'Under Review' #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Uncertainty quantification (UQ) provides a resource-efficient solution for on-device monitoring of tinyML models deployed without access to true labels. However, existing UQ methods impose significant memory and compute demands, making them impractical for ultra-low-power, KB-sized TinyML devices. Prior work has attempted to reduce overhead by using early-exit ensembles to quantify uncertainty in a single forward pass, but these approaches still carry prohibitive costs. To address this, we propose QUTE, a novel resource-efficient early-exit-assisted ensemble architecture optimized for tinyML models. QUTE introduces additional output blocks at the final exit of the base network, distilling early-exit knowledge into these blocks to form a diverse yet lightweight ensemble. We show that QUTE delivers superior uncertainty quality on tiny models, achieving comparable performance on larger models with 59% smaller model sizes than the closest prior work. When deployed on a microcontroller, QUTE demonstrates a 31% reduction in latency on average. In addition, we show that QUTE excels at detecting accuracy-drop events, outperforming all prior works.