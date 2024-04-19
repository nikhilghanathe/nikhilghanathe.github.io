---
title: "Software and firmware co-development using high-level synthesis"
collection: publications
permalink: /publication/software-firmware
excerpt: "This paper presents a case study of using high-level synthesis tools to streamline the firmware development process of CMS Endcap Muon Level-1 Track finder (EMTF) at CERN's Large Hadron Collider."
date: 2016-09-30
venue: 'Topical Workshop on Electronics for Particle Physics (TWEPP), 2016'
paperurl: 'http://nikhilghanathe.github.io/files/software-firmware.pdf'
citation: #'Nikhil P Ghanathe and Steve Wilton, Proceedings of the 20th ACM International Conference on Computing Frontiers, pp. 123–133, 2023'
---

Accelerating [trigger](https://cds.cern.ch/record/433826/files/p318.pdf){:target="_blank"}{:rel="noopener noreferrer"} applications on FPGAs (using VHDL/Verilog) at the CMS experiment at CERN's Large Hadron Collider warrants consistency between each trigger firmware and its corresponding C++ model. This tedious and time consuming process of convergence is exacerbated during each upgrade study. High-level synthesis, with its promise of increased productivity and C++ design entry bridges this gap exceptionally well. This paper explores the "single source code" approach using Vivado-HLS tool for redeveloping the upgraded CMS Endcap Muon Level-1 Track finder (EMTF). Guidelines for tight latency control, optimal resource usage and compatibility with CMS software framework are outlined in this paper.
