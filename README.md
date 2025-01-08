# Image Reconstruction of CIFAR Dataset

This project demonstrates image reconstruction techniques on the CIFAR-10 dataset, a collection of 60,000 32x32 color images in 10 different classes. The goal is to implement and evaluate methods for reconstructing images using advanced deep learning architectures.

## Overview
Image reconstruction involves generating an output image that closely resembles the original input image. This is often used in applications such as image denoising, super-resolution, and image compression. In this project, we:

1. Preprocess the CIFAR-10 dataset for reconstruction tasks.
2. Design and train deep learning models to perform image reconstruction.
3. Evaluate the performance of the models using various metrics.

## Dataset
The [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) consists of:
- 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
- 50,000 training images
- 10,000 test images

The dataset is widely used for image classification, segmentation, and reconstruction tasks.

## Features
- Preprocessing pipeline for CIFAR-10 images.
- Implementation of autoencoders and other reconstruction models.
- Custom loss functions for optimizing reconstruction quality.
- Evaluation metrics 
- Utilized optimizers such as Adam and AdamW.
- Employed MSE (Mean Squared Error) as the loss function.
- Adjusted the number of layers in the models to minimize loss.
- Trained models for 20 epochs.

## Installation
To run this project, clone the repository and install the required dependencies:


# Clone the repository
git clone https://github.com/raj22bh/Image-Reconstruction-of-CIFAR-dataset.git

# Navigate to the project directory
cd Image-Reconstruction-of-CIFAR-dataset



## Results
Key results include:
- High-quality image reconstructions from corrupted or low-resolution inputs.
- Evaluation demonstrating the performance of the models.

## Future Work
- Extend the project to support CIFAR-100 or other datasets.
- Implement GAN-based image reconstruction techniques.
- Incorporate transfer learning for improved performance.

## Contributions
Feel free to contribute to this project by submitting issues or pull requests. For major changes, please open an issue first to discuss your proposed changes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For questions or feedback, please contact [Raj](https://github.com/raj22bh).

