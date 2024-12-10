---
title: "Enabling Risk Management of Machine Learning Predictions for FPGA Routability"
collection: publications
permalink: /publication/RiskRouteMLCAD
excerpt: 'This paper studies the risks of inaccurate predictions of ML models in FPGA CAD algorithms.'
date: 2024-9-9
venue: 'International Symposium on Machine Learning for CAD'
paperurl: 'http://nikhilghanathe.github.io/files/RiskRouteMLCAD.pdf'
citation: #'Under Review' #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Machine Learning (ML) models sometimes make inaccurate predictions for the routability of field-programmable gate array (FPGA) circuit designs. This risks time wasted attempting to route an unroutable design or the premature termination of a routable design's compilation. While improving model accuracy is beneficial, we explore a complementary approach to mitigate the risk of inaccurate predictions by assessing the confidence of ML models. This approach could allow individuals to customize their own trade-off for the competing risks of wasted time and premature compilation termination. In this paper, we introduce a novel mixture of experts ML system for FPGA routability prediction and further quantify the confidence calibration of this system to determine its suitability as a risk management tool. We evaluate our prediction system for the purpose of enabling user risk management in FPGA routability prediction, comparing against a baseline inspired by prior work. Our evaluation finds our approach to achieve almost 2× the precision in risk trade-off between time wasted on unroutable designs and premature termination of routable designs.