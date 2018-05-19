Wasserstein GAN
===

A PyTorch implementation of Wasserstein GAN (WGAN) paper. This project is trying to reproduce the LSUN and CIFAR10 experiments for educational purposes.

In this project, we can also see how Deep Convolutional Generative Adversarial Network (DCGAN) evolved to WGAN.

Note: DCGAN was implemented using Keras 1 initally and migrated to Keras 2.


# Jupyter Notebooks

- [WGAN trained on LSUN dataset](wgan-pytorch-lsun-dataset.ipynb)
    - PyTorch
    - LSUN bedroom dataset
    - scripts to download and pre-process LSUN LMDB data
- [WGAN trained on CIFAR10](wgan-pytorch.ipynb)
    - PyTorch
    - CIFAR10
- [From the original GAN to MLP GAN to DCGAN](dcgan.ipynb)
    - Keras 2
    - MNIST
    
# Pre-trained Model

- PyTorch weights file:
    - [Generator](wgan_samples/netG_epoch_1.pth)
    - [Discriminator](wgan_samples/netD_epoch_1.pth)

# Generated Image Samples

- [Generated sample after 2 epochs](wgan_samples/fake_samples_17500.png)
- [Real sample](wgan_samples/real_samples.png)
- More generated samples in the [wgan_samples directory](wgan_samples)