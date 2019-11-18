---
title: "Uma Abordagem para Processamento em Memória de Operações de Seleção em Sistemas de Bancos de Dados"
date: 2017-01-01
publishDate: 2019-08-28T08:31:21.644590Z
authors: ["Diego Gomes Tomé", "Marco Antonio Zanata Alves", "Eduardo Cunha de Almeida"]
publication_types: ["1"]
abstract: "A considerable portion of the time spent during databases operation
processing consists in moving data around the memory hierarchy rather
than actually processing it. The emergence of smart memories, as the new
Hybrid Memory Cube (HMC) allows mitigating this memory wall problem, by
executing instructions directly inside the memory, reducing data movement. In
this work, we discuss the processing of databases inside the HMC. We focus on
the select scan operator, because the scanning of columns moves large amounts
of data prior to other costly operations like joins (i.e., push-down optimization).
Our preliminary results with the tuple / column / vector-at-a-time query engines
show performance gains of 30% for tuple-at-a-time, 11% column-at-a-time and
6× in the vector-at-a-time execution when compared to x86."
featured: false
publication: "*32nd Brazilian Symposium on Databases*"
url_pdf: "files/WTDBD17.pdf"
url_code: "https://github.com/diegomestre2/Master"
---

