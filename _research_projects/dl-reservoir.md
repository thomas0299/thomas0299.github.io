---
title: "Reservoir Computing for Time-Series Forecasting 📈"
permalink: /research_projects/dl-reservoir
excerpt: 'Machine Learning Project'
date: 2025-06-01
---

<center><img src="/images/research_projects/dl-reservoir_1.png" width="600" height="600" /></center>


Reservoir Computing (RC) is a type of lightweight RNN that achieves near-state-of-the-art performance for specific time-series forecasting tasks. RC leverages a fixed, untrained reservoir to produce rich nonlinear dynamics while training only a readout layer, resulting in minimal memory and computational requirements. Motivated from sleep stage prediction on edge devices, we use RCs to forecast key physiological signals which correlate with sleep stages, and exhibit irregular and subject-specific dynamics. We evaluate RC performance on per-subject forecasting tasks, analyse the influence of spectral radius and reservoir size. In addition, we compare results across diverse real-world and chaotic time-series datasets. Our experiments reveal that RC achieves high accuracy for short-horizon forecasts but declines with longer horizons; it struggles with noisy sleep variables yet performs well on chaotic or smoother real-world series. Deep reservoirs consistently outperform shallow architectures. When performance is high, RC models maintain very few trainable parameters, while training and inferring in mere seconds. Moreover, sparsely connected reservoirs surpass fully connected ones in accuracy. These findings demonstrate that RC represents a broadly viable, resource-efficient framework for real-time, on-edge time-series forecasting.

Shani Kagan Micheletti, Diego Cerretti, Thomas Adler

* [Poster](https://drive.google.com/file/d/1N3svFkLGqmq9oRglIMM2OqXnzWYkdpoZ/view?usp=drive_link)

* [Report](https://drive.google.com/file/d/1db28WJ6ErlRq7o1YDCq0U91grxaEApe7/view?usp=drive_link)


<center><img src="/images/research_projects/dl-reservoir_2.png" width="600" height="600" /></center>
<center><img src="/images/research_projects/dl-reservoir_3.png" width="600" height="600" /></center>


<center><img src="/images/cv/th1.png" width="350" height="350" /></center>
