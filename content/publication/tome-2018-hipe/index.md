---
title: "HIPE: HMC instruction predication extension applied on database processing"
date: 2018-01-01
publishDate: 2019-08-28T08:31:21.643990Z
authors: ["Diego G Tomé", "Paulo C Santos", "Luigi Carro", "Eduardo C Almeida", "Marco AZ Alves"]
publication_types: ["1"]
abstract: "The recent Hybrid Memory Cube (HMC) is a smart
memory which includes functional units inside one logic layer of
the 3D stacked memory design. In order to execute instructions
inside the Hybrid Memory Cube (HMC), the processor needs
to send instructions to be executed near data, keeping most of
the pipeline complexity inside the processor. Thus, control-flow
and data-flow dependencies are all managed inside the processor,
in such way that only update instructions are supported by the
HMC. In order to solve data-flow dependencies inside the memory, previous work proposed HMC Instruction Vector Extensions
(HIVE), which embeds a high number of functional units with
a interlock register bank. In this work we propose HMC Instruction Prediction Extensions (HIPE), that supports predicated
execution inside the memory, in order to transform control-flow
dependencies into data-flow dependencies. Our mechanism focus
on removing the high latency iteration between the processor and
the smart memory during the execution of branches that depends
on data processed inside the memory. In this paper we evaluate a
balanced design of HIVE comparing to x86 and HMC executions.
After we show the HIPE mechanism results when executing a
database workload, which is a strong candidate to use smart
memories. We show interesting trade-offs of performance when
comparing our mechanism to previous work."
featured: false
publication: "*Design, Automation & Test in Europe Conference & Exhibition (DATE), 2018*"
url_pdf: "files/hipe.pdf"
url_code: "https://github.com/diegomestre2/Master"
---

