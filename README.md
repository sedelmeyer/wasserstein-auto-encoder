# An Introduction to the Wasserstein auto-encoder

Authors:

- [Joel Dapello](https://github.com/dapello)
- [Michael Sedelmeyer](https://github.com/sedelmeyer)
- [Wenjun Yan](https://github.com/Wenjun-Yan)

This repository contains a brief tutorial inspired by the paper "[Wasserstein Auto-Encoders](https://arxiv.org/pdf/1711.01558.pdf)" by Tolstikhin, Bousquet, Gelly & Schölkopf (2017)

In this tutorial, we compare model frameworks for the generative adversarial network (GAN) formulation of the Wasserstein auto-encoder (WAEgan), the basic non-stochastic auto-encoder (AE), and the variational auto-encoder (VAE). To accomplish this, we implement each model in PyTorch as a convolutional auto-encoder similar to the popular DCGAN model and compare results with the MNIST and FashionMNIST datasets.
