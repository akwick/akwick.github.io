---
title: "Supporting Error Chains in Static Analysis for Precise Evaluation Results and Enhanced Usability" 
date: 2024-03-01
tags: ["static analysis","error chains","false positive reduction","empirical studies", "cryptographic API misuses", "API misuses"]
author: ["Anna-Katharina Wickert", "Michael Schlichtig", "Marvin Vogel", "Lukas Winter", "Mira Mezini", "Eric Bodden"]
description: "Static analyses often miss the fix location of bugs, causing false positives. Our adapted algorithm reports error chains, showing that every second project is affected by connected misuses." 
summary: "Our paper suggests an adapted algorithm that can report error chains between API misuses. The empirical study onn 471 GitHub repositories showed that 50% of projects are affected by connected cryptographic API misuses. Further, the runtime overhead is minimal, and developers appreciate the adaption."
cover:
    image: "wickert2023subsequent_feature.jpg"
    alt: "Conclusion slide of the presentation"
    relative: false
editPost:
    URL: "https://doi.org/10.1109/SANER60148.2024.00076"
    Text: "DOI"

---


- [📄 Paper](https://arxiv.org/pdf/2403.07808)
- [🔍 CogniCryptSUBS](https://github.com/CROSSINGTUD/CryptoAnalysis/tree/3.1.0)
- [💾 Artifact](https://doi.org/10.6084/m9.figshare.24473197)

---

##### Abstract

Context: Static analyses are well-established to aid in understanding bugs or vulnerabilities during the development process or in large-scale studies. A low false-positive rate is essential for the adaption in practice and for precise results of empirical studies. Unfortunately, static analyses tend to report where a vulnerability manifests rather than the fix location. This can cause presumed false positives or imprecise results. 
Method: To address this problem, we designed an adaption of an existing static analysis algorithm that can distinguish between a manifestation and fix location, and reports error chains. An error chain represents at least two interconnected errors that occur successively, thus building the connection between the fix and manifestation location. We used our tool CogniCryptSUBS for a case study on 471 GitHub repositories, a performance benchmark to compare different analysis con- figurations, and conducted an expert interview. 
Result: We found that 50% of the projects with a report had at least one error chain. Our runtime benchmark demonstrated that our improvement caused only a minimal runtime overhead of less than 4%. The results of our expert interview indicate that with our adapted version participants require fewer executions of the analysis. 
Conclusion: Our results indicate that error chains occur frequently in real-world projects, and ignoring them can lead to imprecise evaluation results. The runtime benchmark indicates that our tool is a feasible and efficient solution for detecting error chains in real-world projects. Further, our results gave a hint that the usability of static analyses may
benefit from supporting error chains.


---

##### Citation

**Anna-Katharina Wickert**, Michael Schlichtig, Marvin Vogel, Lukas Winter, Mira Mezini, and Eric Bodden. “Supporting Error Chains in Static Analysis for Precise Evaluation Results and Enhanced Usability.” In: *2024 IEEE 31th International Conference on Software Analysis, Evolution and Reengineering (SANER)*. DOI: [10.1109/SANER60148.2024.00076](https://doi.org/10.1109/SANER60148.2024.00076).

```BibTeX
@inproceedings{wickert2023supporting,
	title = {Supporting {Error} {Chains} in {Static} {Analysis} for {Precise} {Evaluation} {Results} and {Enhanced} {Usability}},
	booktitle = {2024 {IEEE} 31th {International} {Conference} on {Software} {Analysis}, {Evolution} and {Reengineering} ({SANER})},
	author = {Wickert, Anna-Katharina and Schlichtig, Michael and Vogel, Marvin and Winter, Lukas and Mezini, Mira and Bodden, Eric},
	doi = {10.1109/SANER60148.2024.00076},
}
```

---

##### Related material

+ [⛏️ Repository Miner](https://github.com/marvinvo/Repository_Miner)
+ [🐞 Initial Implementation and Rules](https://github.com/marvinvo/CryptoAnalysis)