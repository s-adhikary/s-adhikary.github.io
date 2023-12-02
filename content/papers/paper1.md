---
title: "A Fast RLWE-based IPFE Library and its Application to Privacy-preserving Biometric Authentication" 
date: "2023"
tags: ["Number theoretic transformation","Inner product functional encryption","OpenMP","AVX2","Privacy-preserving biometric authentication"]
author: "S. Adhikary, A. Karmakar"
description: "This paper was published in IEEE Transactions on Emerging Topics in Computing" 
summary: "This paper was published in IEEE Transactions on Emerging Topics in Computing (2023)" 
editPost:
    URL: "https://doi.org/10.1109/TETC.2023.3268003"
    Text: "IEEE Transactions on Emerging Topics in Computing"

---

---

##### Download

+ [Paper](https://ieeexplore.ieee.org/document/10106755)
+ [ePrint](https://eprint.iacr.org/2023/721.pdf)
+ [Code and data](https://github.com/s-adhikary/IPFE)

---

##### Abstract

With the increased use of data and communication through the internet and the abundant misuse of personal data by many organizations, people are more sensitive about their privacy. Privacy-preserving computation is becoming increasingly important in this era. Functional encryption allows a user to evaluate a function on encrypted data without revealing sensitive information. Most implementations of functional encryption schemes are too time-consuming for practical use. Mera et al. first proposed an inner product functional encryption scheme based on ring learning with errors to improve efficiency. In this work, we optimize the implementation of their work and propose a fast inner product functional encryption library. Specifically, we identify the main performance bottleneck, which is the number theoretic transformation based polynomial multiplication used in the scheme. We also identify the micro and macro level parallel components of the scheme and propose novel techniques to improve the efficiency using open multi-processing and advanced vector extensions 2 vector processor. Compared to the original implementation, our optimization methods translate to 89.72%, 83.06%, 59.30%, and 53.80% improvements in the Setup , Encrypt , KeyGen , and Decrypt operations respectively, in the scheme for standard security level. Designing privacy-preserving applications using functional encryption is ongoing research. Therefore, as an additional contribution to this work, we design a privacy-preserving biometric authentication scheme using inner product functional encryption primitives.

---


##### Citation

S. Adhikary and A. Karmakar, "A Fast RLWE-based IPFE Library and its Application to Privacy-preserving Biometric Authentication," in IEEE Transactions on Emerging Topics in Computing, doi: 10.1109/TETC.2023.3268003.

```BibTeX
@ARTICLE{10106755,
  author={Adhikary, Supriya and Karmakar, Angshuman},
  journal={IEEE Transactions on Emerging Topics in Computing}, 
  title={A Fast RLWE-based IPFE Library and its Application to Privacy-preserving Biometric Authentication}, 
  year={2023},
  volume={},
  number={},
  pages={1-13},
  doi={10.1109/TETC.2023.3268003}}
```

---

