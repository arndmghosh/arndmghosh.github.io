---
title: "Low-resource Low-footprint Wake-word Detection using Knowledge Distillation"
collection: publications
category: conferences
permalink: /publication/2022_interspeech_wakeword
excerpt: 'This paper explores two techniques to leverage acoustic modeling data for large-vocabulary speech recognition to improve a purpose-built wake-word detector: transfer learning and knowledge distillation.'
date: 2022-09-18
venue: 'Interspeech'
paperurl: 'https://www.isca-archive.org/interspeech_2022/ghosh22_interspeech.html'
citation: 'Ghosh, A., Fuhs, M., Bagchi, D., Farahani, B., Woszczyna, M. (2022) Low-resource Low-footprint Wake-word Detection using Knowledge Distillation. Proc. Interspeech 2022, 3739-3743, doi: 10.21437/Interspeech.2022-529.'
---

As virtual assistants have become more diverse and specialized, so has the demand for application or brand-specific wake words. However, the wake-word-specific datasets typically used to train wake-word detectors are costly to create. In this paper, we explore two techniques to leverage acoustic modeling data for large-vocabulary speech recognition to improve a purpose-built wake-word detector: transfer learning and knowledge distillation. We also explore how these techniques interact with time-synchronous training targets to improve detection latency. Experiments are presented on the open-source "Hey Snips” dataset and a more challenging in-house far-field dataset. Using phone-synchronous targets and knowledge distillation from a large acoustic model, we are able to improve accuracy across dataset sizes for both datasets while reducing latency.
