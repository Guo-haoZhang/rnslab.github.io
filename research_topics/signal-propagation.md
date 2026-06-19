---
layout: page
title: "Research Topics"
permalink: "/research/signal-propagation/"
---

{% include research_nav.html %}

## Signal Propagation Modeling

<br>
<hr style="border: none; border-top: 1px solid #ccc; margin: 0.5em 0 1em 0;" />

### Modeling of GNSS Signal Propagation in a Vegetated Environment
<br>

<img src="{{ '/assets/demos/Vegetation.jpg' | relative_url }}" alt="Vegetation" style="width: 90%;display: block; margin: 0 auto;" />

<div style="display: flex; gap: 1rem; align-items: flex-start;">
	<img src="{{ '/assets/demos/Vegetation2.jpg' | relative_url }}" alt="3DMA GNSS ray tracing" style="width: 40%;" />
	<img src="{{ '/assets/demos/Vegetation3.jpg' | relative_url }}" alt="3DMA GNSS ray tracing position" style="width: 55%;" />
</div>
<br>
<p style="text-align: justify;">
While GNSS signal degradation in urban environments has been extensively investigated, its propagation characteristics within vegetation remain unclear. This study introduces a novel modeling framework for GNSS signal propagation through broadleaf vegetation based on multiple scattering theory (MST). The canopy is approximated as a spherical volume containing randomly distributed and oriented discs (leaves) and finitelength cylinders (branches), providing enhanced physical realism compared to conventional cylindrical approximations. Based on MST, the model characterizes coherent field propagation as a function of propagation distance, the canopy’s geometrical and biophysical parameters.
</p>
<p style="text-align: justify;">
Related publications:<br>
D. Hai and G. Zhang, "Modeling of Coherent Field Attenuation for GNSS Signals Under Broad-leaf Vegetation," in Proceedings of the 38th International Technical Meeting of the Satellite Division of The Institute of Navigation (ION GNSS+ 2025), Baltimore, Maryland, September 2025, pp. 1154-1160. DOI: <a href="https://doi.org/110.33012/2025.20319" target="_blank">https://doi.org/10.33012/2025.20319</a>.<br>
D. Hai, C. L. Tsang, and G. Zhang, "Signal Processing Level Analysis of GNSS Performance Degradation in Vegetation Environments," IEEE Transactions on Instrumentation and Measurement.<br>
J. Zhou, T. Guillemaille, C. Meurie, G. Zhang and J. Marais, "Scalable GNSS Performance Assessment and Environment Categorization Under Vegetation," in 2025 IEEE/ION Position, Location and Navigation Symposium (PLANS), Salt Lake City, UT, USA, 2025, pp. 1204-1215, DOI: <a href="https://doi.org/10.1109/PLANS61210.2025.11028472" target="_blank">https://doi.org/10.1109/PLANS61210.2025.11028472</a>.
</p>

<br>
<hr style="border: none; border-top: 1px solid #ccc; margin: 0.5em 0 1em 0;" />

### GNSS RUMS: GNSS Realistic Urban Multiagent Simulator
<br>
<img src="{{ '/assets/demos/GNSS_RUMS.jpg' | relative_url }}" alt="Vegetation" style="width: 100%;display: block; margin: 0 auto;" />
<p style="text-align: justify;">
The GNSS measurement error behavior is complicated in urban areas and unable to be represented by naive models. On the other hand, real experiments requiring numbers of devices are difficult to conduct, especially for a large-scale test. Therefore, a GNSS realistic urban measurement simulator is developed to provide measurements for collaborative positioning studies. The proposed simulator employs a ray-tracing technique searching for all possible interferences in the urban area. Then, it categorizes them into direct, reflected, diffracted, and multipath signal to simulate the pseudorange, C/N0, and Doppler shift measurements correspondingly.
</p>
<p style="text-align: justify;">
Related publications:<br>
G. Zhang, B. Xu, H.-F. Ng, and L.-T. Hsu, "GNSS RUMS: GNSS Realistic Urban Multiagent Simulator for Collaborative Positioning Research," Remote Sensing, vol. 13, no. 4, p. 544, 02/2021, DOI: <a href="https://doi.org/10.3390/rs13040544" target="_blank">https://doi.org/10.3390/rs13040544</a>.<br>
G. Zhang and L.-T. Hsu, "Performance Assessment of GNSS Diffraction Models in Urban Areas," Navigation: Journal of the Institute of Navigation, vol. 68, no. 2, pp. 369–389, 03/2021, DOI: <a href="https://doi.org/10.1002/navi.417" target="_blank">https://doi.org/10.1002/navi.417</a>.
</p>