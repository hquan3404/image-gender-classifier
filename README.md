# image-gender-classifier

A computer vision project for automatic gender classification from face images. This repository contains three different deep learning model implementations—Simple CNN, ResNet-18, and EfficientNet-B0—along with training, evaluation, and inference scripts.

---

## Models & Architectures

- **Simple CNN**  
  - A custom 5-layer convolutional network (Conv → ReLU → Pool blocks)  
  - Lightweight, designed for quick experimentation on small datasets

- **ResNet-18**  
  - A standard 18-layer residual network  
  - Uses pretrained ImageNet weights with fine-tuning of the final layers

- **EfficientNet-B0**  
  - State-of-the-art EfficientNet backbone (B0 variant)  
  - Pretrained on ImageNet, with adaptive pooling and a custom classification head

---