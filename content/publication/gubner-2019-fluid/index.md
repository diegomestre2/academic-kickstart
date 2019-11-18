---
title: "Fluid Co-processing: GPU Bloom-filters for CPU Joins"
date: 2019-01-01
publishDate: 2019-08-28T08:31:21.647793Z
authors: ["Tim Gubner", "Diego Tomé", "Harald Lang", "Peter Boncz"]
publication_types: ["1"]
abstract: "It has so far been unclear which data-intensive CPU tasks
can be accelerated with GPUs, as GPUs are bottlenecked by
the slow bus connection to the CPU and the limited size of
GPU memories.
In this paper we demonstrate a database workload where
co-processing actually helps: accelerating large join pipelines
where the join condition is selective, by pushing down a
Bloom filter test for early pruning. GPUs are more powerful than CPUs for computing hash functions needed in
Bloom filter tests, have a local memory with significantly
more random-access bandwidth than the CPU, and since
only keys (or extracts thereof) have to be moved to the GPU,
data transfers over the bus are relatively small. Our microbenchmarks show that raw Bloom filter lookups are up to
6× faster on the GPU than on the CPU in case the Bloom
filter is larger than the CPU cache.
The next quest is for a database architecture that allows
efficient CPU-GPU co-processing. We present a new heterogeneous query processing framework based on fluid coprocessing. In fluid co-processing, tasks of different sizes
– that fit the device – are dynamically co-processed. Early
results show that fluid co-processing consistently improves
end-to-end CPU performance of early pruning"
featured: false
publication: "*Proceedings of the 15th International Workshop on Data Management on New Hardware*"
url_pdf: "files/fluid.pdf"
url_code: "https://github.com/t1mm3/fluid_coprocessing"
---

