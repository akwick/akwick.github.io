---
title: "Python crypto misuses in the wild" 
date: 2021-10-01
url: /paper/wickert2021python
tags: ["API misuses","cryptography","security", "static analysis", "empirical studies"]
author: ["Anna-Katharina Wickert", "Lars Baumgärtner", "Florian Breitfelder", "Mira Mezini"]
description: "Cryptographic APIs are often misused. Our empirical study of over 900 Python and MicroPython projects shows that 52% of the projects have misuses." 
summary: "Our study analyzes cryptographic API misuses in over 900 Python and MicroPython projects, revealing that 52% of the projects have at least one misuse. The findings indicate a positive impact of good API design in reducing misuses compared to Java and C."
cover:
    image: "/wickert2021python_feature.jpg"
    alt: "Conclusion slide of the presentation"
    relative: false

---

---

- [📄 Paper arXiv](https://arxiv.org/pdf/2109.01109)
- [📄 Paper ACM](https://dl.acm.org/doi/10.1145/3475716.3484195)
- [💾 Artifact](https://doi.org/10.6084/m9.figshare.16499085)

---

##### Abstract

**Background:** Previous studies have shown that up to 99.59 % of the Java apps using crypto APIs misuse the API at least once. However, these studies have been conducted on Java and C, while empirical studies for other languages are missing. For example, a controlled user study with crypto tasks in Python has shown that 68.5 % of the professional developers write a secure solution for a crypto task. 
**Aims:** To understand if this observation holds for real-world code, we conducted a study of crypto misuses in Python. 
**Method:** We developed a static analysis tool that covers common misuses of 5 different Python crypto APIs. With this analysis, we analyzed 895 popular Python projects from GitHub and 51 MicroPython projects for embedded devices. Further, we compared our results with the findings of previous studies. 
**Results:** Our analysis reveals that 52.26 % of the Python projects have at least one misuse. Further, some Python crypto libraries’ API design helps developers from misusing crypto functions, which were much more common in studies conducted with Java and C code. 
**Conclusion:** We conclude that we can see a positive impact of the good API design on crypto misuses for Python applications. Further, our analysis of MicroPython projects reveals the importance of hybrid analyses.

---

##### Citation

**Anna-Katharina Wickert**, Lars Baumgärtner, Florian Breitfelder, and Mira Mezini. “Python crypto misuses in the wild.” In: *15th ACM/IEEE international symposium on empirical software engineering and measurement (ESEM)*. 2021. DOI: [10.1145/3475716.3484195](https://doi.org/10.1145/3475716.3484195).

```BibTeX
@inproceedings{wickert2021python,
	title = {Python crypto misuses in the wild},
	booktitle = {15th {ACM}/{IEEE} international symposium on empirical software engineering and measurement ({ESEM})},
	author = {Wickert, Anna-Katharina and Baumgärtner, Lars and Breitfelder, Florian and Mezini, Mira},
	year = {2021},
	doi = {10.1145/3475716.3484195},
}
```

---

##### Related material

+ [🔍 Implementation](https://doi.org/10.6084/m9.figshare.16538568)
+ [🗣️ Presentation on YouTube](https://www.youtube.com/live/6rSBH6F6A64?si=6OKyRKHoNmcxUjep)