---
title: "Operand size reconfiguration for big data processing in memory"
date: 2017-01-01
publishDate: 2019-08-28T08:31:21.643084Z
authors: ["Paulo C Santos", "Geraldo F Oliveira", "Diego G Tomé", "Marco AZ Alves", "Eduardo C Almeida", "Luigi Carro"]
publication_types: ["1"]
abstract: "Nowadays, applications that predominantly perform lookups over large databases are becoming more popular
with column-stores as the database system architecture of choice.
For these applications, Hybrid Memory Cubes (HMCs) can
provide bandwidth of up to 320 GB/s and represents the best
choice to keep the throughput for these ever increasing databases.
However, even with the high available memory bandwidth and
processing power, in order to achieve the peak performance,
data movements through the memory hierarchy consumes an
unnecessary amount of time and energy. In order to accelerate
database operations, and reduce the energy consumption of
the system, this paper presents the Reconfigurable Vector Unit
(RVU) that enables massive and adaptive in-memory processing,
extending the native HMC instructions and also increasing its
effectiveness. RVU enables the programmer to reconfigure it
to perform as a large vector unit or multiple small vectors
units to better adjust for the application needs during different
computation phases. Due to its adaptability, RVU is capable of
achieving performance increase of 27× on average and reduce
the DRAM energy consumption in 29% when compared to an
x86 processor with 16 cores. Compared with the state-of-theart mechanism capable of performing large vector operations
with fixed size, inside the HMC, RVU performed up to 12%
better in terms of performance and improve in 53% the energy
consumption."
featured: false
publication: "*Proceedings of the Conference on Design, Automation & Test in Europe*"
url_pdf: "files/operand.pdf"
url_code: "https://github.com/diegomestre2/Master"
---

