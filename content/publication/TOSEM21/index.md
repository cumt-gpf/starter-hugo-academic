---
abstract: Side-channel attacks, which are capable of breaking secrecy via side-channel information, pose a growing threat to the implementation of cryptographic algorithms. Masking is an effective countermeasure against side-channel attacks by removing the statistical dependence between secrecy and power consumption via randomization. However, designing efficient and effective masked implementations turns out to be an error-prone task. Current techniques for verifying whether masked programs are secure are limited in their applicability and accuracy, especially when they are applied. To bridge this gap, in this article, we first propose a sound type system, equipped with an efficient type inference algorithm, for verifying masked arithmetic programs against higher-order attacks. We then give novel model-counting-based and pattern-matching-based methods that are able to precisely determine whether the potential leaky observable sets detected by the type system are genuine or simply spurious. We evaluate our approach on various implementations of arithmetic cryptographic programs. The experiments confirm that our approach outperforms the state-of-the-art baselines in terms of applicability, accuracy, and efficiency.
# slides: example
url_pdf: ""
publication_types:
  - "2"
authors:
  - admin
  - Hongyi Xie
  - Fu Song
  - Taolue Chen 
publication: In *ACM Transactions on Software Engineering and Methodology 2021*
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
url_dataset: ""
url_project: ""
publication_short: In *ACM TOSEM 2021*
url_source: ""
url_video: ""
title: "A Hybrid Approach to Formal Verification of Higher-Order Masked Arithmetic Programs"
doi: ""
featured: false
tags: []
# projects:
#   - example
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#   focal_point: ""
#   preview_only: false
date: 2021-02-01T00:00:00.000Z
url_slides: ""
# publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

