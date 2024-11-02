# Rotten Fruit Classification

This repository contains the project for **CDS6334: Visual Information Processing**, comparing the effectiveness of various deep learning models in classifying rotten and fresh fruits. The study focuses on Convolutional Neural Networks (CNN), ResNet50, and MobileNetV3, aiming to identify the most effective model for accurately categorizing fruit quality.

## Models Compared
The following models were evaluated in this study:
1. **Convolutional Neural Network (CNN)**: A basic CNN architecture for image classification.
2. **ResNet50**: A 50-layer deep residual network known for its effectiveness in image recognition tasks.
3. **MobileNetV3**: An efficient model optimized for mobile applications, designed to provide high accuracy with lower computational costs.

## Dataset
- The dataset was sourced from Kaggle, containing over 1000 images of various fruits, categorized into fresh and rotten classes.
- Images were preprocessed to ensure consistency, including resizing to uniform dimensions and standardizing formats to JPEG and PNG.
- The dataset was split into training, validation, and test sets (60%, 20%, and 20%) to provide a fair comparison across models.

## Approach
1. **Preprocessing**: Images were resized and standardized. Data augmentation and transfer learning were applied to improve model robustness.
2. **Evaluation Metrics**: Models were assessed using accuracy, AUC-ROC scores, and confusion matrices to capture performance across various metrics.
3. **Training and Validation**: Each model was trained using identical training/validation splits to ensure a fair comparison.

## Key Findings
- **CNN**: Achieved 85.18% accuracy on the test set, but exhibited potential overfitting.
- **ResNet50**: Showed robust performance with a test accuracy of 99.72%, demonstrating effective generalization.
- **MobileNetV3**: Outperformed other models with a test accuracy of 99.81% and the highest AUC score, indicating its efficiency in classifying fruit quality.

## Conclusion
MobileNetV3 was identified as the best-performing model for this classification task, balancing accuracy with computational efficiency. The findings suggest that MobileNetV3 and ResNet50 are both suitable for high-accuracy image classification tasks, with MobileNetV3 being more resource-efficient.

## Future Work
Future improvements could include:
- Hyperparameter tuning for CNN to address overfitting.
- Use of ensemble models to combine strengths of multiple models.
- Application of regularization techniques to improve model generalization.

## License
This project is for educational purposes as part of coursework for CDS6334.
