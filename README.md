# Image recognition with Teachable Machine
In this repository a simple image classification project built using **Google's Teachable Machine**.

## Project Structure
The repository is orgnized as follows:
 * keras_model.h5 -The trained Keras model
 * labels.text - Class lables (car, motorcycle, bicycle)
 * predict.ipynb - Google Colab / Jupyter Notebook
 * images (26) - Sample image for testing

## Project Idea
The goal of this project is to build an intelligent vehicle classification model that automatically recognizes and differentiates between three common types of road vehicles: **Cars**, **Motorcycles** and **Bicycles**.


**Dataset & Trainig**

The model Trained using **14-15 diverse images per class** taken from **diffrent angles, prespictive and environmental conditions** to ensure high accuracy and robustness.

Below is a screenshot of the dataset and calsses configured inside Google's Teachable Machine: 

<img width="1326" height="910" alt="‪Image Model - Teachable Machines" src="https://github.com/user-attachments/assets/c850482e-71fe-438a-9b57-ed2b9e1d06b0" />

## Results
Below is a screensshot of the model running successfully inside Google Colab and predicting the vehicle type correctly: 

<img width="1161" height="427" alt="‪predict ipynb - Colab - Google Chrome‬ 14_07_2026 03_03_37 PM" src="https://github.com/user-attachments/assets/9e795e26-0b0a-46c3-9b46-36200e09372e" />
