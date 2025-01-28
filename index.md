---
title: ccAFv2
layout: home
---
Single-cell transcriptomics has unveiled a vast landscape of cellular heterogeneity in which the cell cycle is a significant component. We trained a high-resolution cell cycle classifier (ccAFv2) using single cell RNA-seq (scRNA-seq) characterized human neural stem cells. The ccAFv2 classifies six cell cycle states (G1, Late G1, S, S/G2, G2/M, and M/Early G1) and a quiescent-like G0 state (qG0), and it incorporates a tunable parameter to filter out less certain classifications. The ccAFv2 classifier performed better than or equivalent to other state-of-the-art methods even while classifying more cell cycle states, including G0. We demonstrate that the ccAFv2 classifier is generalizable across cell types and all three germ layers by applying it to developing fetal cells. We showcased the versatility of ccAFv2 by successfully applying it to classify cells, nuclei, and spatial transcriptomics data in humans and mice, using various normalization methods and gene identifiers. We provide methods to regress the cell cycle expression patterns out of single cell or nuclei data to uncover underlying biological signals. The classifier can be used either as an R package integrated with Seurat or a PyPI package integrated with scanpy. We proved that ccAFv2 has enhanced accuracy, flexibility, and adaptability across various experimental conditions, establishing ccAFv2 as a powerful tool for dissecting complex biological systems, unraveling cellular heterogeneity, and deciphering the molecular mechanisms by which proliferation and quiescence affect cellular processes.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).


