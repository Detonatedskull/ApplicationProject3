# *Project: ASL Image Classification using Random Forest*
## Overview
This project is aimed at developing a classification model using the Random Forest algorithm to classify images captured from a camera into American Sign Language (ASL) letters. The model's purpose is to assist individuals with hearing impairments in communication by recognizing hand gestures and translating them into corresponding ASL letters.

## About the Developer
This project was created by Kiran Pillai, an AI and Machine Learning (AIML) developer passionate about leveraging technology to create solutions that enhance accessibility and improve lives. With a background in computer science and expertise in machine learning algorithms, Kiran has dedicated efforts to projects aimed at solving real-world problems and making a positive impact.

## How to Run
Then there are 4 files which have to be run in the order -> CollectImages.py-> Create_dataset.py-> Train_classifier.py-> inference_classifier.py. Else you can directly run the inference_classifier provided you have the model.p file and the data folder This is a test statement

### Project Details
#### >Objective
The primary objective of this project is to develop an image classification system capable of recognizing ASL letters from images captured by a camera. The system utilizes the Random Forest algorithm, a powerful ensemble learning method known for its robustness and effectiveness in handling classification tasks.

#### >Methodology
The project follows these key steps:

1. Data Collection: Gather a comprehensive dataset of images representing ASL letters. This dataset serves as the foundation for training the classification model.

2. Preprocessing: Preprocess the images to enhance their quality and ensure consistency in size and format. This step may include resizing, normalization, and noise reduction.

3. Feature Extraction: Extract relevant features from the preprocessed images to represent them in a suitable format for input to the Random Forest classifier. This may involve techniques such as pixel intensity values, edge detection, or feature descriptors.

4. Model Training: Train the Random Forest classifier using the extracted features and corresponding labels (ASL letters). The model learns to recognize patterns in the input data and make predictions based on these patterns.

5. Model Evaluation: Evaluate the performance of the trained model using appropriate metrics such as accuracy, precision, recall, and F1 score. This step ensures that the model generalizes well to unseen data and effectively classifies ASL letters.

6. Deployment: Deploy the trained model in a real-world environment, such as a mobile application or a web interface, where it can interactively classify ASL letters in real-time.

#### > Future Enhancements
While the current implementation focuses on ASL letter classification using Random Forest, several avenues for improvement and expansion exist:

1. Deep Learning Approaches: Explore deep learning architectures such as convolutional neural networks (CNNs) for image classification, which may offer higher accuracy and robustness.

2. Real-Time Performance Optimization: Optimize the model for real-time inference on resource-constrained devices to enable seamless integration into assistive technologies.

3. Multimodal Input Support: Extend the system to recognize ASL gestures from video streams or incorporate other sensor inputs for more comprehensive communication assistance.

## Conclusion
The ASL Image Classification project developed by Kiran Pillai aims to leverage machine learning techniques, particularly the Random Forest algorithm, to facilitate communication for individuals with hearing impairments. By accurately classifying ASL letters from camera images, the system contributes to enhancing accessibility and inclusivity in everyday interactions.
