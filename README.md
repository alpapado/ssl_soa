# State of the art methods for semi-supervised learning

## MNIST (number of misclassifications)
| Model / Unlabeled samples | 20 | 50 | 100 | 200 |
|---|---|---|---|---|
| [Deep Generative Models](https://arxiv.org/abs/1406.5298) | - | - | 333 +- 14 | - |
| [Virtual Adversarial](https://arxiv.org/abs/1507.00677) | - | - | 212 | - |
| [CatGAN](https://arxiv.org/abs/1511.06390) | - | - | 191 +- 10 | - |
| [Skip Deep Generative Model](https://arxiv.org/abs/1602.05473) | - | - | 132 +- 7 | - | 
| [Ladder Network](https://arxiv.org/abs/1507.02672) | - | - | 106 +- 37 | - |
| [Auxiliary Deep Generative Model](https://arxiv.org/abs/1602.05473) | - | - | 96 +- 2| - |
| [Improved GAN](https://arxiv.org/abs/1606.03498) | 1677 +- 452 | 221 +- 136 | 93 +- 6.5 | 90 +- 4.2 |
| [Bayesian GAN](https://arxiv.org/abs/1705.09558) | 997 +- 348 | 154 +- 89 | 89 +- 3.4 | 79 +- 1.4|
| [Bad GAN](https://arxiv.org/abs/1705.09783) | - | - | 79.5 +- 9.8 | - |
| [DRMM](https://arxiv.org/abs/1612.01936) | - | - | 57 | - | 
| [DRMM improved](https://arxiv.org/abs/1612.01942) | - | 91 |  57 |  |

## CIFAR-10 (test error rate)
| Model / Unlabeled samples | 1000 | 2000 | 4000 | 8000
|---|---|---|---|---|
| [DRMM](https://arxiv.org/abs/1612.01936) | - | - | 23.24 | - |
| [DRMM improved](https://arxiv.org/abs/1612.01942) | - | - |  21.50 | 17.16 |
| [Bayesian GAN](https://arxiv.org/abs/1705.09558) | 29.7 +- 3.2 | 25.4 +- 4.3 | 22.8 +-2.4 | 20.9 +- 1.8 |
| [Ladder Network](https://arxiv.org/abs/1507.02672) | - | - | 20.40 +- 0.47 | - |
| [CatGAN](https://arxiv.org/abs/1511.06390) | - | - | 19.58 + 0.46 | - |
| [Improved GAN](https://arxiv.org/abs/1606.03498) | 21.83 +- 2.01 | 19.61 +- 2.09 | 18.63 +- 2.32 | 17.72 +- 1.82 |
| [Bad GAN](https://arxiv.org/abs/1705.09783) | - | - | 14.41 +- 0.3 | - |
