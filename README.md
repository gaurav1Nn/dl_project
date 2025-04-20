# Landscape Image Classification Project

## Problem Statement

The goal of this project is to develop a machine learning model that can accurately classify landscape images into six categories: buildings, forest, glacier, mountain, sea, and street. This involves leveraging various deep learning architectures to evaluate their performance on the Intel Image Classification dataset.

## Dataset

- **Dataset Link**: [Intel Image Classification Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification/code)

## Project Structure

- **Landscape_Identification.ipynb**: 
  - Data loading and preprocessing using `ImageDataGenerator`.
  - CNN model construction, training, and evaluation.

- **gaurav_nilawar_cnn(1).ipynb**: 
  - Alternative CNN architecture.
  - Class distribution exploration and visualization.
  - Model training and evaluation.

- **gaurav_nilawar_vgg19.ipynb**: 
  - Transfer learning with VGG19.
  - Model fine-tuning for classification.

- **resnet_gaurav_nilawar.ipynb**: 
  - ResNet architecture implementation.
  - Model training and evaluation.

## Key Techniques

- **Data Augmentation**: Enhances dataset size and model generalization with transformations like rotation and flipping.
- **Transfer Learning**: Utilizes pre-trained models (e.g., VGG19) for improved performance.
- **ResNet Architecture**: Employs skip connections to address the vanishing gradient problem.

## Results

- Models are evaluated based on accuracy and loss.
- The ResNet model achieved a test accuracy of approximately 79.8%.

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/gaurav1Nn/dl_project.git
2.**Install Dependencies**
 ```bash
    pip install tensorflow keras matplotlib numpy pillow
