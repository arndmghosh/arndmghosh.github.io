---
title: "Leveraging Pretrained Models for Automatic Summarization of Doctor-Patient Conversations"
collection: publications
category: conferences
permalink: /publication/2021_emnlp_summarization
excerpt: 'In this paper, we explore the feasibility of using pretrained transformer models (BART) for summarizing doctor-patient conversations directly from transcripts.'
date: 2021-09-07
venue: 'EMNLP'
paperurl: 'https://aclanthology.org/2021.findings-emnlp.313/'
citation: 'Zhang, Longxiang, Renato Negrinho, Arindam Ghosh, Vasudevan Jagannathan, Hamid Reza Hassanzadeh, Thomas Schaaf, and Matthew R. Gormley. "Leveraging Pretrained Models for Automatic Summarization of Doctor-Patient Conversations." In Findings of the Association for Computational Linguistics: EMNLP 2021, pp. 3693-3712. 2021.'
---

Fine-tuning pretrained models for automatically summarizing doctor-patient conversation transcripts presents many challenges: limited training data, significant domain shift, long and noisy transcripts, and high target summary variability. In this paper, we explore the feasibility of using pretrained transformer models for automatically summarizing doctor-patient conversations directly from transcripts. We show that fluent and adequate summaries can be generated with limited training data by fine-tuning BART on a specially constructed dataset. The resulting models greatly surpass the performance of an average human annotator and the quality of previous published work for the task. We evaluate multiple methods for handling long conversations, comparing them to the obvious baseline of truncating the conversation to fit the pretrained model length limit. We introduce a multistage approach that tackles the task by learning two fine-tuned models: one for summarizing conversation chunks into partial summaries, followed by one for rewriting the collection of partial summaries into a complete summary. Using a carefully chosen fine-tuning dataset, this method is shown to be effective at handling longer conversations, improving the quality of generated summaries. We conduct both an automatic evaluation (through ROUGE and two concept-based metrics focusing on medical findings) and a human evaluation (through qualitative examples from literature, assessing hallucination, generalization, fluency, and general quality of the generated summaries).