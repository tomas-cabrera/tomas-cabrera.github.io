---
title: "A GPU-Accelerated Transient Detection Pipeline for DECam Time-Domain Surveys"
collection: publications
category: Publications
tags: article lead
permalink: /publications/2026-06-19-GW-MMADS-pipeline
excerpt: "Hu, Lei; <b>Cabrera, Tomás</b>; Palmese, Antonella; Wang, Lifan; Andreoni, Igor; Hall, Xander J.; Chen, Xingzhuo; Yang, Jiawen; Valdes, Frank; O'Connor, Brendan; Chen, Yuhan"
date: 2026-06-19
venue: 'Publications of the Astronomical Society of the Pacific'
paperurl: '/files/manuscripts/2026-06-19-GW-MMADS-pipeline.pdf'
citation: 'Hu, L., et al. &quot;A GPU-Accelerated Transient Detection Pipeline for DECam Time-Domain Surveys.&quot; <i>Publications of the Astronomical Society of the Pacific</i>. 2026.'
mycitation: 'Hu, L., <b>Cabrera, T.</b>, et al. &quot;A GPU-Accelerated Transient Detection Pipeline for DECam Time-Domain Surveys.&quot; <i>Publications of the Astronomical Society of the Pacific</i>. 2026.'
---
We present a GPU-accelerated transient detection pipeline developed for time-domain surveys with the Dark Energy Camera (DECam).
It enables real-time-capable image processing, incorporating science-driven candidate filtering to support rapid transient identification in time-critical observing programs.
The pipeline serves as the core transient discovery engine for multiple long-term DECam programs, including the GW-MMADS gravitational-wave follow-up campaign and the DESIRT survey for intermediate-redshift transients with DESI synergy.
The pipeline ingests calibrated imaging products from the DECam Community Pipeline and performs image differencing using the SFFT algorithm, coupled with CNN-based real-bogus classification, to produce science-ready transient alerts and light curves that are delivered to community brokers.
We validate the pipeline using archival DECam data from the DESIRT survey.
The real-bogus classifier achieves a completeness of ∼ 99\% of real transients while rejecting ∼ 96\% of subtraction artifacts, and the workflow typically reduces the candidate load to a manageable level for survey operations.
With GPU acceleration, the typical processing time per DECam exposure is ∼ 50 s from calibrated image processing to alert generation using a modest allocation of computing resources.