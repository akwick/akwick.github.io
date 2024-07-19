---
title: "A Fine-grained Data Set and Analysis of Tangling in Bug Fixing Commits" 
date: 2022-07-02
tags: [
  "tangled changes",
  "tangled commits",
  "bug fix",
  "manual validation",
  "research turk",
  "registered report"]
author: [
  "Steffen Herbold",
  "Alexander Trautsch",
  "Benjamin Ledel",
  "Alireza Aghamohammadi",
  "Taher Ahmed Ghaleb",
  "Kuljit Kaur Chahal",
  "Tim Bossenmaier",
  "Bhaveet Nagaria",
  "Philip Makedonski",
  "Matin Nili Ahmadabadi",
  "Kristof Szabados",
  "Helge Spieker",
  "Matej Madeja",
  "Nathaniel Hoy",
  "Valentina Lenarduzzi",
  "Shangwen Wang",
  "Gema Rodríguez-Pérez",
  "Ricardo Colomo-Palacios",
  "Roberto Verdecchia",
  "Paramvir Singh",
  "Yihao Qin",
  "Debasish Chakroborti",
  "Willard Davis",
  "Vijay Walunj",
  "Hongjun Wu",
  "Diego Marcilio",
  "Omar Alam",
  "Abdullah Aldaeej",
  "Idan Amit",
  "Burak Turhan",
  "Simon Eismann",
  "Anna-Katharina Wickert",
  "Ivano Malavolta",
  "Matus Sulir",
  "Fatemeh Fard",
  "Austin Z. Henley",
  "Stratos Kourtzanidis",
  "Eray Tuzun",
  "Christoph Treude",
  "Simin Maleki Shamasbi",
  "Ivan Pashchenko",
  "Marvin Wyrich",
  "James Davis",
  "Alexander Serebrenik",
  "Ella Albrecht",
  "Ethem Utku Aktas",
  "Daniel Strüber",
  "Johannes Erbel"
]
description: "This study shows tangled commits in bug fixes introduce significant noise, affecting research outcomes. Manual labeling reveals 66-87% of changes fix the actual bug." 
summary: "This study examines the prevalence of tangled commits in bug fixes, revealing that 66-87% of changes in production code files actually fix bugs. Using a crowdsourcing approach, we found significant noise in data due to tangling, suggesting that unvalidated data is likely very noisy and can alter research results."
---

---

- [📄 Paper Springer](https://doi.org/10.1007/s10664-021-10083-5)
- [📄 Paper arXiv](https://arxiv.org/pdf/2011.06244)

---

##### Abstract

**Context**
Tangled commits are changes to software that address multiple concerns at once. For researchers interested in bugs, tangled commits mean that they actually study not only bugs, but also other concerns irrelevant for the study of bugs.

**Objective**
We want to improve our understanding of the prevalence of tangling and the types of changes that are tangled within bug fixing commits.

**Methods**
We use a crowd sourcing approach for manual labeling to validate which changes contribute to bug fixes for each line in bug fixing commits. Each line is labeled by four participants. If at least three participants agree on the same label, we have consensus.

**Results**
We estimate that between 17% and 32% of all changes in bug fixing commits modify the source code to fix the underlying problem. However, when we only consider changes to the production code files this ratio increases to 66% to 87%. We find that about 11% of lines are hard to label leading to active disagreements between participants. Due to confirmed tangling and the uncertainty in our data, we estimate that 3% to 47% of data is noisy without manual untangling, depending on the use case.

**Conclusion**
Tangled commits have a high prevalence in bug fixes and can lead to a large amount of noise in the data. Prior research indicates that this noise may alter results. As researchers, we should be skeptics and assume that unvalidated data is likely very noisy, until proven otherwise.

---

##### Citation

Steffen Herbold, Alexander Trautsch, Benjamin Ledel, Alireza Aghamohammadi, Taher Ahmed Ghaleb, Kuljit Kaur Chahal, Tim Bossenmaier, Bhaveet Nagaria, Philip Makedonski, Matin Nili Ahmadabadi, Kristof Szabados, Helge Spieker, Matej Ma- deja, Nathaniel Hoy, Valentina Lenarduzzi, Shangwen Wang, Gema Rodríguez-Pérez, Ricardo Colomo-Palacios, Roberto Ver- decchia, Paramvir Singh, Yihao Qin, Debasish Chakroborti, Willard Davis, Vijay Walunj, Hongjun Wu, Diego Marcilio, Omar Alam, Abdullah Aldaeej, Idan Amit, Burak Turhan, Simon Eismann, **Anna-Katharina Wickert**, Ivano Malavolta, Matus Sulir, Fate- meh Fard, Austin Z. Henley, Stratos Kourtzanidis, Eray Tuzun, Christoph Treude, Simin Maleki Shamasbi, Ivan Pashchenko, Marvin Wyrich, James Davis, Alexander Serebrenik, Ella Al- brecht, Ethem Utku Aktas, Daniel Strüber, and Johannes Erbel.
“A Fine-grained Data Set and Analysis of Tangling in Bug Fixing Commits.” In: *Empirical Software Engineering 27.6 (2022)*. DOI: [10.1007/s10664-021-10083-5](https://doi.org/10.1007/s10664-021-10083-5).

```BibTeX
@article{herbold2021finegrained,
	title = {A {Fine}-grained {Data} {Set} and {Analysis} of {Tangling} in {Bug} {Fixing} {Commits}},
	volume = {27},
	doi = {10.1007/s10664-021-10083-5},
	author = {Herbold, Steffen and Trautsch, Alexander and Ledel, Benjamin and Aghamohammadi, Alireza and Ghaleb, Taher Ahmed and Chahal, Kuljit Kaur and Bossenmaier, Tim and Nagaria, Bhaveet and Makedonski, Philip and Ahmadabadi, Matin Nili and Szabados, Kristof and Spieker, Helge and Madeja, Matej and Hoy, Nathaniel and Lenarduzzi, Valentina and Wang, Shangwen and Rodríguez-Pérez, Gema and Colomo-Palacios, Ricardo and Verdecchia, Roberto and Singh, Paramvir and Qin, Yihao and Chakroborti, Debasish and Davis, Willard and Walunj, Vijay and Wu, Hongjun and Marcilio, Diego and Alam, Omar and Aldaeej, Abdullah and Amit, Idan and Turhan, Burak and Eismann, Simon and Wickert, Anna-Katharina and Malavolta, Ivano and Sulir, Matus and Fard, Fatemeh and Henley, Austin Z. and Kourtzanidis, Stratos and Tuzun, Eray and Treude, Christoph and Shamasbi, Simin Maleki and Pashchenko, Ivan and Wyrich, Marvin and Davis, James and Serebrenik, Alexander and Albrecht, Ella and Aktas, Ethem Utku and Strüber, Daniel and Erbel, Johannes},
	journal = {Empirical Software Engineering},
	number = {6},
    volume={27},
	year = {2022},
	publisher={Springer},
}
```

---
