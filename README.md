# Cat-vs-Dog-Classifier
This is a course project completed with  an other student

Cat vs. Dog Classifier is a transfer learning-based image classification project that uses MobileNetV2 to distinguish between cat and dog images, achieving a validation accuracy of 96.5%. The project demonstrates efficient model training and edge device deployment capabilities
## Function
- Use MobileNetV2 for binary classification of cat and dog images.
- Apply data augmentation (rotation, flipping, scaling) to improve model generalization capabilities.
- Use Grad-CAM to generate heatmaps to explain the model decision process.
- The model size is only 45 MB, suitable for deployment on edge devices.

## Technology Stack
- **Language**: Python
- **Framework**: TensorFlow 2.12.0, ImageDataGenerator
- **Visualization**: Matplotlib, Seaborn
- **Dataset**: Kaggle Dogs vs Cats (10,000 images)

## Results
- **Validation accuracy**: 96.5% (training accuracy 98.2%).
- **Classification Report**:
- Cat: Precision 96.3%, Recall 97.0%, F1 score 96.6%. 
- Dog: Precision  96.7%, Recall 96.0%, F1 score 96.3%.
- **Model size**: 45 MB, efficient and suitable for edge devices.
- **Grad-CAM**: The model focuses on key features such as head and torso to prove decision reliability.
