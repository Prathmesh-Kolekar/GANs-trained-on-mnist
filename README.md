---

# Generative Adversarial Networks (GANs) on Fashion MNIST

This project involves training Generative Adversarial Networks (GANs) on the MNIST handwritten digits dataset to generate images of handwritten digits similar to those in the dataset. GANs consist of two neural networks, a generator and a discriminator, that are trained together to produce realistic synthetic data.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Description
Generative Adversarial Networks (GANs) are a class of machine learning frameworks designed by Ian Goodfellow and his colleagues in 2014. This project applies GANs to the MNIST dataset, which consists of 70,000 grayscale images of 28x28 pixels each, divided into 60,000 training images and 10,000 test images. The dataset includes images of handwritten digits from 0 to 9.

## Installation
To get started with this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Prathmesh-Kolekar/GANs-trained-on-mnist.git
    cd GANs-trained-on-mnist
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To train the GAN on the Fashion MNIST dataset, run the provided Jupyter notebook:

1. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open `GANs_notebook.ipynb` and run all cells.

The notebook will guide you through the process of training the GAN and generating new fashion item images.

## Dependencies
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

Make sure to install the dependencies using the provided `requirements.txt` file.


---
