---
layout: post
title: "New article - Tox-based prioritization of unknown features"
---

## Prioritization of Unknown LC-HRMS Features Based on Predicted Toxicity Categories

Complex environmental samples contain a diverse array of known and unknown constituents. While liquid chromatography coupled with high-resolution mass spectrometry (LC-HRMS) nontargeted analysis (NTA) has emerged as an essential tool for the comprehensive study of such samples, the identification of individual constituents remains a significant challenge, primarily due to the vast number of detected features in each sample. To address this, prioritization strategies are frequently employed to narrow the focus to the most relevant features for further analysis. In this study, we developed a novel prioritization strategy that directly links fragmentation and chromatographic data to aquatic toxicity categories, bypassing the need for identification of individual compounds. Given that features are not always well-characterized through fragmentation, we created two models: (1) a Random Forest Classification (RFC) model, which classifies fish toxicity categories based on MS1, retention, and fragmentation data─expressed as cumulative neutral losses (CNLs)─when fragmentation information is available, and (2) a Kernel Density Estimation (KDE) model that relies solely on retention time and MS1 data when fragmentation is absent. Both models demonstrated accuracy comparable to that of structure-based prediction methods. We further tested the models on a pesticide mixture in a tea extract measured by LC-HRMS, where the CNL-based RFC model achieved 0.76 accuracy and the KDE model reached 0.61, showcasing their robust performance in real-world applications. [here](https://pubs.acs.org/doi/10.1021/acs.est.4c13026).

![Graphical Abstract](https://github.com/EMCMS/emcms/blob/gh-pages/assets/img/ToxCat_Vika.jpeg?raw=true)
