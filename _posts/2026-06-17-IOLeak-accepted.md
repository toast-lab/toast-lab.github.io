---
title: One Paper Accepted by ACM TECS
commentable: false
Edit: 2026-06-17
mathjax: true
mermaid: true
status: Completed
tags: News
categories: Publication
description: A comprehensive version of IOLeak is accepted by ACM TECS.
---

<p>Our paper titled "IOLeak: Side-channel Information Leakage by Monitoring CPU Frequency Scaling through I/Os" is accepted by <a href="https://tecs.acm.org" style="text-decoration: none;" target="_blank">ACM Transactions on Embedded Computing Systems (TECS)</a>. Power efficiency gains increasing importance to both general-purpose and embedded computing systems. CPU frequency scaling is widely used to dynamically adjust the speed and voltage of CPU cores in real time, aiming to gain both high performance and power efficiency. Prior works indicate that the runtime variations of CPU frequency expose a viable attack surface to leak information of the ongoing workload. In this paper, we find that the performance of I/O requests, such as file I/Os on a fast storage device, is affected by the runtime changes of CPU frequency and, in turn, is exploitable to speculate the workload’s sensitive information. We are hence motivated to develop IOLeak, a new side channel that is based on CPU frequency scaling but does not directly rely on CPU frequency values. We first build IOLeak covert channel by online monitoring I/O latency for secretive communication, both in noise-free and noisy environments. Next, we leverage IOLeak to launch a number of stealthy attacks, such as extracting cryptographic keys and fingerprinting websites, and confirm that IOLeak successfully leaks information by conducting inconspicuous file I/O operations. We particularly demonstrate that IOLeak is effective in the cross-virtual machine (VM) fashion that has not been covered by prior attacks relying on CPU frequency values. We also verify that IOLeak is capable in both general-purpose computers and embedded systems. These justify the serious security breach that IOLeak causes. Regarding the impact of IOLeak, we have responsibly reported our findings to the security teams of relevant organizations and received their feedback.</p>

<p> ACM Transactions on Embedded Computing Systems (TECS) is a prestigious venue that presents the leading work relating to the analysis, design, behavior, and experience with embedded computing systems. A preliminary version of this paper has been published in HotStorage 2025. Professor <a href="https://faculty.sist.shanghaitech.edu.cn/liust/"  style="text-decoration: none;" target="_blank">Siting Liu (&#21016;&#24605;&#24311;)</a> of ShanghaiTech University helped to improve the work. Chundong is the corresponding author. The first author of this paper, Miss Li Zhu, is going to graduate with a Master's degree in July 2026. We wish her the best of luck in all of her future endeavors.</p>


