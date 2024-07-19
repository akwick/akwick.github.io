---
title: "UNGOML: Automated Classification of unsafe Usages in Go" 
date: 2023-05-01
tags: ["graph neural networks", "Go", "unsafe API",
"classification", "API-misuse", "award"]
author: ["Anna-Katharina Wickert", "Clemens Damke", "Lars Baumgärtner", "Eyke Hüllermeier", "Mira Mezini"]
description: "UNGOML, an automated classifier for Go's unsafe package, uses deep learning to identify the purpose of unsafe usages, achieving over 86% accuracy in classification." 
summary: "UNGOML, an automated classifier for Go's unsafe package, uses deep learning to classify the purpose of unsafe usages. It achieves over 86% accuracy, aiding in tasks like refactoring and security audits by identifying what is done with the unsafe package and why."
cover:
    image: "/wickert2023ungoml_feature.jpg"
    alt: "Conclusion slide of presentation"
    relative: false
---

---

- [📄 Paper arXiv](https://arxiv.org/pdf/2306.00694)
- [📄 Paper IEEExplore](https://ieeexplore.ieee.org/document/10174087)
- [💾 Artifact](https://dx.doi.org/10.6084/m9.figshare.22293052)

---

##### Abstract

The Go programming language offers strong protection from memory corruption. As an escape hatch of these protections, it provides the unsafe package. Previous studies identified that this unsafe package is frequently used in real-world code for several purposes, e.g., serialization or casting types. Due to the variety of these reasons, it may be possible to refactor specific usages to avoid potential vulnerabilities. However, the classification of unsafe usages is challenging and requires the context of the call and the program's structure. In this paper, we present the first automated classifier for unsafe usages in Go, UNGOML, to identify what is done with the unsafe package and why it is used. For UNGOML, we built four custom deep learning classifiers trained on a manually labeled data set. We represent Go code as enriched control-flow graphs (CFGs) and solve the label prediction task with one single-vertex and three context-aware classifiers. All three context-aware classifiers achieve a top-1 accuracy of more than 86% for both dimensions, WHAT and WHY. Furthermore, in a set-valued conformal prediction setting, we achieve accuracies of more than 93% with mean label set sizes of 2 for both dimensions. Thus, UNGOML can be used to efficiently filter unsafe usages for use cases such as refactoring or a security audit. 

---

##### Citation

**Anna-Katharina Wickert**, Clemens Damke, Lars Baumgärt- ner, Eyke Hüllermeier, and Mira Mezini. “UNGOML: Automated Classification of unsafe Usages in Go.” In: *2023 IEEE/ACM 20th International Conference on Mining Software Repositories (MSR)*.  2023. DOI: [10.1109/MSR59073.2023.00050](https://doi.org/10.1109/MSR59073.2023.00050).

```BibTeX
@inproceedings{wickert2023ungoml,
	title = {{UNGOML}: {Automated} {Classification} of unsafe {Usages} in {Go}},
	booktitle = {2023 {IEEE}/{ACM} 20th {International} {Conference} on {Mining} {Software} {Repositories} ({MSR})},
	author = {Wickert, Anna-Katharina and Damke, Clemens and Baumgärtner, Lars and Hüllermeier, Eyke and Mezini, Mira},
	year = {2023},
	doi = {10.1109/MSR59073.2023.00050},
}
```

---

##### Related material

+ [🔍 UnGoML](https://github.com/stg-tud/ungoml)