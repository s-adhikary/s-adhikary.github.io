---
title: "ZKFault: Fault attack analysis on zero-knowledge based post-quantum digital signature schemes" 
date: "2024"
tags: ["Digital signature","Zero-knowledge","Fault attack","Key recovery"]
author: "P. Mondal, S. Adhikary, S. Kundu, A. Karmakar"
description: "This paper was published in ASIACRYPT 2024" 
summary: "This paper was published in ASIACRYPT 2024" 
editPost:
    URL: "https://doi.org/10.1007/978-981-96-0944-4_5"
    Text: "Asiacrypt 2024"

---

---

##### Download

+ [Paper](https://link.springer.com/chapter/10.1007/978-981-96-0944-4_5)
+ [ePrint](https://eprint.iacr.org/2024/1422)
+ [Code and data](https://github.com/s-adhikary/zkfault_simulation)

---

##### Abstract

Computationally hard problems based on coding theory, such as the syndrome decoding problem, have been used for constructing secure cryptographic schemes for a long time. Schemes based on these problems are also assumed to be secure against quantum computers. However, these schemes are often considered impractical for real-world deployment due to large key sizes and inefficient computation time. In the recent call for standardization of additional post-quantum digital signatures by the National Institute of Standards and Technology, several code-based candidates have been proposed, including LESS, CROSS, and MEDS. These schemes are designed on the relatively new zero-knowledge framework. Although several works analyze the hardness of these schemes, there is hardly any work that examines the security of these schemes in the presence of physical attacks. 
In this work, we analyze these signature schemes from the perspective of fault attacks. All these schemes use a similar tree-based construction to compress the signature size. We attack this component of these schemes. Therefore, our attack is applicable to all of these schemes. In this work, we first analyze the LESS signature scheme and devise our attack. Furthermore, we showed how this attack can be extended to the CROSS signature scheme. Our attacks are built on very simple fault assumptions. Our results show that we can recover the entire secret key of LESS and CROSS using as little as a single fault. Finally, we propose various countermeasures to prevent these kinds of attacks and discuss their efficiency and shortcomings.

---


##### Citation

Mondal, P., Adhikary, S., Kundu, S., Karmakar, A. (2025). ZKFault: Fault Attack Analysis on Zero-Knowledge Based Post-quantum Digital Signature Schemes. In: Chung, KM., Sasaki, Y. (eds) Advances in Cryptology – ASIACRYPT 2024. ASIACRYPT 2024. Lecture Notes in Computer Science, vol 15491. Springer, Singapore. https://doi.org/10.1007/978-981-96-0944-4_5

```BibTeX
@InProceedings{10.1007/978-981-96-0944-4_5,
author="Mondal, Puja
and Adhikary, Supriya
and Kundu, Suparna
and Karmakar, Angshuman",
editor="Chung, Kai-Min
and Sasaki, Yu",
title="ZKFault: Fault Attack Analysis on Zero-Knowledge Based Post-quantum Digital Signature Schemes",
booktitle="Advances in Cryptology -- ASIACRYPT 2024",
year="2025",
publisher="Springer Nature Singapore",
address="Singapore",
pages="132--167",
abstract="Computationally hard problems based on coding theory, such as the syndrome decoding problem, have been used for constructing secure cryptographic schemes for a long time. Schemes based on these problems are also assumed to be secure against quantum computers. However, these schemes are often considered impractical for real-world deployment due to large key sizes and inefficient computation time. In the recent call for standardization of additional post-quantum digital signatures by the National Institute of Standards and Technology, several code-based candidates have been proposed, including LESS, CROSS, and MEDS. These schemes are designed on the relatively new zero-knowledge framework. Although several works analyze the hardness of these schemes, there is hardly any work that examines the security of these schemes in the presence of physical attacks. In this work, we analyze these signature schemes from the perspective of fault attacks. All these schemes use a similar tree-based construction to compress the signature size. We attack this component of these schemes. Therefore, our attack is applicable to all of these schemes. In this work, we first analyze the LESS signature scheme and devise our attack. Furthermore, we showed how this attack can be extended to the CROSS signature scheme. Our attacks are built on very simple fault assumptions. Our results show that we can recover the entire secret key of LESS and CROSS using as little as a single fault. Finally, we propose various countermeasures to prevent these kinds of attacks and discuss their efficiency and shortcomings.",
isbn="978-981-96-0944-4"
}
```

---

