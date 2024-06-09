# An exploration on Wasserstein GAN and a f-GAN
## 2024Spring CS231N Final Project
[link to project poster](CS231N_project_poster.pdf)

[link to project report](CS231N_project_report.pdf)

## Abstract
Generative Adversarial Nets (GAN) provides a straightforward yet effective method for image generation after learning from training data, and researchers have proposed variants under GAN framework. In this project I compare performances between Vanilla GAN, Wasserstein GAN (WGAN) and $f$-GAN, as the later two extend and generalize GAN implementations. Experimental results show that compared to vanilla GAN, WGAN and Pearson $\chi^2$ $f$-GAN have similar capacities on learning data distributions and generating, given features extracted by convolutional networks. This project also explores hyper parameter tuning for WGAN and the results emphasize importance of gradient clipping threshold.
## Acknowledgement

Data preprocessing, discriminator, and generator designs and codes reuse corresponding parts in assignment #3 of 2024Spring CS231N class.   