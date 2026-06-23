---
title: One Paper Accepted by APWeb 2026
commentable: false
Edit: 2026-06-23
mathjax: true
mermaid: true
status: Completed
tags: News
categories: Publication
description: A paper on de-aging for LSM-tree is accepted by APWeb '26.
---

<p>Our paper titled "Grove: De-aging by Spawning a Tract of LSM-trees" is accepted by the <a href="https://conferences.sigappfr.org/apweb2026/" style="text-decoration: none;" target="_blank">10th APWeb-WAIM joint international conference on Web and Big Data (APWeb-WAIM 2026)</a>.</p> 

<p>Aging is natural for data storage systems. In this paper, we look into the impact of aging on LSM-tree. Our study indicates that aging badly degrades both write and read performance of LSM-tree. We hence propose Grove, a simple yet effective solution for de-aging. Grove initializes an active LSM-tree from scratch. This tree is rendered immutable once it meets a condition and Grove spawns the next active tree to accommodate arriving data. Grove sets the condition based on the temporal cost of compactions. As Grove continues running, it grows into a tract of trees. By serving write requests with a small tree that has not heavily aged, Grove improves write performance. To handle read requests efficiently, it incorporates a Bloom filter per tree for filtering. We build prototypes for Grove on LevelDB, RocksDB and HotRAP. Grove dramatically boosts their performances. For example, Grove improves write and read throughputs of LevelDB by 2.3x and 2.0x, respectively.</p>

<p>The 10th APWeb-WAIM joint International Conference on Web and Big Data (APWeb-WAIM 2026) will be held during September 7-9, 2026, in Danang, Vietnam. This year, APWeb follows the double-blind reviewing policy. This work was solely completed by Toast Lab. Mr Meng Chen is the first author of the paper. Chundong is the corresponding author.</p>
