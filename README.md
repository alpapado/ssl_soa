# ssl_soa
State of the art methods for semi-supervised learning

## MNIST
| Model / Unlabeled samples | 20 | 50 | 100 | 200 |
|---|---|---|---|---|
| Deep Generative Models | - | - | 333 +- 14 | - |
| Virtual Adversarial | - | - | 212 | - |
| CatGAN | - | - | 191 +- 10 | - |
| Skip Deep Generative Model | - | - | 132 +- 7 | - | 
| Auxiliary Deep Generative Model | - | - | 96 +- 2| - |
| Improved GAN | 1677 +- 452 | 221 +- 136 | 93 +- 6.5 | 90 +- 4.2 |
| Bayesian GAN | 997 +- 348 | 154 +- 89 | 89 +- 3.4 | 79 +- 1.4|
| Bad GAN | - | - | 79.5 +- 9.8 | - |
| Deep Rendering MIxture Model | - | - | 57 | - | 


## CIFAR-10
| Model / Unlabeled samples | 1000 | 2000 | 4000 | 8000
|---|---|---|---|---|
| CatGAN | - | - | 19.58 + 0.46 | - |
| Improved GAN | 21.83 +- 2.01 | 19.61 +- 2.09 | 18.63 +- 2.32 | 17.72 +- 1.82 |
| Bayesian GAN | 29.7 +- 3.2 | 25.4 +- 4.3 | 22.8 +-2.4 | 20.9 +- 1.8 |
| Bad GAN | - | - | 14.41 +- 0.3 | - |
| Deep Rendering Mixture Model | - | - | 23.24 | - |
| DRMM improved | - | - |  21.50 | 17.16 |
