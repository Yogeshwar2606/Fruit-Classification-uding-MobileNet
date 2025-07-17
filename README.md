#  Fruit Classification using CNN & Transfer Learning

##  Overview
This project focuses on classifying 33 categories of fruits using deep learning techniques. We trained both a custom CNN model and a MobileNet-based model to identify fruits with high accuracy. The goal is to build a robust, efficient system suitable for real-world applications like grocery store automation, sorting lines, or mobile food recognition.

##  Techniques Used
- **Convolutional Neural Networks (CNN)**: For learning spatial features from fruit images.
- **Transfer Learning (MobileNet)**: To leverage pre-trained knowledge and speed up convergence.
- **Image Normalization**: Ensures faster and more stable training.
- **Training & Validation Splits**: Enables fair evaluation of model generalization.

##  Dataset
- 33 fruit classes with hundreds of images each.
- Images resized to 224x224 pixels.
- Data loaded using `image_dataset_from_directory`.
- Invalid/corrupted images filtered using a PIL-based script.

##  Results
- **Training Accuracy**: ~98.6%
- **Validation Accuracy**: ~100%
- Model generalized well across all classes with minimal overfitting.


##  Future Improvements
- Add model explainability using Grad-CAM or similar techniques.
- Deploy the model as a web/mobile app with real-time image capture.
- Expand dataset with more fruit classes and environmental variations.

##  Conclusion
We built a highly accurate fruit classification system using deep learning and transfer learning. The MobileNet model achieved impressive results with efficiency and speed, making it suitable for deployment in real-world scenarios.

---

