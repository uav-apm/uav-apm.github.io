---
title: "Disaster-Resilient Air Quality Monitoring: Machine Learning Reconstruction from Neighbouring Sensors"
collection: publications
category: conferences
permalink: /publication/2026-11-10-disaster-resilient-air-quality-monitoring
excerpt: 'A machine learning framework (BiLSTM and Extra Trees) that reconstructs PM2.5 and NO₂ at disaster-disrupted monitoring stations using data from surviving neighbouring stations.'
date: 2026-11-10
venue: '2026 International Conference on Information and Communication Technologies for Disaster Management (ICT-DM 2026), Dubai, United Arab Emirates'
paperurl: 'https://research.universityofgalway.ie/en/publications/disaster-resilient-air-quality-monitoring-machine-learning-recons/'
slidesurl: 'https://github.com/uav-apm/predict-lost-station-aq-ml/blob/main/docs/conference/ICT-DM26_Disaster-Resilient_AQ_Monitoring.pdf'
citation: 'Moursi, A., Kelleghan, D., &amp; Saber, T. (2026). &quot;Disaster-Resilient Air Quality Monitoring: Machine Learning Reconstruction from Neighbouring Sensors.&quot; <i>2026 International Conference on Information and Communication Technologies for Disaster Management (ICT-DM 2026)</i>, Dubai, United Arab Emirates.'
---

**Authors:** Ahmed Moursi, David Kelleghan, Takfarinas Saber

**Abstract:** Air pollution causes approximately eight million premature deaths annually, with children under five among the most vulnerable. In megacities like Delhi, one of the world's most polluted capitals, disasters including storms, floods, and earthquakes can destroy monitoring infrastructure, producing data gaps during the periods when monitoring is most needed for emergency response. This paper proposes a machine learning framework to reconstruct air quality at disaster-disrupted stations using data from surviving neighbours. Hourly records from four Delhi Pollution Control Committee (DPCC) stations spanning 2019 to 2025 were used, with 2024 reserved for validation and 2025 as the held-out test set simulating post-disaster conditions. A leave-one-out design assumed each station lost in turn, training on the remaining three to predict PM2.5 and NO₂. Bidirectional Long Short-Term Memory (BiLSTM) and Extra Trees were compared against a multi-station average baseline, with hyperparameters tuned via random search. For PM2.5, both models consistently outperformed all baselines across all stations, with BiLSTM achieving the best results. For NO₂, performance was spatially variable: both models improved over the baseline at most stations, but negative R² at one peri-urban station indicated that local emission sources dominated over network-wide spatial patterns, a limitation shared by all methods. Taken together, these results show that PM2.5 reconstruction from neighbouring stations is feasible without additional sensors, while NO₂ remains harder at sites dominated by local sources.

**Keywords:** air quality prediction, disaster resilience, sensor networks, machine learning

- Paper (accepted author manuscript, CC BY): [University of Galway Research Repository](https://research.universityofgalway.ie/en/publications/disaster-resilient-air-quality-monitoring-machine-learning-recons/)
- Slides: [PDF on GitHub](https://github.com/uav-apm/predict-lost-station-aq-ml/blob/main/docs/conference/ICT-DM26_Disaster-Resilient_AQ_Monitoring.pdf)
- Code: [uav-apm/predict-lost-station-aq-ml](https://github.com/uav-apm/predict-lost-station-aq-ml)
- Related post: [Presenting at ICT-DM 2026](/posts/2026/11/ict-dm-2026/)

This research was funded by Research Ireland through Lero, the Research Ireland Centre for Software, and co-funded by the European Union through the SyMeCo (Systems, Methods, Context) programme at the University of Galway.
