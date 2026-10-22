# PyTorch Project to Build a GAN Model on MNIST Dataset

1.

## Overview
Have you ever wondered how photo editing applications are able to convert night images to day images? Also, you must have come across some photos of people who do not exist in the world. One of the powerful tools to achieve this is Generative Adversarial Networks also known as GAN. The GANs are mainly used in image-to-image translation and to generate photorealistic images which even a human fails to identify as fake or true. In this project, we start by introducing Generative Adversarial Networks. The PyTorch framework is used to build the GAN model on the MNIST dataset. Finally, we learn how to use the Generator model for generating new images of digits.

## Approach
1. Introduction to Generative Adversarial Network
2. Introduction to Generator and Discriminator
3. Loss function in GAN
4. Buiding Model on PyTorch
5. Model training on Google Colab
6. Generating fake images with Generator

Prerequisites
1. Learn to Build Generative Models Using PyTorch Autoencoders
2. Learn How to Build PyTorch Neural Networks from Scratch

Modular code overview

Once you unzip the modular_code.zip file, you can find the following folders within it.
1. data
2. model
3. run.py
4. train.py
5. requirements.txt
1. The data folder contains data_utils.py file which is used to download and transform the data. It will download and store the data in the respective folder
2. The model folder contains gan.py
3. The train.py files contain the code for model training. The run.py is the main file in which all functions are called
4. GAN_Notebook_colab.ipynb is used to train the model on colab
5. The requirements.txt file has all the required libraries with respective versions. Kindly install the file by using the command pip install -r requirements.txt Note: please use cuda versions of torch if CUDA is available

## Tech stack
➔ Language: Python ➔ Libraries: torch, torchvision,numpy, matplotlib

## How to run
```bash
pip install -r GAN/requirements.txt
python GAN/run.py
python GAN/train.py
```
Notebooks: [`GAN_Notebook_colab.ipynb`](GAN/GAN_Notebook_colab.ipynb)

## Project structure
```
.gitignore
GAN/
  GAN_Notebook_colab.ipynb
  model/
    GAN.py
  requirements.txt
  run.py
  train.py
README.md
```

## Credits
Based on a ProjectPro guided project.
