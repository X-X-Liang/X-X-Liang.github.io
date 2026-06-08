---
layout: post
title: "Software Release: LIBDAR v1.1.0 Now Available on Zenodo"
date: 2026-02-17 16:11:00-0400
inline: false
related_posts: false
---

I am thrilled to announce the release of **LIBDAR v1.1.0**, an open-source MATLAB toolbox dedicated to simulating laser-induced bubble dynamics and acoustic radiation. The software is officially published and freely available for download on Zenodo.

**Key Updates in Version 1.1.0:**
* **Tunable Ambient Pressure:** The ambient pressure (p∞) is now a fully adjustable input parameter within the extended Gilmore model.
* **Advanced Liquid Properties:** The model now integrates pressure-dependent liquid properties—specifically ambient mass density and sound speed—derived from the Tait equation of state.
* **Refined Shock Calculations:** The Kirkwood–Bethe shock calculation has been updated to account for the modified pressure distribution in the surrounding liquid.

These physical enhancements allow the toolbox to accurately propagate dynamics across a broad ambient pressure range (0.1 MPa to 50 MPa) while remaining perfectly backward compatible with low-pressure results. We have also included new example scripts so users can immediately explore the effects of ambient pressure on bubble evolution.

🔗 **[Access and download LIBDAR v1.1.0 on Zenodo (DOI: 10.5281/zenodo.18668695)](https://doi.org/10.5281/zenodo.18668695)**

**Recommended Citation:** 
Liang, X.-X., & Vogel, A. (2026). *LIBDAR: A Matlab toolbox for laser-induced bubble dynamics and acoustic radiation (v1.1.0).* Zenodo.
