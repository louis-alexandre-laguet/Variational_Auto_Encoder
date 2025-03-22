# Implementation of Autoencoders and Variational Autoencoders (VAE)

This repository contains three notebooks implementing autoencoders and variational autoencoders (VAE) on the Fashion MNIST and CelebA datasets. These exercises allow exploration of the concepts of image compression, reconstruction, and generation of new images using autoencoders.

## Repository Content

### 1. Autoencoders on Fashion MNIST
**Objectives:**
- Load and visualize the Fashion MNIST dataset.
- Build an autoencoder using convolutional layers.
- Train the autoencoder and evaluate its performance.
- Extract and visualize the latent embeddings.
- Perform image reconstruction and generate new images.

### 2. Variational Autoencoders (VAE) on Fashion MNIST
**Objectives:**
- Load the Fashion MNIST dataset and resize images from 28x28 to 32x32.
- Create DataLoaders for training and validation.
- Visualize a sample of images to verify data integrity.
- Understand the importance of padding and transformations such as normalization.
- Manage batch organization for efficient training.
- Implement and train a VAE for image reconstruction and generation.

### 3. Variational Autoencoders (VAE) on CelebA
**Objectives:**
- Obtain and organize the CelebA dataset.
- Prepare images: resize to 32x32, convert to tensors, and normalize.
- Create a DataLoader with batch_size and shuffle=True for optimal training.
- Visualize a batch of images to ensure proper data loading.
- Implement a VAE to learn the distribution of human faces and generate new images.
