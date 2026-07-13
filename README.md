# Cat vs Dog Image Classifier

A deep learning image classification project that classifies images as either cats or dogs using transfer learning with MobileNetV2 and TensorFlow.

## Project Overview

This project explores the complete workflow of building an image classification model using transfer learning. A pretrained MobileNetV2 model is used as a feature extractor and later fine-tuned to better adapt to the cat and dog classification task.

## Technologies Used

* Python
* TensorFlow
* Keras
* MobileNetV2
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Model Architecture

The project uses MobileNetV2 pretrained on ImageNet.

The initial training stage freezes the pretrained MobileNetV2 layers while training the classification head.

After initial training, the final 20 layers of MobileNetV2 are unfrozen and fine-tuned using a lower learning rate.

## Project Workflow

1. Dataset loading and exploration
2. Image preprocessing and normalization
3. Data augmentation
4. MobileNetV2 transfer learning
5. Initial model training
6. Callback implementation
7. Model fine-tuning
8. Training and validation curve analysis
9. Model evaluation
10. Prediction on unseen images
11. Model saving and loading

## Training Techniques

The project implements:

* Data augmentation
* Transfer learning
* Early stopping
* Model checkpointing
* Learning rate reduction
* Fine-tuning

## Results

The model achieved approximately **97% validation accuracy**.

Training and validation curves were analysed to monitor model learning and identify potential overfitting.

Fine-tuning allowed the pretrained MobileNetV2 features to adapt further to the classification task.

## Future Improvements

* Deploy the model as a web application
* Expand the dataset
* Compare MobileNetV2 with other pretrained architectures
* Add a simple user interface for image upload and prediction

## Author

**Ezeji Godswill**

Biomedical Engineering Student
AI/ML in Healthcare
