# deep-person-reid
This repo contains [pytorch](http://pytorch.org/) implementations of deep person re-identification approaches.

We will actively maintain this repo.

## Pretrained models
## Prepare data
## Train
## Test
## Results
xent: cross entropy + label smoothing regularizer [5]
htri: triplet loss with hard positive/negative mining [4]
### Market1501

| Model | Size (M) | Loss | Rank-1 / -5 / -10 (%) | mAP (%) | Reported Rank | Reported mAP |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| ResNet50 [1] | 25.05 | xent | 85.8 / 94.4 / 96.3 | 70.1 | | |
| ResNet50M [2] | 30.01 | xent | 88.8 / 95.3 / 97.0 | 74.4 | 89.9 / - / -  | 75.6 |
| DenseNet121 [3] | 7.72 | xent | | | | |

## References
[1] [He et al. Deep Residual Learning for Image Recognition. CVPR 2016.](https://arxiv.org/abs/1512.03385)<br />
[2] [Yu et al. The Devil is in the Middle: Exploiting Mid-level Representations for Cross-Domain Instance Matching. arXiv:1711.08106.](https://arxiv.org/abs/1711.08106) <br />
[3] [Huang et al. Densely Connected Convolutional Networks. CVPR 2017.](https://arxiv.org/abs/1608.06993) <br />
[4] [Hermans et al. In Defense of the Triplet Loss for Person Re-Identification. arXiv:1703.07737.](https://arxiv.org/abs/1703.07737) <br />
[5] [Szegedy et al. Rethinking the Inception Architecture for Computer Vision. CVPR 2016.](https://arxiv.org/abs/1512.00567) <br />