# Gender & Age Detection

## Introduction
The objective of this project is to classify a person's gender and predict their age by analyzing facial features. The UTKFace dataset, consisting of over 20,000 face images with annotations of age, gender, and ethnicity, is used for training and testing the models.

## Metadata
The UTKFace dataset is a large-scale face dataset with a wide age span, ranging from 0 to 116 years old. It includes face images with variations in pose, expression, illumination, occlusion, resolution, etc. The dataset is suitable for tasks like face detection, age estimation, age progression/regression, and landmark localization.

## Applications and Challenges
- Age and gender classification can enhance computer perception and interaction capabilities, enabling customized services based on gender and age.
- Age classification can be used to restrict access to inappropriate content for children and assist in recruitment processes.
- Applications include forensic departments, banking sector, ADHAAR database, criminal investigation, and surveillance monitoring.

## Models
Several models were evaluated for gender and age classification, including baseline CNN, CNN with skip connections, AlexNet, ResNet, and transfer learning models like VGGNet and InceptionV3.

## Comparison
Here is a comparison of the models based on accuracy and loss:

| Model                      | Accuracy | Loss   |
|----------------------------|----------|--------|
| Transfer Learning with VGGNet | 77.44%   | 49.33% |
| InceptionV3                | 74.64%   | 56.15% |
| AlexNet                    | 61.44%   | 47.66% |
| CNN                        | 85.47%   | 42.81% |
| CNN with Skip Connections  | 87.56%   | 27.22% |
| ResNet                     | 51.23%   | 80.99% |



## Results & Comments
The base CNN model achieved high accuracy, and the CNN with skip connections performed even better. However, models like GoogleNet, ResNet, and AlexNet had lower accuracy. Age prediction accuracy was affected by unpredictable variables like plastic surgery and makeup.

Hyperparameter reasoning: The RMSprop optimizer was used to maintain a moving average of squared gradients, allowing larger steps for faster convergence.

Hyperparameters: Learning rate of 10^(-3) and batch size of 64 yielded the best accuracy.

