# saasn-stain-normalization

Pytorch implementation of Self-Attentive Adversarial Stain Normalization | [arxiv](https://arxiv.org/abs/1909.01963)

Shrivastava, A., Adorno, W., Ehsan, L., Ali, S.A., Moore, S.R., Amadi, B.C., Kelly, P., Brown, D.E. and Syed, S., 2019. Self-Attentive Adversarial Stain Normalization. arXiv preprint arXiv:1909.01963.

> Hematoxylin and Eosin (H&E) stained Whole Slide Images (WSIs) are utilized for biopsy visualization-based diagnostic and prognostic assessment of diseases. Variation in the H&E staining process across different lab sites can lead to significant variations in biopsy image appearance. These variations introduce an undesirable bias when the slides are examined by pathologists or used for training deep learning models. To reduce this bias, slides need to be translated to a common domain of stain appearance before analysis. We propose a Self-Attentive Adversarial Stain Normalization (SAASN) approach for the normalization of multiple stain appearances to a common domain. This unsupervised generative adversarial approach includes self-attention mechanism for synthesizing images with finer detail while preserving the structural consistency of the biopsy features during translation. SAASN demonstrates consistent and superior performance compared to other popular stain normalization techniques on H&E stained duodenal biopsy image data.
