---
title: "A Probability Fusion Approach for Foot Placement Prediction in Complex Terrains"
collection: publications
category: manuscripts
permalink: /publication/FootPlacementPrediction
excerpt: 'A probability fusion approach using visual infromation and IMU for foot placement prediction.'
date: 2025-11-23
venue: 'IEEE Transactions on Neural Systems and Rehabilitation Engineering'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1109/TNSRE.2023.3333685'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'J. Xiong, C. Chen, Y. Zhang, X. Chen, Y. Qian, Y. Leng, and C. Fu, "A Probability Fusion Approach for Foot Placement Prediction in Complex Terrains," in IEEE Transactions on Neural Systems and Rehabilitation Engineering, vol. 31, pp. 4591-4600, 2023, doi: 10.1109/TNSRE.2023.3333685. '
---
Prediction of foot placement presents great potential in better assisting the walking of people with lower-limb disability in daily terrains. Previous researches mainly focus on foot placement prediction in level ground walking, however these methods cannot be applied to daily complex terrains including ramps, stairs, and level ground with obstacles. To predict foot placement in complex terrains, this paper presents a probability fusion approach for foot placement prediction in complex terrains which consists of two parts: model training and foot placement prediction. In the first part, a deep learning model is trained on augmented data to predict the probability distribution of preliminary foot placement. In the second part, environmental information and human walking constraints are used to calculate the feasible area, and finally the feasible area is fused with the probability distribution of preliminary foot placement to predict the foot placement in complex terrains. The proposed method can predict the foot placement of next step in complex terrains when heel-off is detected. Experiments (including structured terrains experiments and complex terrains experiments) show that the root mean square error (RMSE) of prediction is 8.19 ± 1.20 cm, which is less than 8% of the average stride length, and the landing feasible area accuracy (LFAA) of prediction is 95.11 ± 3.09%. Comparing with existing foot placement prediction studies, the method proposed in this paper achieves faster and more accurate prediction in complex terrains.