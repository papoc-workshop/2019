---
title: "Call for Papers"
date: 2018-10-26T11:24:56+01:00
draft: false
type: page
layout: cfp
---

<br>
Consistency is one of the fundamental issues of distributed computing. There are many competing consistency models, with subtly different power in principle. In practice, the well-known "Consistency-Availability-Partition Tolerance" trade-off translates to difficult choices between fault tolerance, performance, and programmability. These issues and trade-offs become particularly challenging at scale, with a large number of processes or a large distributed database, and in the presence of high latency and failure-prone networks. These challenges might become more pronounced with the use of emerging edge computing architectures that will further increase the scale and heterogeneity of systems. It is clear that there is no universally best solution.

Possible approaches cover the whole spectrum between strong and eventual consistency. Strong consistency (linearizability or serializability, achieved via total ordering) provides familiar and intuitive semantics but requires slow and fragile synchronisation and coordination overheads. The unlimited parallelism allowed by available models, such as eventual consistency, which promise high performance, but allow divergence and conflicts make it difficult to ensure useful application invariants, and managing relevant meta-data can become a challenge. The research and development communities are actively exploring intermediate models (replicated data types, monotonic programming, CRDTs, LVars, causal consistency, red-blue consistency, invariant- and proof-based systems, etc.), designed to improve efficiency, programmability, and overall operation without negatively impacting scalability.

This workshop aims at further advancing the principles and practice of consistency models for large-scale, fault-tolerant, distributed data management systems. It will bring together theoreticians and practitioners from different horizons: system development, distributed algorithms, concurrency, fault tolerance, databases, language and verification, from both academia and industry.

The PaPoC workshop is looking for contributions on the following and associated relevant topics:

- Design principles, correctness conditions, and programming patterns for scalable distributed data systems.
- Techniques for available consistency (also known as weak consistency): session guarantees, causal consistency, operational transformation, conflict-free replicated data types, monotonic programming, state merge, commutativity, etc.
- Techniques for scaling and improving the performance of strongly consistent systems (e.g., Paxos-based, state machine replication, shared-log consensus, blockchain).
- How to expose consistency vs. performance and scalability trade-offs in the programming model, and how to help developers choose.
- How to support composed operations spanning multiple objects (transactions, workflows).
- Reasoning, analysis and verification of applications operating on top of available consistency data management solutions.
- How to strengthen the guarantees beyond consistency: fault tolerance, security, ensuring invariants, bounding metadata size, and controlling divergence.
- Consistency in large-scale distributed scenarios, including geo-replicated and edge systems

## Submission Guidelines

We solicit proposals in two possible formats: 1) Short Papers (5-6 pages, ACM double-column format) with original contributions, experience reports, or work in progress containing initial validations; or 2) contributed talks that should be summarised in the form of extended abstracts (2 pages, ACM double-column format) reporting positions and visions for the future, identifying new challenges or research venues, or early reports of on-going work.

All papers should be written in English and submitted as a single PDF file through the [EasyChair system](https://easychair.org/conferences/?conf=papoc19), using 8.5x11-inch paper, double-column, 10pt font. Limits reported above include all content, images, and references. Authors should use the [ACM Master article template](https://www.acm.org/publications/proceedings-template) when preparing their submissions. The first page should provide the name(s) and affiliation(s) of the author(s), and the type of submission (Short Paper or Extended Abstract).  At least one of the authors of every accepted paper must register and present the paper at the workshop.

Authors will have the opportunity to choose if they want their papers/extended abstracts published in ACM Digital Library (with papers from other EuroSys workshops).

## Important Dates
