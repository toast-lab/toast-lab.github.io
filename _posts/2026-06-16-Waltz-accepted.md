---
title: One Paper Accepted by ACM TOS
commentable: false
Edit: 2026-06-16
mathjax: true
mermaid: true
status: Completed
tags: News
categories: Publication
description: A paper about Computational Storage Device (CSD) is accepted by ACM TOS.
---

<p>Our paper titled "Waltz: Temperature-Aware Cooperative Compression for High-Performance Compression-Based CSDs" is accepted by the <a href="https://tos.acm.org" style="text-decoration: none;" target="_blank">ACM Transactions on Storage (TOS)</a>. Data compression is widely adopted for modern solid-state drives (SSDs) to mitigate both storage capacity and SSD lifetime issues. Researchers have proposed compression schemes at different system layers, including device-side solutions like CCSDs ( c ompression-based c omputational SSDs) and compression supported by host-side, like F2FS (flash-friendly file system). We conduct quantitative studies to understand how host-side and device-side compression schemes affect the temperature and performance of SSD-based storage systems. From our experiments, device-side compression, facilitated by a hardware compression engine, can raise the temperature of CCSDs to intolerable levels, resulting in throttling and service shutdown. In contrast, host-side compression causes software-stack overhead, which often results in large performance degradation and resource consumption. To ensure efficient data compression with high performance and better temperature control, we propose Waltz, a temperature-aware cooperative compression method that schedules (de)compression tasks at the host and device sides by monitoring device temperature. Furthermore, we introduce two variants (Waltzs and Waltzp) for space and performance optimization, respectively. Waltz is implemented within F2FS, achieving high performance while extending SSD lifetime and preventing overheating-induced in-flight shutdowns.</p>

<p>ACM TOS is widely considered as a premier journal for publishing advancements in data storage research and practice. This works was mainly conducted in Professor <a href="https://faculty.ecnu.edu.cn/_s16/sl2_13905/main.psp" style="text-decoration: none;" target="_blank">Liang Shi (&#30707;&#20142;)</a>'s group at <a href="http://https://www.ecnu.edu.cn/" style="text-decoration: none;" target="_blank">East China Normal University</a> (&#21326;&#19996;&#24072;&#33539;&#22823;&#23398;). Co-authors of this paper include Professor <a href="https://elainelv.github.io/" style="text-decoration: none;" target="_blank">Yina Lv (&#21525;&#29088;&#23068;)</a> of <a href="http://https://www.xmu.edu.cn/" style="text-decoration: none;" target="_blank">Xiamen University</a> (&#21414;&#38376;&#22823;&#23398;), Professor <a href="https://www.cs.pitt.edu/people/full-time-faculty/youtao-zhang" style="text-decoration: none;" target="_blank">Youtao Zhang</a> of <a href="https://www.pitt.edu/" style="text-decoration: none;" target="_blank">University of Pittsburgh</a>, and Chundong.</p>
