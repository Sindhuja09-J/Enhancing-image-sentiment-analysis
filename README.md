# Enhancing Image Sentiment Analysis with CNN and Transfer Learning

This project focuses on facial emotion recognition through image sentiment analysis using deep learning. Two approaches are explored: a custom Convolutional Neural Network (CNN) and a Transfer Learning model using ResNet50. The goal is to classify emotions from facial images effectively and evaluate both models comparatively.

## 📌 Project Summary

- **Objective**: Predict human emotions from facial images using CNN and Transfer Learning techniques.
- **Models Used**:
  - Custom CNN built from scratch.
  - ResNet50 with a modified classification head for transfer learning.
- **Dataset**: CK+ (Extended Cohn-Kanade Dataset), containing labeled facial expression images.
- **Image Size**: All input images are resized to 224x224 pixels.

## 🧠 Features

- Preprocessing includes normalization and data augmentation.
- Comparative analysis between the CNN and ResNet50 models.
- Evaluation based on accuracy, precision, recall, and F1-score.
- Confusion matrix and classification report generated for detailed insights.

## 📊 Results

- **CNN Model Accuracy**: ~55%
- **ResNet50 Accuracy**: ~84%
- ResNet50 showed better generalization and higher precision, especially for emotions like anger, sadness, and surprise.
- CNN performed decently for visible emotions but struggled with subtle expressions.

## 🔬 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## 🛠 Future Enhancements

- Introduce attention mechanisms to focus on key facial regions.
- Use color and higher-resolution images.
- Extend to video-based emotion recognition.
- Deploy models on lightweight devices for real-time applications.

## ✅ Conclusion

This study shows that transfer learning (ResNet50) significantly boosts image sentiment analysis performance compared to a traditional CNN. The work demonstrates the potential of deep learning in emotion-aware applications for healthcare, education, and interactive systems.

