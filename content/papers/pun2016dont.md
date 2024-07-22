---
title: "Don’t let data Go astray" 
date: 2016-10-31
tags: ["static analysis","information flow","go"]
author: [Ka I Pun, Martin Steffen, Volker Stolz, Anna-Katharina Wickert, Eric Bodden, Michael Eichberg]
description: "Static taint analysis for Go, addressing concurrent programming and channel communication to ensure secure information flow and prevent vulnerabilities." 
summary: "This paper presents a static taint analysis for Go, a statically typed language with concurrent programming features like goroutines and channel communication. The analysis focuses on secure information flow to prevent vulnerabilities caused by unchecked user input, offering solutions for both context-sensitive taint analysis and channel communication in Go."
---

---

- [📄 Paper](https://bodden.de/pubs/bep16gotaint.pdf)

---

##### Abstract

Taint analysis is a form of data flow analysis aiming at secure information flow. For example, unchecked user input is considered typically as “tainted”, i.e., as untrusted and potentially dangerous. Untrusted data may lead to corrupt memory, undermine the correct functioning or privacy concerns of the software otherwise, if it reaches program points it is not supposed to. Many common attack vectors exploit vulnerabilities based on unchecked data and the programmer’s negligence of foreseeing all possible user inputs (including malicious ones) and the resulting information flows through the program.
We present a static taint analysis for Go, a modern, statically typed programming lan- guage. Go in particular features concurrent programming, supporting light-weight threads dubbed “goroutines”, and message-based communication. Beside a classical context- sensitive taint analysis, the paper presents a solution for analyzing channel communication in Go. A longer version of the material will appear in [bodden2016information](/papers/bodden2016infromation/).

---

##### Citation

Ka I Pun, Martin Steffen, Volker Stolz, Anna-Katharina Wickert, Eric Bodden, and Michael Eichberg. “Don’t let data go astray.” In: Workshop on programming theory (NWPT’16). 

```BibTeX
@inproceedings{pun16don,
	title = {Don’t let data go astray},
	booktitle = {Workshop on programming theory ({NWPT}’16)},
	author = {Pun, Ka I and Steffen, Martin and Stolz, Volker and Wickert, Anna-Katharina and Bodden, Eric and Eichberg, Michael},
    year = {2016},
}
```

---
