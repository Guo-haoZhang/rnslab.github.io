---
layout: page
title: "Research Topics"
permalink: "/research/indoor-positioning/"
---

{% include research_nav.html %}

## Indoor Positioning and Indoor Navigation

<br>
<hr style="border: none; border-top: 1px solid #ccc; margin: 0.5em 0 1em 0;" />

### Indoor Radio Simultaneous Localization and Mapping (SLAM)
<br>
<div style="display: flex; gap: 1rem; align-items: flex-start;">
	<img src="{{ '/assets/demos/RSLAM2.jpg' | relative_url }}" alt="3DMA GNSS ray tracing" style="width: 50%;" />
	<img src="{{ '/assets/demos/RSLAM1.gif' | relative_url }}" alt="3DMA GNSS ray tracing position" style="width: 45%;" />
</div>
<div style="display: flex; gap: 1rem; align-items: flex-start;">
	<img src="{{ '/assets/demos/RSLAM3.jpg' | relative_url }}" alt="3DMA GNSS ray tracing" style="width: 50%;" />
	<img src="{{ '/assets/demos/rslam4.gif' | relative_url }}" alt="3DMA GNSS ray tracing position" style="width: 45%;" />
</div>
<p style="text-align: justify;">
Location awareness is a foundational component for indoor wireless applications. In conventional ranging-based systems, accurate localization relies on the precise pre-survey of infrastructure anchors. However, the anchor’s position is not always known in practical applications, which limits the scalability of indoor positioning services. To overcome this dependency, radio Simultaneous Localization and Mapping (SLAM) is proposed. It treats the unknown anchor positions as latent variables to be jointly estimated alongside the user trajectory. Building on this method, the challenges of harsh multipath conditions can be recast as opportunities. Multipath-assisted positioning exploits specular Multipath Components (MPCs) by associating them with environmental geometry rather than treating multipath effect as interference. These specular reflections are modeled as signals originating from Virtual Anchors (VAs), which are mirror images of physical anchors relative to reflective surfaces. By capturing these MPCs, the information density is improved and the lower error bound of the positioning system is reduced. Consequently, radio SLAM jointly estimates the positions of the agent, the physical anchor, and the virtual anchors, thereby enabling localization with one anchor even when no prior anchor position exists.
</p>
<p style="text-align: justify;">
Related publications:<br>
Z. Lyu and G. Zhang, "Observability Analysis for Resolving Global Ambiguities in Map-assisted Radio SLAM," in the Fifteenth International Conference on Indoor Positioning and Indoor Navigation (IPIN 2026), 2026, GitHub: <a href="https://github.com/Togure/Floorplan-assisted-Radio-SLAM-Observability-analysis" target="_blank">https://github.com/Togure/Floorplan-assisted-Radio-SLAM-Observability-analysis</a>. (Accepted and to be presented)<br>
Z. Lyu and G. Zhang, "Enhanced Radio-SLAM Algorithm Using Building Geometry Constraints," in IPIN-WCAL 2025: Workshop for Computing & Advanced Localization at the Fifteenth International Conference on Indoor Positioning and Indoor Navigation, Tampere, Finland, 2025.
</p>
<br>
<hr style="border: none; border-top: 1px solid #ccc; margin: 0.5em 0 1em 0;" />

### Wi-Fi Round-Trip-Time Positioning Assisted by Floor Plan
<br>
<img src="{{ '/assets/demos/RTT.jpg' | relative_url }}" alt="Vegetation" style="width: 70%;display: block; margin: 0 auto;" />
<br>
<p style="text-align: justify;">
Indoor positioning is crucial for many location-based applications, including emergency response, smart cities, and pedestrian navigation in large indoor complexes. Modern mobile devices like smartphones embed rich computational resources and a variety of sensors like MEMS inertial measurement units (IMU), cameras, GNSS, and Wi-Fi receivers. Among tehm, Wi-Fi round-trip-time (RTT) based indoor positioning has attracted much attention since the publication of IEEE 802.11-2016 standard. It introduces a fine-time measurement (FTM) protocol that enables decimeter-resolution ranging on commodity Wi- Fi devices. In this study, we investigate a NLOS ranging model, coined as a multiwall model (MWM), for Wi-Fi RTT indoor positioning, especially accounting for the range biases due to through-wall signal transmission.
</p>
<p style="text-align: justify;">
Related publications:<br>
Z. Lyu, S. Bai, X. Wang, L. Li and G. Zhang, "Wi-Fi RTT Indoor Positioning Using Visibility Matching with NLOS Receptions," IEEE Internet of Things Journal, vol. 12, no. 12, pp. 18779-18790, 06/2025, DOI: <a href="https://doi.org/10.1109/JIOT.2025.3559065" target="_blank">https://doi.org/10.1109/JIOT.2025.3559065</a>.<br>
Q. Liang, G. Zhang, and L.-T. Hsu, "Accurate Wi-Fi RTT Indoor Positioning with NLOS Mitigation by Floor Map: A Multi-wall Modeling," IEEE Transactions on Instrumentation and Measurement, vol. 75, pp. 9522316-9522316, 2026, Art no. 9522316, DOI: <a href="https://doi.org/10.1109/TIM.2024.3436101" target="_blank">https://doi.org/10.1109/TIM.2024.3436101</a>.
</p>

<br>