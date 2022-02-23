## VAN-Jittor

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
1.use pytorch to convert van parameters downloaded from: https://cloud.tsinghua.edu.cn/f/58e7acceaf334ecdba89/?dl=1 and follow the instructions in train_cub.py to transform it to pth file.
2.python train_cub.py
```


## Acknowledgment

This repo is supported by [Jimm](https://github.com/Jittor-Image-Models/Jittor-Image-Models) which is developed and maintained by Yang Shen, Xuhao Sun and Prof Xiu-Shen Wei.