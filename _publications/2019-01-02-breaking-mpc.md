---
title: "Breaking MPC implementations through compression"
collection: publications
permalink: /publication/2019-01-02-breaking-mpc
excerpt: ''
date: 2019-01-02
venue: 'International Journal of Information Security volume'
paperurl: 'https://prvsousa.github.io/files/Breaking MPC implementations through compression.pdf'
citation: 'Resende, João S., et al. "Breaking MPC implementations through compression." International Journal of Information Security 18.4 (2019): 505-518.'
---

[Download paper here](https://prvsousa.github.io/files/Breaking MPC implementations through compression.pdf)

Abstract:

There are many cryptographic protocols in the literature that are scientifically and mathematically sound. By extension, cryptography today seeks to respond to numerous properties of the communication process beyond confidentiality (secrecy), such as integrity, authenticity, and anonymity. In addition to the theoretical evidence, implementations must be equally secure. Due to the ever-increasing intrusion from governments and other groups, citizens are now seeking alternatives ways of communication that do not leak information. In this paper, we analyze multiparty computation (MPC), which is a sub-field of cryptography with the goal of creating methods for parties to jointly compute a function over their inputs while keeping those inputs private. This is a very useful method that can be used, for example, to carry out computations on anonymous data without having to leak that data. Thus, due to the importance of confidentiality in this type of technique, we analyze active and passive attacks using complexity measures (compression and entropy). We start by obtaining network traces and syscalls, then we analyze them using compression and entropy techniques. Finally, we cluster the traces and syscalls using standard clustering techniques. This approach does not need any deep specific knowledge of the implementations being analyzed. This paper presents a security analysis for four MPC frameworks, where three were identified as insecure. These insecure libraries leak information about the inputs provided by each party of the communication. Additionally, we have detected, through a careful analysis of its source code, that SPDZ-2’s secret sharing schema always produces the same results.

Recommended citation: Resende, João S., et al. "Breaking MPC implementations through compression." International Journal of Information Security 18.4 (2019): 505-518.