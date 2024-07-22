---
title: "Algebraic Replicated Data Types: Programming Secure Local-First Software date" 
date: 2023-07-17
tags: ["local-first","data privacy","coordination freedom","CRDTs","AEAD"]
author: [Christian Kuessner, Ragnar Mogk, Anna-Katharina Wickert, Mira Mezini]
description: "Programming support for local-first apps: automatic synchronization and end-to-end encryption using algebraic data types, ensuring privacy, integrity, and consistency." 
summary: "This paper presents programming support for local-first applications, enabling automatic synchronization and end-to-end encryption using algebraic data types. It addresses challenges in availability, privacy, and security, ensuring data integrity and eventual consistency without complex solutions."
---

---

- [📄 Paper](https://drops.dagstuhl.de/storage/00lipics/lipics-vol263-ecoop2023/LIPIcs.ECOOP.2023.14/LIPIcs.ECOOP.2023.14.pdf)
- [💾 Artifact](https://archive.softwareheritage.org/browse/directory/9d1f296a61ad08d53d81f8e8042373e82d0a3e84/?origin_url=https://github.com/rescala-lang/REScala&revision=b3498f4b2ada20e199845b1488cca8ada0573f38&snapshot=4af071843b6301542798be9e0d535750fbd4f322)
- [🔍 Code](https://github.com/rescala-lang/REScala)

---

##### Abstract

This paper is about programming support for local-first applications that manage private data locally, but still synchronize data between multiple devices. Typical use cases are synchronizing settings and data, and collaboration between multiple users. Such applications must preserve the privacy and integrity of the user’s data without impeding or interrupting the user’s normal workflow – even when the device is offline or has a flaky network connection.
From the programming perspective, availability along with privacy and security concerns pose significant challenges, for which developers have to learn and use specialized solutions such as conflict-free replicated data types (CRDTs) or APIs for centralized data stores. This work relieves developers from this complexity by enabling the direct and automatic use of algebraic data types – which developers already use to express the business logic of the application – for synchronization and collaboration. Moreover, we use this approach to provide end-to-end encryption and authentication between multiple replicas (using a shared secret), that is suitable for a coordination-free setting. Overall, our approach combines all the following advantages: it (1) allows developers to design custom data types, (2) provides data privacy and integrity when using untrusted intermediaries, (3) is coordination free, (4) guarantees eventual consistency by construction (i.e., independent of developer errors), (5) does not cause indefinite growth of metadata, (6) has sufficiently efficient implementations for the local-first setting.

---

##### Citation

Christian Kuessner, Ragnar Mogk, **Anna-Katharina Wickert**, and Mira Mezini. “Algebraic Replicated Data Types: Program- ming Secure Local-First Software.” In: *37th European Conference on Object-Oriented Programming (ECOOP 2023)*. Leibniz International Proceedings in Informatics (LIPIcs). Schloss Dagstuhl – Leibniz-Zentrum für Informatik, 2023. DOI: [10.4230/LIPICS.ECOOP.2023.14](https://doi.org/10.4230/LIPICS.ECOOP.2023.14).

```BibTeX
@inproceedings{kuessner2023algebraic,
	series = {Leibniz {International} {Proceedings} in {Informatics} ({LIPIcs})},
	title = {Algebraic {Replicated} {Data} {Types}: {Programming} {Secure} {Local}-{First} {Software}},
	shorttitle = {Algebraic {Replicated} {Data} {Types}},
	booktitle = {37th {European} {Conference} on {Object}-{Oriented} {Programming} ({ECOOP} 2023)},
	publisher = {Schloss Dagstuhl – Leibniz-Zentrum für Informatik},
	author = {Kuessner, Christian and Mogk, Ragnar and Wickert, Anna-Katharina and Mezini, Mira},
	year = {2023},
	doi = {10.4230/LIPICS.ECOOP.2023.14},
}
```
```BibTeX
@article{kuessner2023algebraicartifact,
	title = {Algebraic {Replicated} {Data} {Types}: {Programming} {Secure} {Local}-{First} {Software} ({Artifact})},
	volume = {9},
	shorttitle = {Algebraic {Replicated} {Data} {Types}},
	doi = {10.4230/DARTS.9.2.26},
	number = {2},
	urldate = {2024-05-10},
	journal = {Dagstuhl Artifacts Series},
	author = {Kuessner, Christian and Mogk, Ragnar and Wickert, Anna-Katharina and Mezini, Mira},
	editor = {Kuessner, Christian and Mogk, Ragnar and Wickert, Anna-Katharina and Mezini, Mira},
	year = {2023},
	doi = {10.4230/DARTS.9.2.26},
}
```

---
