---
title: "A Dataset of Parametric Cryptographic Misuses" 
date: 2019-05-27
author: ["Anna-Katharina Wickert", "Michael Reif", "Michael Eichberg", "Anam Dodhy", "Mira Mezini"]
description: "88-95% of apps using crypto APIs are insecure. Our dataset of 201 real-world misuses aids research & detection tool evaluation" 
summary: "Cryptographic APIs are often misused. Our dataset of 201 real-world misuses aids research & tool evaluation that aim to mitigate cryptographic API misuses. "
cover:
    image: "featured.png"
    alt: "Last slide of the talk and an overview of the work."
    relative: false
editPost:
    URL: "https://doi.org/10.1109/MSR.2019.00023"
    Text: "DOI"

---

+ [Benchmark](https://github.com/akwick/MUBench/tree/thesis-2018-anam-dodhy)
+ [Presentation slides](2019_05_27_MSR_A-dataset-of-parametric-cryptographic-misuses.pdf)

---

##### Abstract

Cryptographic APIs (Crypto APIs) provide the foundations for the development of secure applications. Unfortunately, most applications do not use Crypto APIs securely and end up being insecure, e.g., by the usage of an outdated algorithm, a constant initialization vector, or an inappropriate hashing algorithm. Two different studies have recently shown that 88% to 95% of those applications using Crypto APIs are insecure due to misuses. To facilitate further research on these kinds of misuses, we created a collection of 201 misuses found in real-world applications along with a classification of those misuses. In the provided dataset, each misuse consists of the corresponding open-source project, the project's build information, a description of the misuse, and the misuse's location. Further, we integrated our dataset into MUBench, a benchmark for API misuse detection. Our dataset provides a foundation for research on Crypto API misuses. For example, it can be used to evaluate the precision and recall of detection tools, as a foundation for studies related to Crypto API misuses, or as a training set.

---


##### Citation

Wickert, Anna-Katharina, Michael Reif, Michael Eichberg, Anam Dodhy, and Mira Mezini. ‘A Dataset of Parametric Cryptographic Misuses’. In Proceedings of the 16th International Conference on Mining Software                   Repositories, MSR 2019, 26-27 May 2019, Montreal, Canada, IEEE / ACM, 2019. https://doi.org/10.1109/MSR.2019.00023.


```BibTeX
@inproceedings{wickert2019dataset,
	title = {A {Dataset} of {Parametric} {Cryptographic} {Misuses}},
	url = {https://doi.org/10.1109/MSR.2019.00023},
	doi = {10.1109/MSR.2019.00023},
	booktitle = {Proceedings of the 16th {International} {Conference} on {Mining} {Software} {Repositories}, {MSR} 2019, 26-27 {May} 2019, {Montreal}, {Canada}},
	publisher = {IEEE} / {ACM},
	author = {Wickert, Anna-Katharina and Reif, Michael and Eichberg, Michael and Dodhy, Anam and Mezini, Mira},
	editor = {Storey, MargaretAnne D. and Adams, Bram and Haiduc, Sonia},
	year = {2019},
}

```