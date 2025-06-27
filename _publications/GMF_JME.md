---
title: "Joint Moment Estimation for Hip Exoskeleton Control: A Generalized Moment Feature Generation Method"
collection: publications
category: manuscripts
permalink: /publication/GMF_JME
excerpt: 'A novel hip joint moment estimation method and its application on an exoskeleton.'
date: 2025-06-09
venue: 'Biomimetic Intelligence and Robotics'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S2667379725000373'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Zhang Y, Xiong J, Xian H, et al. Joint moment estimation for hip exoskeleton control: A generalized moment feature generation method[J]. <i>Biomimetic Intelligence and Robotics</i>, 2025: 100246.'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Hip joint moments during walking are the key foundation for hip exoskeleton assistance control. Most recent studies have shown estimating hip joint moments instantaneously offers a lot of advantages compared to generating assistive torque profiles based on gait estimation, such as simple sensor requirements and adaptability to variable walking speeds. However, existing joint moment estimation methods still suffer from a lack of personalization, leading to estimation accuracy degradation for new users. To address the challenges, this paper proposes a hip joint moment estimation method based on generalized moment features (GMF). A GMF generator is constructed to learn GMF of the joint moment which is invariant to individual variations while remaining decodable into joint moments through a dedicated decoder. Utilizing this well-featured representation, a GRU-based neural network is used to predict GMF with joint kinematics data, which can easily be acquired by hip exoskeleton encoders. The proposed estimation method achieves a root mean square error of 0.1180 ± 0.0021 Nm/kg under 28 walking speed conditions on a treadmill dataset, improved by 6.5% compared to the model without body parameter fusion, and by 8.3% for the conventional fusion model with body parameter. Furthermore, the proposed method was employed on a hip exoskeleton with only encoder sensors and achieved an average 20.5% metabolic reduction (p < 0.01) for users compared to assist-off condition in level-ground walking.