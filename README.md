# Automatic-Classification-of-Digestive-Tract-Disorders-in-Endoscopy-Images-using-CNNs
- **Overview**
 This project aims to enhance the diagnostic process for gastrointestinal (GI) tract disorders by automatically classifying endoscopic images. Leveraging the Kvasir dataset, we applied image preprocessing and deep learning techniques to improve diagnostic accuracy for GI disorders such as peptic ulcers, polyps, and esophagitis. Our model employs Convolutional Neural Networks (CNNs) with InceptionV3 and ResNet50V2 architectures to achieve robust classification results, helping medical professionals efficiently identify digestive tract conditions.

- **Dataset**
- Name: Kvasir Dataset
- Description: The Kvasir dataset consists of 3,500 labeled GI tract endoscopy images across multiple classes, specifically designed for training and evaluating computer vision models for digestive tract disorders.
- Classes: Normal, Esophagitis, Polyps, and Ulcerative Colitis.
- Link: Kvasir Dataset on Kaggle Link: https://www.kaggle.com/datasets/meetnagadia/kvasir-dataset

- **Image Preprocessing**
  To enhance feature extraction and model performance, we applied Contrast Limited Adaptive Histogram Equalization (CLAHE). CLAHE improves image contrast by adjusting histogram distribution, making critical features more distinguishable and aiding in the classification process.

- **Model Architecture and Training**
We used two CNN architectures:
- InceptionV3
- ResNet50V2
Training Metrics:
ResNet50V2 achieved a training accuracy of 100% and a validation accuracy of 92.71%.
Training Details:
- Loss Function: Categorical Crossentropy
- Otimizer: Adam
- Learning Rate: 0.001
- Batch Size: 32

- **Results**
ResNet50V2 outperformed other models, achieving high accuracy on both training and validation data.
- Training Accuracy: 100%
- Validation Accuracy: 92.71%
These results indicate the potential of CNNs to assist in diagnostic decision-making by providing rapid, automated classification of GI disorders.

- **Conclusions**
Our model demonstrates that deep learning, specifically CNNs, can accurately classify endoscopic images into diagnostic categories. This work supports the development of AI-based tools for GI diagnosis, potentially reducing diagnostic time and aiding in early detection and treatment.

_ **Future Work**
Further testing with more diverse and larger datasets.
Incorporating additional image preprocessing techniques.
Exploring other CNN architectures for improved performance.
