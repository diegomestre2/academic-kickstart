---
title: "Near-Data Filters: Taking Another Brick from the Memory Wall"
date: 2018-01-01
publishDate: 2019-08-28T08:31:21.646571Z
authors: ["Diego G. Tomé", "Tiago R. Kepe", "Marco A. Z. Alves", "Eduardo C. de Almeida"]
publication_types: ["1"]
abstract: "In this paper, we use the potential of the near-data parallel
computing presented in the Hybrid Memory Cube (HMC) to
process near-data query filters and mitigate the data movement through the memory hierarchy up to the x86 processor.
In particular, we present a set of extensions to the HMC Instruction Set Architecture (ISA) to filter data in-memory.
Our near-data filters support vector instructions and solve
data and control dependencies internally in the memory: internal register bank and branch-less evaluation of data filters
transform control-flow dependencies into data-flow dependencies (i.e., predicated execution). We implemented the
near-data filters in the select scan operator and we discuss
preliminary results for projection and join. Our experiments
running the select scan achieve performance improvements
of up to 5.64× with an average reduction of 80% in energy consumption when e"
featured: false
publication: "*ADMS@VLDB*"
url_pdf: "files/near_data.pdf"
url_code: "https://github.com/diegomestre2/Master"
---

