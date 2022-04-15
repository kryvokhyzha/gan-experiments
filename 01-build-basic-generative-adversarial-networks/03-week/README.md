# Wasserstein GANs with Gradient Penalty

## (Optional Notebook) ProteinGAN

_Please note that this is an optional notebook that is meant to introduce more advanced concepts, if you're up for a challenge. So, don't worry if you don't completely follow every step! We provide external resources for extra base knowledge required to grasp some components of the advanced material._

The goal of this notebook is to demonstrate that core GAN ideas can be applied outside of the image domain. In this notebook, you will be able to play around with a pre-trained ProteinGAN model to see how it can be used in bioinformatics to generate functional molecules.

+ [Notebook link](https://colab.research.google.com/github/https-deeplearning-ai/GANs-Public/blob/master/ProteinGAN.ipynb)

[ProteinGAN](https://www.biorxiv.org/content/10.1101/789719v2) was developed by [Biomatters Designs](https://www.biomatterdesigns.com/) and [Zelezniak lab at Chalmers University of Technology](https://twitter.com/AZelezniak).

## (Optional) The DCGAN Paper

Curious about the paper behind the deep convolutional GAN (DCGAN) you just implemented? Check out the paper!

+ [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks (Radford, Metz, and Chintala, 2016)](https://arxiv.org/abs/1511.06434)

## (Optional) The WGAN and WGAN-GP Papers

Interested in the papers behind the Wasserstein GAN with Gradient Penalty (WGAN-GP) you just implemented? Check them out! The first paper is the original WGAN paper and the second proposes GP (as well as weight clipping) to WGAN in order to enforce 1-Lipschitz continuity and improve stability.

+ [Wasserstein GAN (Arjovsky, Chintala, and Bottou, 2017)](https://arxiv.org/abs/1701.07875)
+ [Improved Training of Wasserstein GANs (Gulrajani et al., 2017)](https://arxiv.org/abs/1704.00028)

## (Optional) WGAN Walkthrough

Want another explanation of WGAN? This article provides a great walkthrough of how WGAN addresses the difficulties of training a traditional GAN with a focus on the loss functions.

+ [From GAN to WGAN (Weng, 2017)](https://lilianweng.github.io/lil-log/2017/08/20/from-GAN-to-WGAN.html)
