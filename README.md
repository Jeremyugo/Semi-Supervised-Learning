# Semi-Supervised Learning using Sklearn & Tensorflow

This repository contains a short notebook detailing techniques for performing semi-supervised learning. The main libraries used are `Sklearn` & `Tensorflow`.

![image](https://github.com/user-attachments/assets/711ba47d-180c-4374-b8fa-859dee9cb4fa)

## Data
The dataset used is keras' Fashion Mnist dataset, mainly because of it is high dimensional and simple (has no complex features). The dataset consists of 28 x 28 pixel images that were flattened.

## Techniques
The main techniques used are:
1. LabelPropagation & LabelSpreading
2. Self-Training Classification
3. Deep neural network + Autoencoders for Unsupervised pre-training


### Model performance (f1-score)
| S/N | Technique                             | f1-score |
|-----|---------------------------------------|----------|
|  1. | DNN + Autoencoder                     | 0.81     |
|  2. | Self-training classifier (RandomForest)              | 0.75     |
|  3. | LabelPropagation & LabelSpreading     | 0.07     |
