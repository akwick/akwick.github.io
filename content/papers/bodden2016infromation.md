---
title: "Information Flow Analysis for Go" 
date: 2016-10-05
tags: ["static analysis","information flow","go"]
author: [Eric Bodden, Ka I. Pun, Martin Steffen, Volker Stolz, Anna-Katharina Wickert]
description: "State-of-the-art information flow analyses for Go apps, exploring future directions for runtime use, precision, and optimizations, with a focus on closures and channels." 
summary: "This paper presents current information flow analyses for Go applications, discussing future uses of static analysis at runtime to enhance precision and optimize checks. It focuses on unique Go features like closures and message-based communication via channels"
---

---

- [📄 Paper Springer](https://link.springer.com/chapter/10.1007/978-3-319-47166-2_30)
- [📄 Paper](https://martinsteffen.github.io/assets/download/16/informationflowgo.pdf)

---

##### Abstract

We present the current state of the art of information flow analyses for Go applications. Based on our findings, we discuss future directions of where static analysis information can be used at runtime to for example achieve higher precision, or optimise runtime checks. We focus specifically on outstanding language features such as closures and message-based communication via channels.


---

##### Citation

Eric Bodden, Ka I Pun, Martin Steffen, Volker Stolz, and **Anna-Katharina Wickert**. “Information flow analysis for go.” In: *Leveraging applications of formal methods, verification and validation: Foundational techniques: 7th international symposium (ISoLA)*. Springer International Publishing Cham, 2016. DOI: [10.1007/978-3-319-47166-2_30](https://doi.org/10.1007/978-3-319-47166-2_30).

```BibTeX
@inproceedings{bodden2016information,
	title = {Information flow analysis for go},
	booktitle = {Leveraging applications of formal methods, verification and validation: {Foundational} techniques: 7th international symposium (ISoLA)},
	publisher = {Springer International Publishing Cham},
	author = {Bodden, Eric and Pun, Ka I and Steffen, Martin and Stolz, Volker and Wickert, Anna-Katharina},
	year = {2016},
    doi = {10.1007/978-3-319-47166-2\_30},
}
```

---
