---
abstract: Cryptographic algorithms are widely used to protect data privacy in many aspects of daily lives from smart card to cyber-physical systems. Unfortunately, programs implementing cryptographic algorithms may be vulnerable to practical power side-channel attacks, which may infer private data via statistical analysis of the correlation between power consumptions of an electronic device and private data. To thwart these attacks, several masking schemes have been proposed, giving rise to effective countermeasures for reducing the statistical correlation between private data and power consumptions. However, programs that rely on secure masking schemes are not secure a priori. Indeed, designing effective masking programs is a labor intensive and error-prone task. Although some techniques have been proposed for formally verifying masking countermeasures and for quantifying masking strength, they are currently limited to Boolean programs and suffer from low accuracy. In this work, we propose an approach for formally verifying masking countermeasures of arithmetic programs. Our approach is more accurate for arithmetic programs and more scalable for Boolean programs comparing to the existing approaches. It is essentially a synergistic integration of type inference and model-counting based methods, armed with domain speciﬁc heuristics. The type inference system allows a fast deduction of leakage-freeness of most intermediate computations, the model-counting based methods accounts for completeness, namely, to eliminate spurious flaws, and the heuristics facilitate both type inference and model-counting based reasoning, which improve scalability and efﬁciency in practice. In case that the program does contain leakage, we provide a method to quantify its masking strength. A distinguished feature of our type system lies in its support of compositional reasoning when verifying programs with procedure calls, so the need of inlining procedures can be signiﬁcantly reduced. We have implemented our methods in a veriﬁcation tool QMVERIF which has been extensively evaluated on cryptographic benchmarks including full AES, DES and MAC-Keccak. The experimental results demonstrate the effectiveness and efﬁciency of our approach, especially for compositional reasoning. In particular, our tool is able to automatically prove leakage-freeness of arithmetic programs for which only manual proofs exist so far; it is also significantly faster than the state-of-the-art tools EasyCrypt on common arithmetic programs, QMSINFER, SC Sniffer and maskVerif on Boolean programs.
# slides: example
url_pdf: ""
publication_types:
  - "2"
authors:
  - admin
  - Hongyi Xie 
  - Pu Sun 
  - Jun Zhang
  - Fu Song
  - Taolue Chen 
publication: In *IEEE Transactions on Software Engineering 2020*
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
#   tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
#   condimentum.
url_dataset: ""
url_project: ""
publication_short: In *IEEE TSE 2020*
url_source: ""
url_video: ""
title: "Formal Veriﬁcation of Masking Countermeasures for Arithmetic Programs"
doi: ""
featured: false
tags: []
# projects:
#   - example
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#   focal_point: ""
#   preview_only: false
date: 2020-07-01T00:00:00.000Z
url_slides: ""
# publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

