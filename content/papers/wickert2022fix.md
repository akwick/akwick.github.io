---
title: "To Fix or Not to Fix: A Critical Study of Crypto-misuses in the Wild" 
date: 2022-12-09
url: /paper/
author: ["Anna-Katharina Wickert", "Lars Baumgärtner", "Michael Schlichtig", "Krishna Narasimhan", "Mira Mezini"]
description: "Empirial study of cryptographic misuses that identified several potential effective false positives." 
summary: "Empirial study of cryptographic misuses on enterprise-driven applications that identified several potential effective false positives, such as the use of hash algorithms in a non-security context. Further, we introduced a theoretical model of vulnerabilities caused by API misuses."
editPost:
    URL: "https://doi.org/10.1109/TrustCom56396.2022.00051"
    Text: "DOI"

---

---

##### Download:

- [Paper arXiv](https://arxiv.org/abs/2209.11103)
- [Data](https://figshare.com/articles/software/To_Fix_or_Not_to_Fix_A_Critical_Study_of_Crypto-misuses_in_the_Wild/21178243)

---

##### Abstract

Recent studies have revealed that 87 % to 96 % of the Android apps using cryptographic APIs have a misuse which may cause security vulnerabilities. As previous studies did not conduct a qualitative examination of the validity and severity of the findings, our objective was to understand the findings in more depth. We analyzed a set of 936 open-source Java applications for cryptographic misuses. Our study reveals that 88.10 % of the analyzed applications fail to use cryptographic APIs securely. Through our manual analysis of a random sample, we gained new insights into effective false positives. For example, every fourth misuse of the frequently misused JCA class MessageDigest is an effective false positive due to its occurrence in a non-security context. As we wanted to gain deeper insights into the security implications of these misuses, we created an extensive vulnerability model for cryptographic API misuses. Our model includes previously undiscussed attacks in the context of cryptographic APIs such as DoS attacks. This model reveals that nearly half of the misuses are of high severity, e.g., hard-coded credentials and potential Man-in-the-Middle attacks.

---

##### Figure X:  Figure title

![](/figurex.png)

---

##### Citation

Wickert, Anna-Katharina, Lars Baumgärtner, Michael Schlichtig, Krishna Narasimhan, and Mira Mezini. ‘To Fix or Not to Fix: A Critical Study of Crypto-Misuses in the Wild’. In {IEEE} International Conference on Trust, Security and Privacy in Computing and Communications, TrustCom 2022, Wuhan, China, December 9-11, 2022, 315--322. IEEE, 2022. https://doi.org/10.1109/TRUSTCOM56396.2022.00051.


```BibTeX
@inproceedings{wickert2022fix,
	title = {To {Fix} or {Not} to {Fix}: {A} {Critical} {Study} of {Crypto}-misuses in the {Wild}},
	shorttitle = {To {Fix} or {Not} to {Fix}},
	url = {https://doi.org/10.1109/TrustCom56396.2022.00051},
	doi = {10.1109/TRUSTCOM56396.2022.00051},
	booktitle = {{IEEE} {International} {Conference} on {Trust}, {Security} and {Privacy} in {Computing} and {Communications}, {TrustCom} 2022, {Wuhan}, {China}, {December} 9-11, 2022},
	publisher = {IEEE},
	author = {Wickert, Anna-Katharina and Baumgärtner, Lars and Schlichtig, Michael and Narasimhan, Krishna and Mezini, Mira},
	year = {2022},
	pages = {315--322},
}
```

---

##### Related material

+ [Presentation slides](/presentation.pdf)