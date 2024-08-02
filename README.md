
# Plant Disease Classification Project

## Overview

This project focuses on fine-tuning a pre-trained model using the PlantVillage dataset for efficient plant disease classification. The process involves modifying certain parameters to enhance the model's performance on a new, smaller dataset, reducing both time and computational resources compared to training from scratch.

## Fine-tuning Techniques

The project incorporates several fine-tuning techniques:

- **Conv2D Layer:** Essential in CNNs, it applies learnable filters to extract local features from input images.
  
- **Global Average Pooling (GAP):** Minimizes the convolutional layer output before classification, providing efficient feature maps and preventing overfitting.

- **Batch Normalization:** Normalizes layer activations, enhancing stability and preventing extreme values during training.

- **Dropout:** Mitigates overfitting by randomly omitting input units during training cycles.

- **Dense Layers:** Crucial for regression and hierarchical functions, incorporating non-linear activation functions for effective learning.

## Key Features

- **Efficient Classification:** Achieved by leveraging fine-tuning techniques to optimize the model on a smaller dataset.

- **User-Friendly Interface:** Includes a custom prediction function for practical usability.

- **Insightful Visualizations:** Accuracy/loss curves and a confusion matrix provide valuable performance insights.

## Demo of the site I have created using FastAPI and Postman:
![Screenshot 2024-08-02 123530](https://github.com/user-attachments/assets/5f7480bf-8612-4ffb-a6da-a5f3c37ad7b1)

![Screenshot 2024-08-02 123705](https://github.com/user-attachments/assets/e3fa36e5-9b08-4451-ad35-8278bda545ec)

