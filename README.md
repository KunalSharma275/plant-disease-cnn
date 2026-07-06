# 🌿 Plant Disease Detection Using Deep Learning

## Project Overview

This project implements an automated plant disease detection system
using Deep Learning with TensorFlow/Keras. The notebook downloads the
complete 38-class PlantVillage dataset, preprocesses the images, trains
multiple deep learning models, evaluates their performance, and compares
the results.

The project demonstrates both a custom Convolutional Neural Network
(CNN) and a MobileNetV2 Transfer Learning model for multiclass image
classification.

## Features

-   Automatic download of the PlantVillage dataset
-   Dataset validation and corrupted image removal
-   Dataset summary and visualization
-   Class distribution analysis
-   Image preprocessing
-   Data augmentation
-   Train/Validation/Test split (70/15/15)
-   Custom CNN implementation
-   MobileNetV2 Transfer Learning
-   Model training and evaluation
-   Accuracy and loss visualization
-   Confusion matrix
-   Classification report
-   Model comparison
-   Save trained model for future predictions

## Dataset

This project uses the **PlantVillage Dataset**, containing over 54,000
leaf images across 38 disease classes.

## Technologies Used

-   Python
-   TensorFlow
-   Keras
-   NumPy
-   Pandas
-   Matplotlib
-   Pillow (PIL)
-   Scikit-learn
-   tqdm

## Project Structure

``` text
plant-disease-cnn/
│
├── UC-17233.ipynb
├── Proposal.docx
├── README.md
├── requirements.txt
└── trained_model.keras
```

## Installation

``` bash
git clone https://github.com/KunalSharma275/plant-disease-cnn.git
cd plant-disease-cnn
pip install -r requirements.txt
```

## Running the Project

Open `UC-17233.ipynb` and run all cells. The notebook downloads the
dataset, preprocesses images, trains both models, evaluates them, and
saves the trained model.

## Model Architectures

### Custom CNN

-   Convolution + MaxPooling
-   Batch Normalization
-   Dropout
-   Dense Layers
-   Softmax Output

### MobileNetV2

-   Transfer Learning
-   Fine-tuning
-   Softmax Classification Layer

## Evaluation

The notebook reports: - Training, validation, and test accuracy - Loss
curves - Confusion matrix - Classification report

## Author

**Kunal Sharma**

## License

This project is provided for educational purposes.
