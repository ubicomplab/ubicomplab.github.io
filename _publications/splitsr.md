---
title: 'SplitSR: An End-to-End Approach to Super-Resolution on Mobile Devices'
authors:
- liu_xin
- Yuang Li
- fromm
- yuntao
- Ziheng Jiang
- mariakakis
- patel
conference: Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT), 2021
date: 2021-02-01
pdf: /pdfs/splitsr.pdf
thumbnail: /images/pubs/splitsr.png
image: /images/pubs/splitsr.png
abstract: |
  Super resolution (SR) is a coveted image processing technique for mobile apps ranging from the basic camera apps to mobile health. Existing SR algorithms rely on deep learning models with significant memory requirements, so they have yet to be deployed on mobile devices and instead operate in the cloud to achieve feasible inference time. This shortcoming prevents existing SR methods from being used in applications that require near real-time latency. In this work, we demonstrate state-of-the-art latency and accuracy for on-device super-resolution using a novel hybrid architecture called SplitSR and a novel lightweight residual block called SplitSRBlock. The SplitSRBlock supports channel-splitting, allowing the residual blocks to retain spatial information while reducing the computation in the channel dimension. SplitSR has a hybrid design consisting of standard convolutional blocks and lightweight residual blocks, allowing people to tune SplitSR for their computational budget. We evaluate our system on a low-end ARM CPU, demonstrating both higher accuracy and up to 5 times faster inference than previous approaches. We then deploy our model onto a smartphone in an app called ZoomSR to demonstrate the first-ever instance of on-device, deep learning-based SR. We conducted a user study with 15 participants to have them assess the perceived quality of images that were post-processed by SplitSR. Relative to bilinear interpolation --- the existing standard for on-device SR --- participants showed a statistically significant preference when looking at both images (Z=-9.270, p<0.01) and text (Z=-6.486, p<0.01).

bibtex: |
  @article{liu2021splitsr,
    title={SplitSR: An End-to-End Approach to Super-Resolution on Mobile Devices},
    author={Liu, Xin and Li, Yuang and Fromm, Josh and Wang, Yuntao and Jiang, Ziheng and Mariakakis, Alex and Patel, Shwetak},
    journal={arXiv preprint arXiv:2101.07996},
    year={2021}
  }
---