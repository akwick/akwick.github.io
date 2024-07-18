---
title: "Uncovering the Hidden Dangers: Finding Unsafe Go Code in the Wild"
date: 2020-12-29
tags: ["Go","static analysis","memory corruption","unsafe API", "vulnerable API usage", "buffer overflow"]
author: ["Johannes Lauinger", "Lars Baumgärtner", "Anna-Katharina Wickert", "Mira Mezini"]
description: "An empirical study of unsafe usages in Go." 
summary: "We conducted an empirical study to understand how frequently the unsafe API is used in Go. We show that 38% of the analyzed projects directly use the unsafe API. Further, we introduce go-geiger and go-safer to assess usages of the API."
editPost:
    URL: "10.1109/TrustCom50675.2020.00063"
    Text: "DOI"

---


+ [📄 Paper on arXiv](https://arxiv.org/abs/2010.11242)
+ [🔒 go-safer](https://github.com/stg-tud/go-safer)
+ [☢ go-geiger](https://github.com/stg-tud/go-geiger)


---

##### Abstract

The Go programming language aims to provide memory and thread safety through measures such as automated memory management with garbage collection and a strict type system. However, it also offers a way of circumventing this safety net through the use of the unsafe package. While there are legitimate use cases for unsafe, developers must exercise caution to avoid introducing vulnerabilities like buffer overflows or memory corruption in general. In this work, we present go-geiger, a novel tool for Go developers to quantify unsafe usages in a project's source code and all of its dependencies. Using go-geiger, we conducted a study on the usage of unsafe in the top 500 most popular open-source Go projects on GitHub, including a manual analysis of 1,400 code samples on how unsafe is used. From the projects using Go's module system, 38% directly contain at least one unsafe usage, and 91% contain at least one unsafe usage in the project itself or one of its transitive dependencies. Based on the usage patterns found, we present possible exploit vectors in different scenarios. Finally, we present go-safer, a novel static analysis tool to identify dangerous and common usage patterns that were previously undetected with existing tools.


---

##### Citation

Johannes Lauinger, Lars Baumgärtner, **Anna-Katharina Wickert**, and Mira Mezini. “Uncovering the hidden dangers: Finding unsafe go code in the wild.” In: *2020 IEEE 19th international conference on trust, security and privacy in computing and communications (TrustCom)*. IEEE, 2020. DOI: [10.1109/TRUSTCOM50675.2020.00063](https://doi.org/10.1109/TrustCom50675.2020.00063).


```BibTeX
@inproceedings{lauinger2020uncovering,
	title = {Uncovering the {Hidden} {Dangers}: {Finding} {Unsafe} {Go} {Code} in the {Wild}},
	copyright = {All rights reserved},
	shorttitle = {Uncovering the {Hidden} {Dangers}},
	doi = {10.1109/TrustCom50675.2020.00063},
	booktitle = {2020 {IEEE} 19th {International} {Conference} on {Trust}, {Security} and {Privacy} in {Computing} and {Communications} ({TrustCom})},
	author = {Lauinger, Johannes and Baumgärtner, Lars and Wickert, Anna-Katharina and Mezini, Mira},
	month = dec,
	year = {2020},
	pages = {410--417},
}
```

------ 

##### Related material

+ [💣 Exploit Proof of Concept](https://dev.to/jlauinger/exploitation-exercise-with-unsafe-pointer-in-go-information-leak-part-1-1kga)
+ [🎙️ Presentation on YouTube](https://youtu.be/adn6A7nG61I)