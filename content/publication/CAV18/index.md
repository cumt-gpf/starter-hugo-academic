---
abstract: Power side-channel attacks, capable of deducing secret using statistical analysis techniques, have become a serious threat to devices in cyber-physical systems and the Internet of things. Random masking is a widely used countermeasure for removing the statistical dependence between secret data and sidechannel leaks. Although there are techniques for verifying whether software code has been perfectly masked, they are limited in accuracy and scalability. To bridge this gap, we propose a reﬁnement-based method for verifying masking countermeasures. Our method is more accurate than prior syntactic type inference based approaches and more scalable than prior model-counting based approaches using SAT or SMT solvers. Indeed, it can be viewed as a gradual reﬁnement of a set of semantic type inference rules for reasoning about distribution types. These rules are kept abstract initially to allow fast deduction, and then made concrete when the abstract version is not able to resolve the veriﬁcation problem. We have implemented our method in a tool and evaluated it on cryptographic benchmarks including AES and MAC-Keccak. The results show that our method signiﬁcantly outperforms state-of-the-art techniques in terms of both accuracy and scalability.
# slides: example
url_pdf: ""
publication_types:
  - "1"
authors:
  - Jun Zhang
  - admin
  - Fu Song
  - Chao Wang 
publication: In *30th International Conference on Computer Aided Verification*
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
url_dataset: ""
url_project: ""
publication_short: In *the proceedings of CAV 2018*
url_source: ""
url_video: ""
title: "SCInfer: Refinement-based Verification of Software Countermeasures
  against Side-Channel Attacks"
doi: ""
featured: false
tags: []
# projects:
#   - example
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#   focal_point: ""
#   preview_only: false
date: 2018-07-01T00:00:00.000Z
url_slides: ""
# publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

