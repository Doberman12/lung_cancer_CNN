# Lung Cancer Image Classification using CNN

## Description

This project uses **Convolutional Neural Networks (CNN)** to classify histopathological images of lungs. The goal is to automatically recognize three categories: **adenocarcinoma**, **healthy lungs**, and **squamous cell carcinoma**.

## Dataset

The project uses the publicly available dataset "**Lung Cancer Histopathological Images**" from Kaggle. The dataset contains histopathological lung images, divided into three categories.

## Model

Two CNN models were built:

1. **Custom Model:** A CNN model designed from scratch with multiple convolutional layers, max pooling, and dense layers.
2. **Pretrained Model (VGG16):** A pretrained VGG16 model with ImageNet weights, enhanced with custom classification layers.

## Results

Both models achieved high accuracy on the validation set:

* **Custom Model:** 
    * **97.20%** (last epoch)
    * **98.16%** (average of the last 5 epochs)
    * **99.07%** (highest value)
    
* **VGG16 Model:**  
    * **97.70%** (last epoch)  
    * **97.71%** (average of the last 5 epochs)  
    * **97.77%** (highest value)

## Instructions

To run the project:

1. Download the dataset "**Lung Cancer Histopathological Images**" from Kaggle.
2. Import the notebook into **Google Colab**.
3. Install the required libraries:
    ```bash
    pip install tensorflow keras scikit-learn seaborn
    ```
4. Run the notebook.

## Conclusion

This project demonstrates that CNNs can be effectively used for the classification of histopathological lung images. Both models achieved high accuracy, suggesting their potential for medical applications.
