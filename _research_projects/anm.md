---
title: "Edge-Based Sleep-Stage Classification with Change Point Detection 🛌"
permalink: /research_projects/anm
excerpt: 'Machine Learning Project'
date: 2025-06-01
---

<center><img src="/images/research_projects/anm.png" width="600" height="600" /></center>


Wearable devices can monitor sleep stages, but running sophisticated sleep stage classification models on-device is challenging due to limited resources. In this work, we develop a lightweight model for real-time sleep stage classification on the edge (e.g., Apple Watch) with a novel focus on wake-up timing. We incorporate change point detection (CPD) to identify transitions between sleep stages and evaluate performance using a timing-based metric, since traditional accuracy is limited by noisy sensor data and imperfect labels. Experiments on the Sleep-Accel dataset demonstrate that while overall classification accuracy is relatively low (around 40%–50%), the inclusion of CPD often improves the prediction of optimal wake-up times. Our approach achieves only modest F1 and accuracy scores, but can trigger a smart alarm within mere minutes of the ideal wake stage, highlighting the importance of timing-based evaluation for smart alarm applications.

Shani Kagan Micheletti, Diego Cerretti, Thomas Adler

* [Report](https://drive.google.com/file/d/10PWNeB0PoAYyqU7b0wKne5iIXcOg6v75/view?usp=drive_link)

* [Presentation](https://drive.google.com/file/d/1B3pLF3A_yqmJwR1YDtxAuxpa-oY4exyV/view?usp=drive_link)

<center><img src="/images/cv/th1.png" width="350" height="350" /></center>
