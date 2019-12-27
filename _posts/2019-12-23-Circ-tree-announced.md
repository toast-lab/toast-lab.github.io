---
title: The Release of Circ-Tree
commentable: false
Edit: 2019-12-23
mathjax: true
mermaid: true
tags: News
categories: Progress
description: Circ-Tree is a new B+-tree variant for persistent memory with circular design.
---

<p>We have released a pre-print paper titled "<a href="https://arxiv.org/abs/1912.09783" target="_blank">Circ-Tree: A B+-Tree Variant with Circular Design for Persistent Memory</a>". It presents a new B+-tree variant for the persistent memory built on top of the byte-addressable non-volatile memory, e.g., Intel 3D XPoint. 
In contrast to a standard B+-tree node, a node of Circ-Tree no long has a fixed base address but is with a circular structure. This novel design significantly reduces memory writes in shifting key-value pairs for insertion and deletion. More details of Circ-Tree can be found in the <a href="https://arxiv.org/pdf/1912.09783.pdf" style="text-decoration: none;" target="_blank">paper</a>. A final version of the paper would be sent out for review soon.</p>

<p>The second author of this paper, <a href="https://scholar.google.com/citations?user=QMbXGTsAAAAJ" style="text-decoration: none;" target="_blank">Mr Gunavaran Brihadiswarn</a>, did the work when he was an intern in Singapore University of Technology and Design as a third-year undergraduate student. We wish him every success in his future endeavours.</p>

