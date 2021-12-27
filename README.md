# SITT
The repo contains official PyTorch Implementation of the paper [Single Image Texture Translation for Data Augmentation](https://arxiv.org/abs/2106.13804).

#### Authors: 
* [Boyi Li](https://sites.google.com/site/boyilics/home)
* [Yin Cui](https://scholar.google.com/citations?hl=zh-CN&user=iP5m52IAAAAJ)
* [Tsung-Yi Lin](https://scholar.google.com/citations?hl=zh-CN&user=_BPdgV0AAAAJ)
* [Serge Belongie](https://scholar.google.com/citations?user=ORr4XJYAAAAJ&hl=zh-CN)



### Overview

Recent advances in image synthesis enables one to translate images by learning the mapping between a source domain and a target domain. Existing methods tend to learn the distributions by training a model on a variety of datasets, with results evaluated largely in a subjective manner. Relatively few works in this area, however, study the potential use of semantic image translation methods for image recognition tasks. In this paper, we explore the use of Single Image Texture Translation (SITT) for data augmentation. We first propose a lightweight model for translating texture to images based on a single input of source texture, allowing for fast training and testing. Based on SITT, we then explore the use of augmented data in long-tailed and few-shot image classification tasks. We find the proposed method is capable of translating input data into a target domain, leading to consistent improved image recognition performance. Finally, we examine how SITT and related image translation methods can provide a basis for a data-efficient, augmentation engineering approach to model training.

## Usage
### Environment
CUDA 10.1, pytorch 1.3.1

### Running 
`bash run.sh`

More will be updated.

If you find this repo useful, please cite:
```
@article{li2021single,
  title={Single Image Texture Translation for Data Augmentation},
  author={Li, Boyi and Cui, Yin and Lin, Tsung-Yi and Belongie, Serge},
  journal={arXiv preprint arXiv:2106.13804},
  year={2021}
}
```

