---
layout: page
title: "Research Topics"
permalink: "/research/3dma-gnss/"
---

{% include research_nav.html %}

## 3D Mapping Aided GNSS
<p style="text-align: justify;">
The 3D mapping aided (3DMA) GNSS employs a 3D building model to simulate and predict the signal signal receptions (measurement availability, reflection bias, diffraction attenuation, etc.), which further assists the positioning by exploring its match with the real received measurement. It shows promising improvements in positioning accuracy compared to other GNSS positioning techniques, especially in dense urban areas.
</p>
<br>
<hr style="border: none; border-top: 1px solid #ccc; margin: 0.5em 0 1em 0;" />

### 3DMA GNSS Shadow Matching & Ray-Tracing
<br>
<img src="{{ '/assets/demos/Shadow matching video.gif' | relative_url }}" alt="3DMA GNSS" />
<p style="text-align: justify;">
Shadow matching conducts positioning by finding the candidate agent position with a 3D-building-model-based satellite visibility prediction that matches with the actual measurement-based satellite visibility evaluation, which is similar the concept of fingerprinting.
</p>
<div style="display: flex; gap: 1rem; align-items: flex-start;">
	<img src="{{ '/assets/demos/RT.jpg' | relative_url }}" alt="3DMA GNSS ray tracing" style="width: 35%;" />
	<img src="{{ '/assets/demos/RT_pos.gif' | relative_url }}" alt="3DMA GNSS ray tracing position" style="width: 66.67%;" />
</div>
<p style="text-align: justify;">
Besides using the signal obstructions, 3DMA GNSS ray-tracing uses the NLOS receptions to aid positioning. It first simulates the GNSS pseudorange measurements, including the reflection delay, based on the 3D building model and signal propagation geometry. Then, positioning is conducted by finding the candidate agent position with the simulated interfered measurements that most match the received measurements.
</p>
<p style="text-align: justify;">
Related publications:<br>
G. Zhang, H.-F. Ng, W. Wen, and L.-T. Hsu, "3D Mapping Database Aided GNSS Based Collaborative Positioning Using Factor Graph Optimization," IEEE Transactions on Intelligent Transportation Systems, vol. 22, no. 10, pp. 6175-6187, 10/2021, DOI: <a href="https://doi.org/10.1109/TITS.2020.2988531" target="_blank">https://doi.org/10.1109/TITS.2020.2988531</a>.<br>
G. Zhang, W. Wen, B. Xu, and L. Hsu, "Extending Shadow Matching to Tightly-Coupled GNSS/INS Integration System," IEEE Transactions on Vehicular Technology, vol. 69, no. 5, pp. 4979-4991, 05/2020, DOI: <a href="https://doi.org/10.1109/TVT.2020.2981093" target="_blank">https://doi.org/10.1109/TVT.2020.2981093</a>.
</p>

<br>
<hr style="border: none; border-top: 1px solid #ccc; margin: 0.5em 0 1em 0;" />

### 3DMA GNSS using Diffraction Feature Matching
<br>
<img src="{{ '/assets/images/3DMA_GNSS_1.jpg' | relative_url }}" alt="3DMA GNSS" />
<p style="text-align: justify;">
Diffraction effects may arise when a GNSS signal propagates in close proximity to building edges, leading to propagating around obstacles and consequent attenuation. Diffraction effects are common for GNSS signals in urban environments but have not been well utilized. This study turns diffracted GNSS signals from a source of error into a useful location-dependent feature for positioning, instead of ignoring or excluding them by most existing methods. This provides a new information source for feature-matching based positioning techniques.
</p>
<p style="text-align: justify;">
Related publications:<br>
D. Hai, H.-F. Ng, G. Zhang, and L.-T. Hsu "Improving GNSS Positioning in Dense Urban Areas by Diffraction Feature Matching," NAVIGATION: Journal of the Institute of Navigation, vol. 73, 2026, DOI: <a href="https://doi.org/10.33012/navi.759" target="_blank">https://doi.org/10.33012/navi.759</a>.<br>
G. Zhang and L.-T. Hsu, "Performance Assessment of GNSS Diffraction Models in Urban Areas," Navigation: Journal of the Institute of Navigation, vol. 68, no. 2, pp. 369–389, 03/2021, DOI: <a href="https://doi.org/10.1002/navi.417" target="_blank">https://doi.org/10.1002/navi.417</a>.
</p>
<br>
<hr style="border: none; border-top: 1px solid #ccc; margin: 0.5em 0 1em 0;" />

### 3DMA GNSS Doppler Velocity Estimation

<br>

<img src="{{ '/assets/images/3DMA_GNSS_2.jpg' | relative_url }}" alt="3DMA GNSS 2" />

<br>

<p style="text-align: justify;">
Besides position solutions, GNSS also provides the receiver velocity information from its
Doppler frequency measurement, which is vital for intelligent transportation
applications, such as accurate navigation for road agents or traffic flow management.
However, the accuracy of GNSS velocity estimation could be severely degraded by the
non-line-of-sight (NLOS) receptions and multipath effects on Doppler frequency in
urban canyons. This study aims to explore the NLOS characteristics on GNSS Doppler shift measurements, and turn these degradations into useful features to improve the velocity estimation in urban areas.
</p>
<p style="text-align: justify;">
Related publications:<br>
L. Zhang, H.-F. Ng, Y. Zhong, G. Zhang, and L. T. Hsu, "GNSS Doppler Velocity Estimation Aided by 3D Mapping Database," IEEE Transactions on Intelligent Transportation Systems, vol. 26, no. 1, pp. 1215-1226, 01/2025, DOI: <a href="https://doi.org/10.1109/TITS.2024.3486448" target="_blank">https://doi.org/10.1109/TITS.2024.3486448</a>.<br>
L. Zhang, H. F. Ng, G. Zhang, and L. T. Hsu, "Ray-Tracing Correction for GNSS Velocity Estimation Using Doppler Frequency: A Feasibility Analysis," IEEE Transactions on Instrumentation and Measurement, vol. 73, pp. 1-10, 04/2024, DOI: <a href="https://doi.org/10.1109/TIM.2024.3385033" target="_blank">https://doi.org/10.1109/TIM.2024.3385033</a>.
</p>
<br>
<hr style="border: none; border-top: 1px solid #ccc; margin: 0.5em 0 1em 0;" />
