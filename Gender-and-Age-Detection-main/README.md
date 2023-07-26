# Gender & Age Detection

This project aims to classify a person's gender and predict their age based on facial features. It utilizes the UTKFace dataset, which contains over 20,000 face images annotated with age, gender, and ethnicity.

## Dataset
The UTKFace dataset is a large-scale face dataset with a wide age span (0 to 116 years old). The images exhibit variations in pose, expression, illumination, occlusion, resolution, and more. It is suitable for various tasks such as face detection, age estimation, age progression/regression, and landmark localization.

## Models
Several models were evaluated for gender and age classification, including CNN, CNN with skip connections, AlexNet, ResNet, and transfer learning models like VGGNet and InceptionV3.

## Results
The models were compared based on accuracy and loss. The CNN with skip connections achieved the highest accuracy, while other models like GoogleNet and ResNet performed less effectively. Age prediction accuracy was affected by unpredictable variables like plastic surgery and makeup.

## Usage
To use this project, follow these steps:
1. Download the UTKFace dataset.
2. Train the desired model using the provided code.
3. Evaluate the model's performance on test data.
4. Use the trained model for gender and age prediction on new images.

## Further Improvements
Possible areas for improvement include:
- Fine-tuning the models to handle unpredictable variables better.
- Exploring other pre-trained models or advanced architectures.
- Augmenting the dataset to increase diversity and robustness.

