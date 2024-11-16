---
title: "DEBUG-HD: Debugging TinyML models on-device using Hyper-Dimensional computing"
collection: publications
permalink: /publication/DebugHD
excerpt: 'This paper studies explores on-device debug of field-deployed TinyML models using Hyper-dimensional computing.'
date: 2024-11-16
venue: 'Machine Learning for Systems Workshop at NeurIPS'
paperurl: 'http://nikhilghanathe.github.io/files/DebugHD.pdf'
citation: #'Under Review' #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

TinyML models often operate in remote, dynamic environments without cloud connectivity, making them prone to failures. Ensuring reliability in such scenarios requires not only detecting model failures but also identifying their root causes. However, transient failures, privacy concerns, and the safety-critical nature of many applications-where systems cannot be interrupted for debugging-complicate the use of raw sensor data for offline analysis. We propose DEBUG-HD, a novel, resource-efficient on-device debugging approach optimized for KB-sized tinyML devices that utilizes hyper-dimensional computing (HDC). Our method introduces a new HDC encoding technique that leverages conventional neural networks, allowing DEBUG-HD to outperform prior binary HDC methods by 27% on average in detecting input corruptions across various image and audio datasets.