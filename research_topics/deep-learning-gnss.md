---
layout: page
title: "Research Topics"
permalink: "/research/deep-learning-gnss/"
---

{% include research_nav.html %}

## Deep Learning Assisted GNSS

<br>
<hr style="border: none; border-top: 1px solid #ccc; margin: 0.5em 0 1em 0;" />

<img src="{{ '/assets/demos/LSTM.jpg' | relative_url }}" alt="LSTM" style="width: 70%;display: block; margin: 0 auto;" />
<p style="text-align: justify;">
Besides positioning information, GNSS receiver also provide additional information about the signal status. However, their association with the signal and positioning may be complicated and hard to be employ by traditional methods. Deep learning is excellent in extracting hidden information and stablish underlying correlations according to data. Thus, it is potential to use deep learning to extra new hidden features to assist GNSS positioning in challenging environments.
</p>
<br>
<img src="{{ '/assets/demos/Transformer.jpg' | relative_url }}" alt="LSTM" style="display: block; margin: 0 auto;" />
<img src="{{ '/assets/demos/Transformer2.jpg' | relative_url }}" alt="LSTM" style="width: 80%;display: block; margin: 0 auto;" />
<p style="text-align: justify;">
This study aims to develop a deep learning framework to explore the spatial correlation between GNSS satellites and the hidden features lated to the signal status, which can further infer the surrounding environment for sensing and predict the measurement status and uncertainty. Our team has developed different deep learning architectures (e.g., LSTM, Transformer, reinforcement learning, etc.) to perform environment sensing, NLOS classification/correction, and fault detection and exclusion.
</p>
<p style="text-align: justify;">
Related publications:<br>
Z. Zhang, P. Xu, and G. Zhang, "Intelligent Urban GNSS Measurement Uncertainty Prediction by Exploring the Spatial Characteristics with Transformer," Applied Soft Computing, vol. 184, part A, pp.113773, 08/2025, DOI: <a href="https://doi.org/10.1016/j.asoc.2025.113773" target="_blank">https://doi.org/10.1016/j.asoc.2025.113773</a>.<br>
Z. Zhang, P. Xu, G. Zhang, and L. T. Hsu, "GNSS-based Environment Retrieval: A Deep Learning Approach for Fine-grained Environment Perception," IEEE Transactions on Intelligent Vehicles, pp. 1-13, 08/2024, DOI: <a href="https://doi.org/10.1109/TIV.2024.3440645" target="_blank">https://doi.org/10.1109/TIV.2024.3440645</a>.<br>
G. Zhang, P. Xu, H. Xu, and L.-T. Hsu, "Prediction on the Urban GNSS Measurement Uncertainty based on Deep Learning Networks with Long Short-Term Memory," IEEE Sensors Journal, vol. 21, no. 18, pp. 20563-20577, 09/2021, DOI: <a href="https://doi.org/10.1109/JSEN.2021.3098006" target="_blank">https://doi.org/10.1109/JSEN.2021.3098006</a>.
</p>