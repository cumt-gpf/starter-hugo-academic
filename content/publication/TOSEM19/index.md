---
abstract: Power side-channel attacks, capable of deducing secret data using statistical analysis, have become a serious threat. Random masking is a widely used countermeasure for removing the statistical dependence between secret data and side-channel information. Although there are techniques for verifying whether a piece of software code is perfectly masked, they are limited in accuracy and scalability. To bridge this gap, we propose a refinement-based method for verifying masking countermeasures. Our method is more accurate than prior type-inference-based approaches and more scalable than prior model-counting-based approaches using SAT or SMT solvers. Indeed, our method can be viewed as a gradual refinement of a set of type-inference rules for reasoning about distribution types. These rules are kept abstract initially to allow fast deduction and then made concrete when the abstract version is not able to resolve the verification problem. We also propose algorithms for quantifying the amount of side-channel information leakage from a software implementation using the notion of quantitative masking strength. We have implemented our method in a software tool and evaluated it on cryptographic benchmarks including AES and MAC-Keccak. The experimental results show that our method significantly outperforms state-of-the-art techniques in terms of accuracy and scalability.
# slides: example
url_pdf: ""
publication_types:
  - "2"
authors:
  - admin 
  - Jun Zhang 
  - Fu Song
  - Chao Wang 
publication: In *ACM Transactions on Software Engineering and Methodology 2019*
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
url_dataset: ""
url_project: ""
publication_short: In *ACM TOSEM 2019*
url_source: ""
url_video: ""
title: "Verifying and Quantifying Side-channel Resistance of Masked Software Implementations"
doi: ""
featured: false
tags: []
# projects:
#   - example
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#   focal_point: ""
#   preview_only: false
date: 2019-07-01T00:00:00.000Z
url_slides: ""
# publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

