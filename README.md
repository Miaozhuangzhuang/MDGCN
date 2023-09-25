 # MDGCN
Official PyTorch Implementation of Multi-Level Dynamic Graph Convolutional Networks for Weakly Supervised Crowd Counting, .
![image](MDGCN.png)

## Abstract
Crowd counting is very important in many fields such as public safety, urban planning, and is essential for the intelligent transportation systems. Due to the complexity and diversity of traffic scenes, point-level annotations for pedestrians would cost much human labor. Weakly-supervised crowd counting methods are more suitable for these scenes, considering they only require count-level annotations. However, ignoring the uneven distribution of cross-distance crowd region density and multi-scale pedestrian head, existing weakly supervised methods can not achieve similar counting performance as fully supervised crowd counting methods. To solve these issues, we propose a novel multi-level dynamic graph convolutional networks for weakly supervised crowd counting. Within this network, a multi-level region dynamic graph convolutional module is designed to mine the cross-distance intrinsic relationship between crowd regions. A feature enhancement module is used to enhance crowd semantic information. In addition, we design a coarse grained multi-level feature fusion module to aggregate multi-scale pedestrian information. Experiments are conducted on five well-known benchmark crowd counting datasets, achieving state-of-the-art results compared to existing weakly supervised methods and competitive results compared to fully supervised methods.

## Training
1. We have provided the MDGCN model file, MDGCN.py.
2. You can obtain other files from [TransCrowd](https://github.com/dk-liang/TransCrowd), and modify the sub image size in data preprocessing (224×224→384×384).
3. You can follow the steps of TransCrowd for training.

## Citation
If you find this project is useful for your research, please cite:
```
@article{miao2023mdgcn,
  title={Multi-Level Dynamic Graph Convolutional Networks for Weakly Supervised Crowd Counting},
  author={Zhuangzhuang Miao and Yong Zhang and Hao Ren and Yongli Hu and Baocai Yin},
  journal={},
  year={2023},
  publisher={}
}
```

## Acknowlegement
1. We sincerely thank the authors of [TransCrowd](https://github.com/dk-liang/TransCrowd) for open sourcing their methods.
2. We are very grateful for [Awesome-Crowd-Counting's](https://github.com/gjy3035/Awesome-Crowd-Counting) contribution to the field of crowd counting!

