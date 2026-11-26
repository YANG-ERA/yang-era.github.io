---
title: "CellPatch: a flexible and efficient framework for single-cell foundation models empowered by heuristic gene patching"
collection: publications
category: manuscripts
permalink: /publication/2026-cellpatch
excerpt: >-
  CellPatch is a lightweight foundation model for single-cell gene expression. We use cross-attention to summarize a variable number of expressed genes into a fixed set of learned patches, reducing the amount of computation needed for training and fine-tuning. The model supports different decoders, and we evaluated it on cell-type annotation, spatial domain detection, and gene-expression response prediction after perturbation. The attention weights can also be inspected to see which genes contribute to each patch.
contribution: "As a co-first author, I helped validate the model and write the manuscript."
date: 2026-10-30
venue: "Genome Biology"
authors: "Hanwen Zhu, Yushun Yuan, Jiyuan Yang, Kangwen Cai, Nana Wei, Senxin Zhang, Lu Wang, Wen-Jie Jiang, Yuanchen Sun, An Liu, Futing Lai, Yu-Juan Wang, Zeyu Ma, Xiaoqi Zheng, Hua-Jun Wu"
role: "Co-first author"
paperurl: "https://doi.org/10.1186/s13059-026-04329-y"
codeurl: "https://github.com/HanwenZhu98/CellPatch"
figure:
  path: /images/publications/cellpatch.png
  width: 1418
  height: 1113
  alt: "CellPatch architecture with patch tokens, cross-attention, and different decoders for downstream tasks."
  caption: "CellPatch architecture and downstream modules"
  credit: "Fig. 1, Zhu et al. (2026)"
  license: "CC BY 4.0"
  license_url: "https://creativecommons.org/licenses/by/4.0/"
---
