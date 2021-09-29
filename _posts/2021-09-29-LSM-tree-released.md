---
title: The Release of a Revolutionized LSM-tree
commentable: false
Edit: 2021-09-28
mathjax: true
mermaid: true
status: In-Progress
tags: News
categories: Progress
description: An LSM-tree variant leveraging dentry management of file system
---

<p>We have released a pre-print paper titled "<a href="https://arxiv.org/abs/2109.13142" target="_blank">Accelerating LSM-Tree with the Dentry Management of File System</a>". It presents a new LSM-tree variant namely DeLSM leveraging the dentry management of file system. In contrast to a conventional LSM-tree, each KV pair of DeLSM makes an individual file while the original SST file is transformed into an SST directory. A major compaction of DeLSM hence no longer physically moves actual KV pairs but their dentrys. As a result, DeLSM significantly reduces the I/O amplification for LSM-tree and achieves superior performance. More details of our design and preliminary experimental results can be found in the <a href="https://arxiv.org/pdf/2109.13142.pdf" style="text-decoration: none;" target="_blank">paper</a>.</p>

<p>The first author of this paper, Mr. Yanpeng Hu, is a first-year postgraduate student of Toast Lab at ShanghaiTech University.</p>



