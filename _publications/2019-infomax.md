---
title: "QAInfomax: Learning robust question answering system by mutual information maximization."
collection: publications
permalink: /publication/2019-infomax
excerpt: '
**Yi-Ting Yeh**, and Yun-Nung Chen.
'
date: 2019-11-03
venue: 'The 2019 Conference on Empirical Methods in Natural Language Processing (EMNLP)'
paperurl: 'https://arxiv.org/abs/1909.00215'
codeurl: 'https://github.com/MiuLab/QAInfomax'

---

**Yi-Ting Yeh**, and Yun-Nung Chen.

Full Paper: [arXiv](https://arxiv.org/abs/1909.00215)

Code: [GitHub](https://github.com/MiuLab/QAInfomax)

Video: [Vimeo](https://vimeo.com/426361695)

Standard accuracy metrics indicate that modern reading comprehension systems have achieved strong performance in many question answering datasets. 

However, the extent these systems truly understand language remains unknown, and existing systems are not good at distinguishing distractor sentences, which look related but do not actually answer the question. 

To address this problem, we propose QAInfomax as a regularizer in reading comprehension systems by maximizing mutual information among passages, a question, and its answer. 

QAInfomax helps regularize the model to not simply learn the superficial correlation for answering questions. 

The experiments show that our proposed QAInfomax achieves the state-of-the-art performance on the benchmark Adversarial-SQuAD dataset. 