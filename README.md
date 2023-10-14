# Covid-19_classification_vgg16
COVID-19 Chest X-ray Images Classification Using VGG16 CNN on Google Colaboratory
# COVID-19 Chest X-ray Classification

![COVID-19 X-ray](xray_image.jpg)

This repository contains a deep learning project that focuses on classifying chest X-ray images for the detection of COVID-19 using a VGG16 Convolutional Neural Network (CNN) model. The project aims to contribute to the early diagnosis and monitoring of COVID-19 patients through AI-powered image analysis.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

In the wake of the COVID-19 pandemic, medical imaging has become a critical tool for diagnosis. This project leverages the power of deep learning to assist healthcare professionals in identifying COVID-19 cases in chest X-ray images. The VGG16 architecture is chosen for its proven effectiveness in image classification tasks.

## Dataset

The dataset used for training, valdation, evaluation is (https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database/data, which contains a diverse collection of chest X-ray images, including COVID-19 positive and negative cases. The dataset is divided into training, validation, and test sets to ensure model robustness.

## Model Architecture

We utilized a pre-trained VGG16 model as the backbone for this classification task. The model was built with Transfer Learning on our dataset and achieved excellent performance. Details on the model's architecture can be found in the [model directory](model/). You can view the model architecture diagram ![here](model/your-image.png).

## Results

Our trained model achieved a 93.75% accuracy, 94.5% precision, and 94% recall on the test dataset, demonstrating its effectiveness in COVID-19 detection.



## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

---

**Note:** Always follow ethical guidelines and ensure proper permissions and consents when working with medical data.

For more information or inquiries, please contact [Aisy Nahdah](mailto:nidanahdah@gmail.com).
