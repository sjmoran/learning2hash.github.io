---
layout: publication
title: "K-Nearest Neighbors Hashing"
authors: Xiangyu He, Peisong Wang, Jian Cheng
conference: CVPR
year: 2019
bibkey: he2019knearest
additional_links:
   - {name: "Paper", url: "http://openaccess.thecvf.com/content_CVPR_2019/papers/He_K-Nearest_Neighbors_Hashing_CVPR_2019_paper.pdf"}
---
Hashing based approximate nearest neighbor search embeds high dimensional data to compact binary codes, which
enables efficient similarity search and storage. However,
the non-isometry sign(·) function makes it hard to project
the nearest neighbors in continuous data space into the
closest codewords in discrete Hamming space. In this work,
we revisit the sign(·) function from the perspective of space partitioning.
In specific, we bridge the gap between
k-nearest neighbors and binary hashing codes with Shannon entropy. We further propose a novel K-Nearest Neighbors Hashing (KNNH) method to learn binary representations from KNN within the subspaces generated by sign(·).
Theoretical and experimental results show that the KNN relation is of central importance to neighbor preserving embeddings, and the proposed method outperforms the stateof-the-arts on benchmark datasets.
