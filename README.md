# LVDM

The LVDM dataset is introduced in our paper titled “STD-Net: Spatio-Temporal Decomposition Network for Video Demoiréing with Sparse Transformers,” published in the IEEE Transactions on Circuits and Systems for Video Technology (TCSVT) in 2024.

## Overview

We propose the large-scale video demoiréing dataset (LVDM) for training and evaluating the video demoiréing methods. This dataset comprises over 3,500 pairs of 720p clean and moiré videos, each consisting of 30 frames, resulting in a total of over 100,000 frames. For LVDM, 93% videos in the dataset are used for training, and the remaining 7% are used for testing. The clean videos are sourced from the visual tracking dataset GOT-10k, which features diverse scenes from YouTube, such as land, sea, and cities, providing a rich variety of real-world scenarios.



![](README_md_files/c001b9f0-ec42-11ef-bb40-9f2736ce15ef.jpeg?v=1&type=image)

Figure 1 Two examples from the LVDM dataset. Each row represents three adjacent frames, and red circles highlight areas of prominent change between frames. Apart from moiré patterns, the video content in adjacent frames of LVDM typically undergo significant changes, posing greater challenges for maintaining temporal consistency with adjacent frames.
