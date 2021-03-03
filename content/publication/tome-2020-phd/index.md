---
title: "Redesigning Query Engines for White-box Compression"
date: 2020-01-01
publishDate: 2020-08-28T08:31:21.646571Z
authors: ["Diego G. Tomé", "Peter Boncz"]
publication_types: ["1"]
abstract: "Modern columnar databases heavily use compression to reduce memory footprint and boost query execution. These techniques, however, are implemented as a ”black box”, since their decompression logic is hard-coded and part of the table scan infrastructure. We proposed a novel compression model called White-box compression that views compression actions as functions over the physical columns stored in a block. Because these functions become visible as expressions in the query plan, many more optimizations can be made by the database system, boosting query execution speed. These functions are learnt from the data and also allow the data to be stored much more compactly, by decomposing string values, storing data in appropriate data-types automatically, and exploiting correlations between columns. White-box compression opens up a whole new set of research questions. We started with (1) How to learn whitebox compression expressions (functions) from the data automatically? This Ph.D. research will subsequently study (2) How to leverage white-box compression with (run-time) query optimizations? (3) How can we integrate white-box compression in a query engine, if the white-box functions may be different for each block of data?"
featured: false
publication: "*PhdWorkshop@VLDB*"
url_pdf: "files/phd_vldb.pdf"
url_code: "https://github.com/diegomestre2/Master"
---

