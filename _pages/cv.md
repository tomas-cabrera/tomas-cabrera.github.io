---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

My complete CV may be found in pdf form <a href="/files/cv_cabrera.pdf" target="_blank">here</a> (last updated 2026-06-30).

## Education
* Ph.D. in Physics, Carnegie Mellon University, 2026 (expected)
  * M.S. in Physics, Carnegie Mellon University, 2022
* B.S. in Physics, Massachusetts Institute of Technology, 2019

## Skills
* **Software:** Python (numpy, pandas, scipy, matplotlib, astropy), git, GitHub, Unix, Slurm; familiarity with C, SQL
* **Analytical:** Data visualization, Bayesian inference, statistics, N-body simulations
* **Astronomy:** Photometry, difference imaging, spectroscopy, observation planning/execution, transient classification, gravitational wave follow-up; HEALPix skymaps, TOPCAT, DS9
* **Observation experience:** DECam (15+ nights), Gemini GMOS (10 hours), SALT RSS (3+ targets), *Swift* (5+ targets), Lowell Discovery Telescope (4 hours)

## PhD Thesis: *"Constraining dynamical formation channels of LIGO/Virgo/KAGRA binary black holes"*

* **Real-time discovery of electromagnetic counterparts to gravitational wave events**
  * Designed and implemented GPU-enabled image differencing pipeline to process DECam telescope images in real-time
  * Installed and operated pipeline on HPC systems (Pittsburgh Supercomputing Center, National Energy Research Scientific Computing Center), and optimized pipeline parallelization on such resources
  * Developed software tools to automate observation planning, and distributed such tools as [healpix-painter<i class="fa-brands fa-github"></i>](https://github.com/tomas-cabrera/healpix-painter) Python package
  * Led real-time follow-ups of gravitational wave alerts, including the triggering of additional multi-wavelength and spectroscopic resources to collect additional data on promising counterpart candidates
  * Administered and maintained internal SQL database to supply archival context to new discoveries

* **Measuring correlations between binary black holes and formation environments**
  * Refined and applied Bayesian inference methods to catalogs of active galactic nucleus (AGN) flares and binary black holes to constrain the fraction of AGN-hosted mergers
  * Optmized legacy Monte Carlo N-body simulations in C to study populations of black holes in star clusters of 10<sup>7+</sup> objects

* **AGN transient modeling with archival photometric data**
  * Generated 13-year baseline AGN lightcurve catalogs from archival DECam deep field data
  * Developed machine learning tools to identify and classify transient flares in AGN lightcurves

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

16 NASA GCN Circulars and 779 TNS submissions reporting transients found with the GW-MMADS pipeline

## Talks

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

<!--
## Allocations

* **Telescope**
  * PI: "Riddles in the Dark: Deciphering the origin of BBH mergers through spectroscopic study of potential AGN flare counterparts" (Gemini Fast Turnaround January 2025, renewed May 2025, 6 hours)
  * PI: "Searching for variability in the spectrum of an electromagnetic counterpart candidate to the gravitational wave
event S230922g" (Gemini DDT 2023B, 1 hour)
  * PI: "Spectroscopic follow-up of a new electromagnetic counterpart candidate to the gravitational wave event
S230922g" (Gemini DDT 2023B, 1 hour)
  * co-I: "GW-MMADS: Gravitational Wave Multi-Messenger Astronomy DECam Survey" (PIs Andreoni & Palmese;
DECam GW follow-up survey during the LIGO/Virgo/KAGRA O4 run, 2023-2025; proposal ID 2023B-851374,
extended from allocated standard programs 2022B-715089, PI Palmese and 2022B-922046, PIs Andreoni &
Palmese)
  * co-I on various additional electromagnetic counterpart discovery proposals for the LIGO/Virgo/KAGRA O4 run
* **Compute**
  * PI: "Archival search for AGN transients in DECam deep fields" (Pittsburgh Supercomputing Center Discover
Allocation, 2025-2026)
  * co-I on various PSC and NERSC allocations supporting PhD research since 2020
-->