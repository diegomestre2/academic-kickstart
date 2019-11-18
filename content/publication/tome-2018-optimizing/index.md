---
title: "Optimizing Group-By And Aggregation using GPU-CPU Co-Processing"
date: 2018-01-01
publishDate: 2019-08-28T08:31:21.647180Z
authors: ["Diego Tomé", "Tim Gubner", "Mark Raasveldt", "Eyal Rozenberg", "Peter Boncz"]
publication_types: ["1"]
abstract: "While GPU query processing is a well-studied area, real adoption is limited in practice as typically GPU execution is only
significantly faster than CPU execution if the data resides in
GPU memory, which limits scalability to small data scenarios
where performance tends to be less critical. Another problem
is that not all query code (e.g. UDFs) will realistically be
able to run on GPUs. We therefore investigate CPU-GPU
co-processing, where both the CPU and GPU are involved in
evaluating the query in scenarios where the data does not fit
in the GPU memory.
As we wish to deeply explore opportunities for optimizing
execution speed, we narrow our focus further to a specific
well-studied OLAP scenario, amenable to such co-processing,
in the form of the TPC-H benchmark Query 1.
For this query, and at large scale factors, we are able to improve performance significantly over the state–of–the–art for
GPU implementations; we present competitive performance
of a GPU versus a state–of–the–art multi-core CPU baseline
a novelty for data exceeding GPU memory size; and finally,
we show that co-processing does provide significant additional
speedup over any of the processors individually.
We achieve this performance improvement by utilizing
parallelism-friendly compression to alleviate the PCIe transfer
bottleneck, query-compilation-like fusion of the processing
operations, and a simple yet effective scheduling mechanism.
We hope that some of these features can inspire future w"
featured: false
publication: "*ADMS@VLDB*"
url_pdf: "files/cpu_gpu.pdf"
url_code: "https://github.com/diegomestre2/tpchQ01_GPU"
---

