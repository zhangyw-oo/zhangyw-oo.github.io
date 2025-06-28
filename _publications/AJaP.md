---
title: "AJaP: An Adaptive Network for Hip Joint Angle Prediction in Assistive Walking with Continual Learning"
collection: publications
category: manuscripts
permalink: /publication/AJaP
excerpt: 'An adaptive joint angle prediction method able to selt-optimize under real world.'
date: 2025-06-23
venue: 'IEEE Transactions on Cognitive and Developmental Systems'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1109/TCDS.2025.3582970'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Y. Zhang, J. Xiong, H. Xian, X. Chen, C. Fu and Y. Leng, "AJaP: An Adaptive Network for Hip Joint Angle Prediction in Assistive Walking with Continual Learning," in IEEE Transactions on Cognitive and Developmental Systems, doi: 10.1109/TCDS.2025.3582970.'
---
Predicting lower limb joint angles during human walking is crucial for enhancing the control performance of assistive wearable robots. Existing studies typically use surface electromyography for joint angle prediction. However, this sensor is easily affected by measurement conditions (such as skin environment and assembly position) and requires complex preprocessing of the measured signals. This paper proposes a method for predicting future hip joint angles using only motor encoders from exoskeleton robots. A joint angle predictor, trained on offline datasets, is introduced to capture comprehensive information through multi-scale and multi-span sampling of the joint angle time series. Moreover, to overcome issues such as user variability, sensor data drift, and terrain change in real-world exoskeleton applications, an adaptive strategy based on continual learning is employed to improve the prediction accuracy of JaP, referred to as AJaP. In offline joint angle prediction for time horizons of 50 ms, 100 ms, and 200 ms, the proposed JaP achieved mean absolute errors of [0.7846 ± 0.0859°, 1.5752 ± 0.0666°, 2.5887 ± 0.0872°], respectively. During exoskeleton-assisted walking experiments, AJaP achieved joint angle prediction mean absolute errors of [1.6132 ± 0.2450°, 2.1850 ± 0.82190, 3.2091 ± 1.1393°] on level ground, ramp, and stair at 100 ms. With adaptive optimization, the prediction accuracy of AJaP improved by [59.76%, 60.21%, 64.77%] compared to directly deploying JaP.