# CIFAR-10 Generative Adversarial Network (GAN) Project

This project implements various Generative Adversarial Network (GAN) architectures for generating images from the CIFAR-10 dataset. The supported architectures include Deep Convolutional GAN (DCGAN), Conditional GAN (CGAN), Spectral Normalization GAN (SNGAN), and Auxiliary Classifier GAN (ACGAN).

## Overview

Generative Adversarial Networks (GANs) are a class of artificial intelligence algorithms used in unsupervised machine learning, implemented by a system of two neural networks competing against each other in a zero-sum game framework. In this project, we explore different GAN architectures to generate realistic images resembling those from the CIFAR-10 dataset.

## Architectures

1. **Deep Convolutional GAN (DCGAN)**: An architecture employing convolutional networks for both the generator and discriminator, introduced by Radford et al. in 2015.
   
2. **Conditional GAN (CGAN)**: Extends the GAN framework by conditioning both the generator and discriminator on some additional information, such as class labels, to control the generated outputs.

3. **Spectral Normalization GAN (SNGAN)**: A variant of GAN that applies spectral normalization to stabilize the training process, introduced by Miyato et al. in 2018.

4. **Auxiliary Classifier GAN (ACGAN)**: A GAN architecture that incorporates label information into both the generator and the discriminator, introduced by Odena et al. in 2017.

## Usage

```bash
git clone https://github.com/yourusername/cifar10-gan-project.git
cd cifar10-gan-project
pip install -r requirements.txt
