---
title: "Adafocal: Calibration-aware adaptive focal loss"
collection: publications
category: conferences
permalink: /publication/2022_neurips_adafocal
excerpt: 'This paper proposes Adafocal training algorithm that produces better calibrated models without any significant loss in accuracy/performance.'
date: 2022-11-28
venue: 'Advances in Neural Information Processing Systems 35'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2022/hash/0a692a24dbc744fca340b9ba33bc6522-Abstract-Conference.html'
citation: 'Ghosh, Arindam, Thomas Schaaf, and Matthew Gormley. “Adafocal: Calibration-aware adaptive focal loss.” Advances in Neural Information Processing Systems 35 (2022): 1583-1595.'
---

Much recent work has been devoted to the problem of ensuring that a neural network's confidence scores match the true probability of being correct, i.e. the calibration problem. Of note, it was found that training with focal loss leads to better calibration than cross-entropy while achieving similar level of accuracy \cite{mukhoti2020}. This success stems from focal loss regularizing the entropy of the model's prediction (controlled by the parameter γ), thereby reining in the model's overconfidence. Further improvement is expected if γ is selected independently for each training sample (Sample-Dependent Focal Loss (FLSD-53) \cite{mukhoti2020}). However, FLSD-53 is based on heuristics and does not generalize well. In this paper, we propose a calibration-aware adaptive focal loss called AdaFocal that utilizes the calibration properties of focal (and inverse-focal) loss and adaptively modifies γt for different groups of samples based on γt−1 from the previous step and the knowledge of model's under/over-confidence on the validation set. We evaluate AdaFocal on various image recognition and one NLP task, covering a wide variety of network architectures, to confirm the improvement in calibration while achieving similar levels of accuracy. Additionally, we show that models trained with AdaFocal achieve a significant boost in out-of-distribution detection.
