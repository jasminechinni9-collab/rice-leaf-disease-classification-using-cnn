# Rice Leaf Disease Classification Using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify rice leaf diseases from images. The model identifies three types of rice leaf diseases: Leaf smut, Brown spot, and Bacterial leaf blight.

## Objective
The main objective is to identify rice leaf diseases using image classification and deep learning techniques.

## Dataset Description
The dataset contains images of three rice leaf disease classes:
- Leaf smut
- Brown spot
- Bacterial leaf blight

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow
1. Data Exploration
2. Image Resizing
3. Image Normalization
4. Label Encoding
5. Data Augmentation
6. CNN Model Building
7. Model Training
8. Model Evaluation

## Model Architecture
A CNN model was developed using convolutional layers, MaxPooling layers, and Dropout to classify rice leaf disease images.

## Model Performance

Two CNN models were trained and evaluated.

| Model | Test Accuracy |
|---|---:|
| CNN Model 1 | 87.50% |
| CNN Model 2 | 58.33% |

CNN Model 1 was selected as the final model based on its better test accuracy.

## Evaluation Metrics
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The Brown spot class achieved the lowest F1-score of 85.71%.

## Conclusion
The project successfully developed a CNN-based model for rice leaf disease classification. The model achieved 87.50% test accuracy. The dataset size was a limitation, and Transfer Learning models such as MobileNet can be explored in the future to improve performance.

## Future Improvements
- Increase the dataset size.
- Explore Transfer Learning models such as MobileNet.
- Improve model generalization.
