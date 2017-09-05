# Train CIFAR10 with PyTorch with SGDR

Built from `kuangliu`'s great simple
[pytorch-cifar](https://github.com/kuangliu/pytorch-cifar) repository.
Switches out the manual learning rate scheduling for [SGDR][]. Used the
anytime schedule reported best in the paper. So far, trained for 147 epochs
on ResNet18 and 93.99%.

## Accuracy
| Model             | Acc. Before | SGDR Acc. |
| ----------------- | ----------- | --------- |
| [VGG16](https://arxiv.org/abs/1409.1556)             | 92.64%      | ? |
| [ResNet18](https://arxiv.org/abs/1512.03385)          | 93.02%      | 93.99 % |
| [ResNet50](https://arxiv.org/abs/1512.03385)          | 93.62%      | ? |
| [ResNet101](https://arxiv.org/abs/1512.03385)         | 93.75%      | ? |
| [ResNeXt29(32x4d)](https://arxiv.org/abs/1611.05431)  | 94.73%      | ? |
| [ResNeXt29(2x64d)](https://arxiv.org/abs/1611.05431)  | 94.82%      | ? |
| [DenseNet121](https://arxiv.org/abs/1608.06993)       | 95.04%      | ? |
| [ResNet18(pre-act)](https://arxiv.org/abs/1603.05027) | 95.11%      | ? |
| [DPN92](https://arxiv.org/abs/1707.01629)             | 95.16%      | ? |

