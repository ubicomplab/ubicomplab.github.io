---
title: 'Heterogeneous Bitwidth Binarization in Convolutional Neural Networks'
authors:
- fromm
- patel
- Matthai Philipose
conference: Conference on Neural Information Processing Systems (NeurIPS 2018)
date: 2018-12-02
pdf: /pdfs/hbnns.pdf
thumbnail: /images/pubs/hbnns.png
abstract: |
    Recent work has shown that fast, compact low-bitwidth neural networks can be surprisingly accurate. These networks use homogeneous binarization: all parameters in each layer or (more commonly) the whole model have the same low bitwidth (e.g., 2 bits). However, modern hardware allows efficient designs where each arithmetic instruction can have a custom bitwidth, motivating heterogeneous binarization, where every parameter in the network may have a different bitwidth. In this paper, we show that it is feasible and useful to select bitwidths at the parameter granularity during training. For instance a heterogeneously quantized version of modern networks such as AlexNet and MobileNet, with the right mix of 1-, 2- and 3-bit parameters that average to just 1.4 bits can equal the accuracy of homogeneous 2-bit versions of these networks. Further, we provide analyses to show that the heterogeneously binarized systems yield FPGA- and ASIC-based implementations that are correspondingly more efficient in both circuit area and energy efficiency than their homogeneous counterparts.
bibtex: |
    @incollection{NIPS2018_7656,
    title = {Heterogeneous Bitwidth Binarization in Convolutional Neural Networks},
    author = {Fromm, Joshua and Patel, Shwetak and Philipose, Matthai},
    booktitle = {Advances in Neural Information Processing Systems 31},
    editor = {S. Bengio and H. Wallach and H. Larochelle and K. Grauman and N. Cesa-Bianchi and R. Garnett},
    pages = {4006--4015},
    year = {2018},
    publisher = {Curran Associates, Inc.},
    url = {http://papers.nips.cc/paper/7656-heterogeneous-bitwidth-binarization-in-convolutional-neural-networks.pdf}
    }

---
