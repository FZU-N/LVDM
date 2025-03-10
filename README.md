# LVDM: Large-Scale Video Demoiréing Dataset

[paper](https://ieeexplore.ieee.org/abstract/document/10495363) | [supplementary materials](https://pan.baidu.com/s/1YaY8QpLyx_RnM-0gc7Ln2w?pwd=n6x2) | [LVDM dataset](https://pan.baidu.com/s/1zrwacxO_TUWtvPx927PxYA?pwd=27ym)

LVDM is introduced in our paper **“STD-Net: Spatio-Temporal Decomposition Network for Video Demoiréing with Sparse Transformers”**, published in *IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)* *2024*. In this paper, we also provide both experimental and theoretical proof of the sparsity of moiré patterns, which can be found in the supplementary materials.

LVDM is available for download via [Baidu Netdisk](https://pan.baidu.com/s/1zrwacxO_TUWtvPx927PxYA?pwd=27ym), offering access to both the **full dataset** （~30G）and its **separated subsets** (including ~27 GB for the training set and ~2G for the testing set).

## Overview

LVDM is a **large-scale dataset** designed for training and evaluating video demoiréing methods. It consists of **over 3,500 pairs** of 720p clean and moiré videos, each containing 30 frames, resulting in a total of more than 100,000 frames. The dataset is split into **93% for training** and **7% for testing**.

The clean videos in LVDM are sourced from the GOT-10k visual tracking dataset, which features a diverse range of real-world scenes from YouTube, including landscapes, urban environments, and ocean views. This diversity enhances the dataset’s applicability to various real-world demoiréing scenarios.

### Examples

The image below illustrates sample frames from LVDM. Each row represents three adjacent frames, with red circles highlighting regions of significant change between frames. Beyond moiré patterns, the video content itself exhibits substantial variations between adjacent frames, making temporal consistency a greater challenge for video demoiréing models.

![](README_md_files/43712ff0-ec43-11ef-bb40-9f2736ce15ef.jpeg?v=1&type=image)

## Citation

We sincerely thank the GOT-10k dataset for providing the clean video sources used in LVDM. For any commercial use, please reach out to them for permission.

```
@article{GOT-10k,
  title={Got-10k: A Large High-diversity Benchmark for Generic Object Tracking in the Wild},
  author={Huang, Lianghua and Zhao, Xin and Huang, Kaiqi},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
  volume={43},
  number={5},
  pages={1562--1577},
  year={2019},
  publisher={IEEE}
}
```



To cite our dataset or the proposed method, please use the following reference:

```markup
@ARTICLE{STDNet,
author={Niu, Yuzhen and Xu, Rui and Lin, Zhihua and Liu, Wenxi},
journal={IEEE Transactions on Circuits and Systems for Video Technology},
title={STD-Net: Spatio-Temporal Decomposition Network for Video Demoiréing With Sparse Transformers},
year={2024},
volume={34},
number={9},
pages={8562-8575},
}
```

