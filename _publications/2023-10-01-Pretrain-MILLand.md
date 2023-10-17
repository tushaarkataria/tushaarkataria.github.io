---
title: "To Pretrain or Not to Pretrain? A Case Study of Domain-Specific Pretraining for Semantic Segmentation in Histopathology"
collection: publications
permalink: /publication/2023-10-01-Pretrain-MILLand
excerpt: 'Annotating medical imaging datasets is costly, so fine-tuning (or transfer learning) is the most effective method for digital pathology vision applications such as disease classification and semantic segmentation. However, due to texture bias in models trained on real-world images, transfer learning for histopathology applications might result in underperforming models, which necessitates the need for using unlabeled histopathology data and self-supervised methods to discover domain-specific characteristics. Here, we tested the premise that histopathology-specific pretrained models provide better initializations for pathology vision tasks, i.e., gland and cell segmentation. In this study, we compare the performance of gland and cell segmentation tasks with histopathology domain-specific and non-domain-specific (real-world images) pretrained weights. Moreover, we investigate the dataset size at which domain-specific pretraining produces significant gains in performance. In addition, we investigated whether domain-specific initialization improves the effectiveness of out-of-distribution testing on distinct datasets but the same task. The results indicate that performance gain using domain-specific pretrained weights depends on both the task and the size of the training dataset. In instances with limited dataset sizes, a significant improvement in gland segmentation performance was also observed, whereas models trained on cell segmentation datasets exhibit no improvement'
 
date: 2023-10-08
venue: 'Medical Image Learning with Limited and Noisy Data'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-44917-8_24'
archive: https://arxiv.org/abs/2307.03275
citation: 'Kataria, T., Knudsen, B., Elhabian, S. (2023). To Pretrain or Not to Pretrain? A Case Study of Domain-Specific Pretraining for Semantic Segmentation in Histopathology. In: Xue, Z., et al. Medical Image Learning with Limited and Noisy Data. MILLanD 2023. Lecture Notes in Computer Science, vol 14307. Springer, Cham. https://doi.org/10.1007/978-3-031-44917-8_24'
---
