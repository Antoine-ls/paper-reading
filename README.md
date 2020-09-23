# paper-reading
This repository is created to record paper reading of medical group in SPEIT

Tips:< br > and to change line and [name](link) for link.

Paper | Summary |  Source   
:-: | :-: | :-: 
[U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/pdf/1505.04597.pdf) | Based on FCN, authors propose a fully convolutional network for biomedical segmentation, consisting of contracting and expanding path. | Miccai2015
Multi-view Learning with Feature Level Fusion for Cervical Dysplasia Diagnosis |  A feature fusion method between two modalities. | Miccai2019 |
IRNet: Instance Relation Network for Overlapping Cervical Cell Segmentation | Proposed an IRM (instance relation module) to build instance relation matrix for reducing overlapping impact | Miccai2019 |
[Deep Semantic Segmentation of Natural and Medical Images: A Review](https://arxiv.org/abs/1910.07655) | Summary of currently used networks, architectures, Loss functions etc. in semantic segmentation of natural and medical images  |   |
Code Reading: Coco Eval| look into details of cocoeval used in torchvision/reference/detection. |  |
[EfficientDet: Scalable and Efficient Object Detection](https://arxiv.org/abs/1911.09070) | Lightweight detection model based on efficientNet and BiFPN | CVPR2020  |
[EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](https://arxiv.org/abs/1905.11946) | A family of CNN. Sota level, very few FLOPS | ICML 2019

Multi-modal Paper | Summary |  Source   
:-: | :-: | :-: 
[MMTM: Multimodal Transfer Module for CNN Fusion](https://arxiv.org/pdf/1911.08670.pdf) | The input is data from multi-modal separately. The output depends on the task. This is not entirely new problem but quite challenging as multi-modal data is important in different case like auto-driving and medical. The hypothesis is that if we add MMTM in the network, the performance is better than simple early/middle/late fusion. The key proposed solution is a SE(squeeze and excitation) module which computes an attention vector for each feature map. The experiment is conducted on several multi-modal tasks including Hand gesture recognition, audio-visual speech enhancement and human action recognition and the results support the hypothesis. | CVPR2020 |





