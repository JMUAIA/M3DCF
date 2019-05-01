### Introduction

In this project, we design a new strategy called M3DCF that acts as a more eﬀective alternative to previous approaches for lesion detection. First, we adopt a one-stage detector to enable the network is faster and simpler. And which gives rise to eﬀective results.Second, for characteristics of computed tomography (CT) scans, we propose a novel feature fusion strategy based on 3D context to suﬃciently fuse the extracted feature of multiple neighboring slices.Third, based on our 3D context fusion strategy, the multi-scale strategy allows us to get more meaningful semantic information, and it obviously improves the performance on the test set of DeepLesion database.The experimental results conducted on DeepLesion dataset indicates that the proposed method surpass the accuracy of the mainstream algorithms such as Faster R-CNN, RetinaNet, and 3DCE, while still being faster.

For more details, this method was initially described in our paper ***Multi-scale Convolutional Neural Network Based on 3D Context Fusion for Lesion Detection***.

As shown in our GitHub, we released our model first, and the rest will follow. Our algorithm designed on the framework of darknet, and the model of which is available on BaiduYun.

Link: https://pan.baidu.com/s/1dIiLGrG6un5HJlNNxma3vg 
Code: 4usk 

### Dataset

Our experiments all conducted on DeepLesion database, which is available at https://nihcc.box.com/v/DeepLesion. The DeepLesion database was mined from a hospital’s picture archiving and communication system (PACS) based on bookmarks, which are markers annotated by radiologists during their daily work to highlight signiﬁcant image ﬁndings. It is a large-scale dataset with 32,735 lesions on 32,120 axial slices from 10,594 CT studies of 4,427 unique patients. Diﬀerent from existing datasets that typically focus on one type of lesion, DeepLesion contains a variety of lesions including those in lungs, livers, kidneys, etc.

### Network

![](https://p.qlogo.cn/qqmail_head/et9q9FvjBBrcXx3lpwC3XtWhjiaVLHBYibupOtc8DGKT9sQdgaCjHArp7ibfKE4sXe6powBxnnWCyM/0)

### Example

The image as follow shows the comparison result of all algorithms.

![](https://p.qlogo.cn/qqmail_head/PiajxSqBRaELBocS8gagFulBibnMkxOgyrsz1iccAssm85xdGdEL9XE40prEWgF7pFsc6ozvZ4uIpM/0)

### Experiment

The Precision-Recall curve of all algorithms is shown as follow.

![](https://p.qlogo.cn/qqmail_head/eK0ef1rxvqja3FicgpkXOSiak4td0xClWWahX4YGJLbaZ6u0x8vt2Xrouoqqukp90H/0)

 The table shows the mAPs and the APs of all algorithms.

![](https://p.qlogo.cn/qqmail_head/ajNVdqHZLLD5xKj3EK4cabYd9v6QibnicPs9a3PT3cexODcXfThdySJJiasuSY5Zs0IGbDTLBibU5UE/0)

