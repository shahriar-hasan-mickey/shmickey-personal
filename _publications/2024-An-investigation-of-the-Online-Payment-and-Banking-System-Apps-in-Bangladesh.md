---
title: "An investigation of the Online Payment and Banking System Apps in Bangladesh"
collection: publications
category: manuscripts
permalink: /publication/2024-An-investigation-of-the-Online-Payment-and-Banking-System-Apps-in-Bangladesh
excerpt: 'This paper is about conducting static and dynamic analysis of the android applications using available open-source analyzers and opensource tools.'
date: 2024-05-28
venue: 'arXive'

paperurl: 'https://arxiv.org/pdf/2407.07766'
citation: 'Mickey, S.H. & Yanhaona, M.N. (2024). &quot;An investigation of the Online Payment and Banking System Apps in Bangladesh.&quot; <i>arXive</i>. https://doi.org/10.48550/arXiv.2407.07766.'
---

Presently, Bangladesh is expending substantial efforts to digitize its national infrastructure,
with a significant emphasis on achieving this goal
through mobile applications that facilitate online
payments and banking system advancements. Despite
the lack of knowledge about the security level of
these systems, they are currently in frequent use
without much consideration. To observe whether they
follow the minimum global set standards, we choose
to conduct static and dynamic analysis of the applications using available open-source analyzers and opensource tools. This allows us to attempt to extract sensitive information, if possible, and determine whether
the applications adhere to the standards of MASVS
set by OWASP. We show how we analyzed 17 .apks
and a SDK using open source scanner and discover
security flaws to the applications, such as weaknesses
related to data storage, vulnerable cryptographic elements, insecure network communications, and unsafe
utilization of WebViews, detected by the scanner.
These outputs demonstrate the need for extensive
manual analysis of the application through source
code review and dynamic analysis. We further implement reverse engineering and dynamic approach
to verify the outputs and expose some applications
do not comply with the standard method of network
communication. Moreover, we attempt to verify the
rest of the potential vulnerabilities in the next phase
of our ongoing investigation.
