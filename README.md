Emotion Detection
Description
This project is an emotion detection system that predicts emotions from text using machine learning. It employs TF-IDF vectorization for feature extraction and an SVM (Support Vector Machine) model for classification. The system can classify emotions such as joy, sadness, and anger based on input text.
Dataset Overview
* The dataset consists of 16,000 rows and 2 columns: 
1. Comment – The text input expressing an emotion.
2. Emotion – The corresponding emotion label (sadness, joy, anger, love, etc.).
* The dataset is used to train the emotion detection model by mapping textual data to emotion categories.
Libraries Used
* scikit-learn (Machine Learning)
* joblib (Model Saving & Loading)
* neattext (Text Cleaning)
* numpy (Array Operations)
* pandas (Data Handling)
Model Used
* Support Vector Machine (SVM) for emotion classification.
* TF-IDF Vectoriser for text feature extraction.
