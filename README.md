# Image Colourization using GAN

This project is the final project for the course "Generative AI" organized by EduNet Foundation. It aims to colorize grayscale images using Generative Adversarial Networks (GANs). GANs consist of two neural networks, a generator, and a discriminator, competing against each other to generate realistic images. 

## Getting Started

To run the project, make sure you have the required libraries installed. You can install them using pip:

```bash
pip install numpy h5py pandas matplotlib opencv-python keras scikit-learn
```

## Prerequisites

You need to have Python installed on your system. The code is intended to run in a Jupyter Notebook environment.

## Dataset

This project uses the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes. The dataset is divided into 50,000 training images and 10,000 testing images.
The Dataset is not uploaded manually instead directly loaded using keras.dataset library

## Running the Code

To run the code, open the provided Jupyter Notebook ImageColourization.ipynb and execute each cell sequentially.
