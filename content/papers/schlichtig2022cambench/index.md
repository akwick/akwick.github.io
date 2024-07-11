---
title: "CamBench - Cryptographic API Misuse Detection Tool Benchmark Suite" 
date: 2022-05-19
author: ["Michael Schlichtig", "Anna-Katharina Wickert", "Stefan Krüger", "Eric Bodden", "Mira Mezini"]
description: "The suggested benchmark suite CamBench to provide a novel approach to compare the capabilities of cryptographic API misuse detection tools." 
summary: "So far, benchmarks for cryptographic API misuses only focused on a subset of issues or tools. To drive future development in this domain, we will openly generate a benchmark. We will derive the generation of this novel benchmark from best practices."
cover:
    image: "featured.jpg"
    alt: "Last slide of the talk and an overview of the work."
    relative: false
#editPost:
#    URL: "https://arxiv.org/pdf/2204.06447"
#    Text: "DOI"

---

- [Paper arXiv](https://arxiv.org/pdf/2204.06447)
- [Code](https://github.com/CROSSINGTUD/CamBench)

---

##### Abstract

*Context*
Cryptographic APIs are often misused in real-world applications. Therefore, many cryptographic API misuse detection tools have been introduced. However, there exists no established reference benchmark for a fair and comprehensive comparison and evaluation of these tools. While there are benchmarks, they often only address a subset of the domain or were only used to evaluate a subset of existing misuse detection tools.
*Objective*
To fairly compare cryptographic API misuse detection tools and to drive future development in this domain, we will devise such a benchmark. Openness and transparency in the generation process are key factors to fairly generate and establish the needed benchmark.
*Method*
We propose an approach where we derive the benchmark generation methodology from the literature which consists of general best practices in benchmarking and domain-specific benchmark generation. A part of this methodology is transparency and openness of the generation process, which is achieved by pre-registering this work. Based on our methodology we design CamBench, a fair "Cryptographic API Misuse Detection Tool Benchmark Suite". We will implement the first version of CamBench limiting the domain to Java, the JCA, and static analyses. Finally, we will use CamBench to compare current misuse detection tools and compare CamBench to related benchmarks of its domain.

---

##### Citation

Wickert, Anna-Katharina, Lars Baumgärtner, Michael Schlichtig, Krishna Narasimhan, and Mira Mezini. ‘To Fix or Not to Fix: A Critical Study of Crypto-Misuses in the Wild’. In {IEEE} International Conference on Trust, Security and Privacy in Computing and Communications, TrustCom 2022, Wuhan, China, December 9-11, 2022, 315--322. IEEE, 2022. https://doi.org/10.1109/TRUSTCOM56396.2022.00051.


```BibTeX
@misc{schlichtig2022cambench,
	title = {{CamBench} -- {Cryptographic} {API} {Misuse} {Detection} {Tool} {Benchmark} {Suite}},
	copyright = {All rights reserved},
	url = {http://arxiv.org/abs/2204.06447},
	publisher = {arXiv},
	author = {Schlichtig, Michael and Wickert, Anna-Katharina and Krüger, Stefan and Bodden, Eric and Mezini, Mira},
	month = apr,
	year = {2022},
	note = {accepted at the MSR 2022 Registered Reports Track as In-Principal Acceptance (IPA), ranked A in CORE21},
	keywords = {Computer Science - Software Engineering},
	annote = {Comment: 8 pages, accepted at the MSR 2022 Registered Reports Track as a In-Principal Acceptance (IPA)},
}
```

---

##### Related material

+ [Presentation slides - Virtual MSR](https://github.com/CROSSINGTUD/CamBench/blob/main/presentations/2022_05_19_MSR_CamBench.pdf)
+ [Presentation slides - In-person MSR](https://github.com/CROSSINGTUD/CamBench/blob/main/presentations/2022_05_24_MSR_CamBench.pdf)
+ [Poster - In-person MSR](https://github.com/CROSSINGTUD/CamBench/blob/main/presentations/2022_05_23_MSR_CamBench_Poster.pdf)
+ [CamBench REAL](https://github.com/CROSSINGTUD/CamBench/tree/main/CamBench_Real)
+ [Logo](https://github.com/CROSSINGTUD/CamBench/tree/main/logos)