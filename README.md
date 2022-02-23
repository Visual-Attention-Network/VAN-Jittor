This is a Jittor implementation of VAN proposed by our paper "Visual Attention Network". We will conduct experiment on CUB classification dataset. 

CUB is a widely-used dataset for fine-grained visual categorization task.

## Requirement 

1. Jittor
2. Jimm
3. pytorch==1.12.0

## Results

| VAN-Base | 87.6 |
| -------- | ---- |

More results will come soon,imagenet-1K pretrianed weight can be loaded in [Here](https://github.com/Visual-Attention-Network/VAN-Classification).



## Train 
```
1.download van parameters from: https://cloud.tsinghua.edu.cn/f/58e7acceaf334ecdba89/?dl=1 
2.follow the instructions in train_cub.py to transform it to pth file.
3.download CUB dataset from http://www.vision.caltech.edu/visipedia-data/CUB-200-2011/CUB_200_2011.tgz
4.python train_cub.py (need to edit the path of CUB dataset)
```


## Acknowledgment

This repo is supported by [Jimm](https://github.com/Jittor-Image-Models/Jittor-Image-Models) which is developed and maintained by Yang Shen, Xuhao Sun and Prof Xiu-Shen Wei.