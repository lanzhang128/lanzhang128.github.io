---
title: "On the Effect of Isotropy on VAE Representations of Text"
collection: publications
permalink: /publication/On-the-Effect-of-Isotropy-on-VAE-Representations-of-Text
excerpt: 'Oral Presentation. A short paper studies the effect of injecting isotropy into the representation of VAEs.'
date: 2022-05-22
venue: 'Association for Computational Linguistics (ACL)'
paperurl: 'https://aclanthology.org/2022.acl-short.78'
citation: 'Lan Zhang, Wray Buntine, and Ehsan Shareghi. 2022. On the Effect of Isotropy on VAE Representations of Text. In Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers), pages 694–701, Dublin, Ireland. Association for Computational Linguistics.'
---

**Abstract**

Injecting desired geometric properties into text representations has attracted a lot of attention. A property that has been argued for, due to its better utilisation of representation space, is isotropy. In parallel, VAEs have been successful in areas of NLP, but are known for their sub-optimal utilisation of the representation space. To address an aspect of this, we investigate the impact of injecting isotropy during training of VAEs. We achieve this by using an isotropic Gaussian posterior (IGP) instead of the ellipsoidal Gaussian posterior. We illustrate that IGP effectively encourages isotropy in the representations, inducing a more discriminative latent space. Compared to vanilla VAE, this translates into a much better classification performance, robustness to input perturbation, and generative behavior. Additionally, we offer insights about the representational properties encouraged by IGP.

This paper have a previous [preprint](https://arxiv.org/abs/2110.07383).

BibTex citation:
```
@inproceedings{zhang-etal-2022-effect,
    title = "On the Effect of Isotropy on {VAE} Representations of Text",
    author = "Zhang, Lan  and
      Buntine, Wray  and
      Shareghi, Ehsan",
    booktitle = "Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers)",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.acl-short.78",
    doi = "10.18653/v1/2022.acl-short.78",
    pages = "694--701"
}
```
