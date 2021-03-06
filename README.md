# O-CNN

<!-- ## Introduction <a name="introduction"></a> -->

This repository contains the implementation of *O-CNN*  and  *Adaptive O-CNN* 
introduced in our SIGGRAPH 2017 paper and SIGGRAPH Asia 2018 paper.  
The code is released under the **MIT license**.

- **[O-CNN: Octree-based Convolutional Neural Networks](https://wang-ps.github.io/O-CNN.html)**<br/>
  By [Peng-Shuai Wang](https://wang-ps.github.io/), [Yang Liu](https://xueyuhanlang.github.io/), 
  Yu-Xiao Guo, Chun-Yu Sun and [Xin Tong](https://www.microsoft.com/en-us/research/people/xtong/) <br/>
  ACM Transactions on Graphics (SIGGRAPH), 36(4), 2017

- **[Adaptive O-CNN: A Patch-based Deep Representation of 3D Shapes](https://wang-ps.github.io/AO-CNN.html)**<br/>
By [Peng-Shuai Wang](https://wang-ps.github.io/), Chun-Yu Sun, [Yang Liu](https://xueyuhanlang.github.io/) 
and [Xin Tong](https://www.microsoft.com/en-us/research/people/xtong/)<br/>
ACM Transactions on Graphics (SIGGRAPH Asia), 37(6), 2018<br/>

- **[Deep Octree-based CNNs with Output-Guided Skip Connections for 3D Shape and Scene Completion](https://arxiv.org/abs/2006.03762)**<br/>
By [Peng-Shuai Wang](https://wang-ps.github.io/), [Yang Liu](https://xueyuhanlang.github.io/) 
and [Xin Tong](https://www.microsoft.com/en-us/research/people/xtong/)<br/>
Computer Vision and Pattern Recognition (CVPR) Workshops, 2020<br/>

- **[Unsupervised 3D Learning for Shape Analysis via Multiresolution Instance Discrimination](https://arxiv.org/abs/2008.01068)**<br/>
By [Peng-Shuai Wang](https://wang-ps.github.io/), Yu-Qi Yang, Qian-Fang Zou, 
[Zhirong Wu](https://www.microsoft.com/en-us/research/people/wuzhiron/), 
[Yang Liu](https://xueyuhanlang.github.io/) 
and [Xin Tong](https://www.microsoft.com/en-us/research/people/xtong/)<br/>
Arxiv preprint, 2020<br/>

If you use our code or models, please [cite](docs/citation.md) our paper.


### What's New?

- 2020.10.12: Release the initial version of our O-CNN under PyTorch. The code
  has been tested with the [classification task](docs/classification.md#o-cnn-on-pytorch).
- 2020.08.16: We released our code for [3D unsupervised learning](docs/unsupervised.md).
  We provided a unified network architecture for generic shape analysis tasks and 
  an unsupervised method to pretrain the network. Our method achieved state-of-the-art 
  performance on several benchmarks.
- 2020.08.12: We released our code for 
  [Partnet segmentation](docs/segmentation.md#shape-segmentation-on-partnet-with-tensorflow).
  We achieved  an average IoU of **58.4**, significantly better than PointNet
  (IoU: 35.6), PointNet++ (IoU: 42.5), SpiderCNN (IoU: 37.0), and PointCNN(IoU:
  46.5).
- 2020.08.05: We released our code for [shape completion](docs/completion.md).
  We proposed a simple yet efficient network and output-guided skip connections
  for 3D completion, which achieved state-of-the-art performances on several 
  benchmarks.
- 2020.03.16: We released ResNet-based O-CNN architecture for 
  [shape classification](docs/classification.md#o-cnn-on-tensorflow).
  We achieved a testing accuracy of **92.5** on ModelNet40 (without voting).



### Contents
- [Installation](docs/installation.md)
- [Data Preparation](docs/data_preparation.md)
- [Shape Classification](docs/classification.md)
- [Shape Retrieval](docs/retrieval.md)
- [Shape Segmentation](docs/segmentation.md)
- [Shape Autoencoder](docs/autoencoder.md)
- [Shape Completion](docs/completion.md)
- [Image2Shape](docs/image2shape.md)



We thank the authors of [ModelNet](http://modelnet.cs.princeton.edu), 
[ShapeNet](http://shapenet.cs.stanford.edu/shrec16/) and 
[Region annotation dataset](http://cs.stanford.edu/~ericyi/project_page/part_annotation/index.html) 
for sharing their 3D model datasets with the public.

Please contact us (Pengshuai Wang wangps@hotmail.com, Yang Liu yangliu@microsoft.com ) 
if you have any problems about our implementation.  

