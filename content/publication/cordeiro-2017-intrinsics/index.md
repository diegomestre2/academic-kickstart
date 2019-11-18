---
title: "Intrinsics-HMC: An Automatic Trace Generator for Simulations of Processing-In-Memory Instructions"
date: 2017-01-01
publishDate: 2019-08-28T08:31:21.645260Z
authors: ["Aline Santana Cordeiro", "Tiago Rodrigo Kepe", "Diego Gomes Tomé", "Eduardo Cunha de Almeida", "Marco Antonio Zanata Alves"]
publication_types: ["2"]
abstract: "Processor-in-Memory (PIM) architectures, such as the Hybrid Memory Cube (HMC), are emerging nowadays as a solution for processing large
amount of data directly inside the memory. In this area, several researchers are
proposing and evaluating new instructions and new PIM architectures. For such
evaluations, trace-driven simulators, as the Simulator of Non-Uniform Cache
Architectures (SiNUCA), are commonly used in order to model these new proposed systems. Such simulators provide fast prototyping of new architectures,
while it requires the researcher to write simulation traces manually when evaluating new Instruction Set Architecture (ISA) proposals, which is an time consuming and error prone task. In this work, we propose a methodology for fast generation of simulation traces focused on HMC architecture, which consists on a
high-level Intrinsics-HMC library and a modification inside the trace-generator
tool from SiNUCA. Our proposal enables the researchers to write high level
code in C/C++ languages using our library, which mimics the behavior of HMC
instructions. These codes can be compiled and executed in traditional x86 architectures for verification. After ensure the code is correct and working, the user
can use our modified version of SiNUCA-Tracer to translate HMC functions
into HMC instructions know by the simulator, providing a convenient solution
to generate traces and fast simulations of new PIM architectures. Results using the proposed technique applied on database application kernels show the
correct translation and simulation of new HMC instructions using SiNUCA."
featured: false
publication: "*Simpósio em Sistemas Computacionais de Alto Desempenho (WSCAD)*"
url_pdf: "files/intrinsics.pdf"
url_code: "https://github.com/AlineS/intrinsics"
---

